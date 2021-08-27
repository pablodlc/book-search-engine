# **BSE**: book-search-engine

Please visit the deployed application by clicking the following link: [**BSE**]().  
A video about **BSE** can be found here: [**BSE** on YouTube!](https://www.youtube.com/watch?v=W5e_aKWikWQ)

![BSE](./client/assets/BSE-saved.png)

### Table of Contents

-   [Description](#description)
-   [User Story](#user-story)
-   [Acceptance Criteria](#acceptance-criteria)
-   [Questions](#questions)

## Description

book-search-engine (which I call **BSE** for short) is a MERN-Stack app powered by Apollo Server and GraphQL on the backend. BSE features authentication utilizing _bcrypt_, _jsonwebtoken_, and _jwt-decode_ dependencies in order to feature signup, log in, and log out functionality. Once logged in, user's can search books for data about the book: author, title, a description, and an image of the book cover. On the bottom of cards that generate based on the user's input, there is a button that reads, "Save This Book!". Clicking that button saves that book to the user's book list. Also, after clicking, the button's text changes to, "Book Saved!" so the user knows the save was successful. After books are saved from the search, the user can then navigate to their book list by clicking the `See Your Books` link at the top of the nav bar. This page will display cards with all of the books saved by the user. At the bottom of these cards is a button that reads, "Delete This Book!" which removes the book from their list.

## User Story

> AS AN avid reader  
> I WANT to search for new books to read  
> SO THAT I can keep a list of books to purchase

## Acceptance Criteria

> GIVEN a book search engine  
> WHEN I load the search engine  
> THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  
> WHEN I click on the Search for Books menu option  
> THEN I am presented with an input field to search for books and a submit button  
> WHEN I am not logged in and enter a search term in the input field and click the submit button  
> THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site  
> WHEN I click on the Login/Signup menu option  
> THEN a modal appears on the screen with a toggle between the option to log in or sign up
> WHEN the toggle is set to Signup  
> THEN I am presented with three inputs for a username, an email address, and a password, and a signup button  
> WHEN the toggle is set to Login  
> THEN I am presented with two inputs for an email address and a password and login button  
> WHEN I enter a valid email address and create a password and click on the signup button  
> THEN my user account is created and I am logged in to the site  
> WHEN I enter my account’s email address and password and click on the login button  
> THEN I the modal closes and I am logged in to the site  
> WHEN I am logged in to the site  
> THEN the menu options change to Search for Books, an option to see my saved books, and Logout  
> WHEN I am logged in and enter a search term in the input field and click the submit button  
> THEN I am presented with several search results, each featuring a book’s title, author, description, image and a link to that book on the Google Books site and a button to save a book to my account  
> WHEN I click on the Save button on a book  
> THEN that book’s information is saved to my account  
> WHEN I click on the option to see my saved books  
> THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account  
> WHEN I click on the Remove button on a book  
> THEN that book is deleted from my saved books list  
> WHEN I click on the Logout button  
> THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button

## Questions?

Please feel free to contact me with any questions or comments, or visit my GitHub to see more of my work.

-   [Contact me by email](mailto:pablodlc@gmail.com)
-   [GitHub User pablodlc](https://github.com/pablodlc)
-   [**BSE** GitHub Repo](https://github.com/pablodlc/book-search-engine)

**BSE** made with ❤️ by pablodlc
