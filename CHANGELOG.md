v0.3.0 - 2021 - 07 - 14

- A sign-up page and a login page were added to the website.
- Now, users are only abble to access the main page of the website if they are authenticated.
- Added a users class on Back4App, which is updated when a new user signs up.
- If a user tries to access the protected route with a login and password that are not registered on the database, a message requesting the user to login again will be displayed.
- After the user has already logged in and accessed the protected route, it is not possible to route to the login and sign-up pages.
- The protected route accessed after the user logs in is similar to the page from feature 4, with a few minor changes.
