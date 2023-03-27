# BookStoreApplicationProject

I have creted a book store and access application, where user can access the books and also able to add books to the list of books avaiable.

I have used technologies like Express JS, Node JS, React JS and SQLite to develop the application.

To run the application on VS Code, use npm run pavan , so that the app will run on some port in the browser.

Firstly I have created a database bookStore.db and created table and some list of books by INSERT method of SQLite.

Created a Node JS project and connected to Database using using OPEN method of sqlite (by installing third party package) and also by creating API's to get access to the books 

avaiable in database(GET METHOD used)

AXIOS third party package with method get is used to fetch information(array of objects) from backend to frontend

Created a component that uses the fetched data and displays the list view of books by using map method of arrays and also made some styling using CSS as well

Inbuilt Link component is used to navigate between list view and FormField component(which has form elements to collect the book details to store it in database)

AXIOS.post method is used to post the added book details to the backend.
