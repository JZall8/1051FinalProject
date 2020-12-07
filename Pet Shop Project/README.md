Reflection:
- What we learned: 
    - if something doesn't work, start researching and testing things to find solutions
    - keep the urls where we get the code and templates from, so that it is easier to do the citation later on 
    - coding is full of iteration and testing 
- What we enjoyed:
    - debugging
    - making the website look nice and creative thinking
    - learning more about html, css, and javascript

Unfinished Tasks:
- When user clicks the "add to cart" button for a product, the product is added to the checkout page, and the number, 0, next to the shopping cart symbol on the navbar will be updated.
- When user clicks the "x" button on the checkout page, the product will be deleted.
- Setting up the account page and linking it to the sign in page.
- A sticky navbar: The navbar was sticky at 1st, but we later lost it when we added the bootstrap.min.css and all.min.css.
- On the login page, linking the forgot password to a page to reset a password, and obtaining account information for a user to make an account (Which includes getting the remember password to save login information).
- Save the registration form to meet a pet in the available pets page.

Difficulties That We Overcame:
- On the pet page, the positions of the flipping circles were not responsive to the screen size. On Jenny's screen, everything looked fine. However, on Jacob's screen, which is much bigger than Jenny's screen, the flipping circles were all over the place. Initially, we used "vh/vw" to position the flipping circles, so they should be responsive to screen size, but they were not in good positions. We adjusted the y-values/y-positions for height and used "px" instead of "vh/vw", but it didn't work. Next, we researched on Google about making things responsive to screen size, and one of the things that popped up was position property in css, so we looked up different position properties. We didn't know which property is the right one to use, so we started testing and ended up with the "abosulte" position property. Next, we adjusted the position of each flipping circle while setting all of them to "aboslute", and it worked.

- Shopping cart: from the old one to the new one ("view compilled", making products slide horizontally as the mouse hovers over them: instead of puting the Javascript code in a different file and link it to the html, we put it in the html file with the "script" tag).

- Figuring out how to adjust the given flipping circle code, so that it fits into our website, such as making the flipping circles bigger and moving them: by testing.

- On the login and register pages, formatting the css so that it is centered. We also had difficulties with the remember password checkbox icon to allow it to be checked with a checkmark as it orignally only showed a white box. We editted the checkout in the css and reformatted the html to get it to work.

- Positioning the logo (home page), other pages, and icons on the navbar and top navbar. Originally it was difficult to increase the size of the logo because it would make the height of the navbar too large and move around the other text and icons. We found a good size for the logo and then adjusted the texts to get it to look nice and then after that we were able to add the cart icon easily.

- Getting all of the footer sizes and the text position to be the same on all of the pages. Some of the pages had a slightly different size than others and we knew this was being caused in the css's so we changed the margins in the html file to fix this.
