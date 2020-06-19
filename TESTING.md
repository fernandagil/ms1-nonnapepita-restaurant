# Testing

## Code validators

[Markup Validator](https://validator.w3.org/) : the test returned an error that was solved by adding an empty value attribute. The warnings were ignored since they were design decisions. 

![Markup Validator](htmlvalidator.png)

[CSS Validator](https://jigsaw.w3.org/css-validator/) : the test didn't find any errors.

## Responsiveness

To test the responsiveness of the site I used [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) and [Responsive Design Checker](https://www.responsivedesignchecker.com/).
![Responsive Design](responsiveness.png)

Notes:

- The design is responsive in most screen sizes. The only issue that I've found is that on a 10'' Notebook screen the jumbotron on "Home Page" might overflow a small bit.

## Browser compatibility

![Browser Compatibility](compatibility.png)

Notes:

- The site renders quite good on Firefox, although on the **Menu Page** the headings show a white overlay/background.
- On Microsoft Edge and Internet Explorer, the call to action button on **Home Page** doesn't seem to show the background color, but thanks to the border that does display properly it's easy to still see that is a button.

## Testing User stories

- As an owner, I want to show off what we can do to attract more clients.

This is shown mainly through the Restaurant’s Menu on the **Menu Page**, where customers can see which dishes are offered, but also through some of the pictures alongside the site.

- As an owner, I want to offer the possibility to book online to avoid unnecessary calls during busy hours.

  and
- As a person celebrating a special occasion, I want to be able to book a table in advance so nothing goes wrong.

This is possible through the Reservation Form on the **Home Page**. Because some users might have not seen this form, they might instinctively go to the **Contact Page** to make a reservation, there they'll find a link to go back to the Reservation Form in **Home Page**.

- As an owner, I want my website to be easy recognisable through the icon in the tab and also through the name on the fixed navbar while the customers are navigating through the site.

The website has a consistent design: the business’ name is on the top left side of the fixed menu and it can be seen every moment; and there is a favicon that makes the website recognisable when the user has multiple tabs open. 

- As a user, I want to be able to get in touch with the restaurant for any reason.

The **Contact Page** is easily accessible any time on the fixed menu on the top of every page.

- As a user, I want to be able to check the opening hours and to see the restaurant's location.

The opening hours can be seen in the Where to find us Section on the **Home Page**. The restaurant’s address can also be found in that section and also in the footer at the end of every page. There is an embed Google Maps in the Where to find us Section and in the **Contact Page** to make it easier to the users to visually recognise the restaurant’s location.

- As a curious user, I want to know more about the owner's stories.

There is a short introduction about the restaurant’s owners on the **Home Page**. To get to know them in more detail, the user can click in the Read more Button or on About us on the fixed navbar at the top of the page. Both options will lead to the **About us Page** where the user can see pictures and small biography of the owners.

- As a person with an allergy, I want to be able to check out the menu in advance to see if this place is a good option for me.

In the **Menu Page** the user can see a small icon telling which of the dishes are gluten free or vegetarian. In addition, when making a reservation on **Home Page**, they can specify the allergies the customers have and request a modification.

- As a regular customer, I want to check out the menu before my next visit so I can check out if there are any new dishes.
  
  and
- As a potential client, I would like to see the the menu and compare it to other places regarding ingredients, prices, etc.

This is easy accessible on the **Menu Page**. The user can access this from every page on the site by just clicking on the navbar.


## Bugs 

- One of the major bugs I found during the development process was the overflowing jumbotron on mobile's landscape mode. 

This was solved by adding some media queries to make reduce some margins and paddings.


## Bugs to be fixed

- When using Firefox, the white overlay on headings on the **Menu Page**.

[Go back to README.md file](../README.md).

