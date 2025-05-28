# 📚 Book Search Engine

A full-stack MERN application that lets users search for books using the Google Books API, create an account, log in, and save their favorite books. This app provides a seamless experience for browsing and storing books of interest.

## 🚀 Features

- 🔍 Search for books via the Google Books API
- 🧾 View book details: title, author, description, cover image, and link to the book
- 🧑‍💼 User authentication with Login/Signup modal
- 💾 Save and view a personal list of favorite books
- ❌ Remove books from your saved list
- 🔐 Session-based authentication with personalized UI changes

## 📖 User Stories

- **GIVEN** a book search engine  
  **WHEN** I load the site  
  **THEN** I see a navigation menu with options: _Search for Books_, _Login/Signup_, and a search input field

- **WHEN** I click on _Search for Books_  
  **THEN** I see a search field and a submit button

- **WHEN** I am not logged in and perform a search  
  **THEN** I see search results including the book’s title, author, description, image, and a link to Google Books

- **WHEN** I click _Login/Signup_  
  **THEN** a modal appears with toggle options to _Login_ or _Signup_

- **WHEN** I choose _Signup_  
  **THEN** I see inputs for a username, email, and password, and a signup button

- **WHEN** I choose _Login_  
  **THEN** I see inputs for email and password, and a login button

- **WHEN** I sign up with valid credentials  
  **THEN** I am registered and logged in automatically

- **WHEN** I log in with valid credentials  
  **THEN** the modal closes and I see options for _Search for Books_, _Saved Books_, and _Logout_

- **WHEN** I perform a search while logged in  
  **THEN** I can see book results and click a _Save_ button to add a book to my account

- **WHEN** I click _Saved Books_  
  **THEN** I see a list of all books I’ve saved with their details and a _Remove_ button

- **WHEN** I click the _Remove_ button on a book  
  **THEN** that book is removed from my saved list

- **WHEN** I click _Logout_  
  **THEN** I am logged out and the original menu appears

## 🛠️ Tech Stack

- **Frontend**: React, Bootstrap, Apollo Client
- **Backend**: Node.js, Express, Apollo Server
- **Authentication**: JWT
- **Database**: MongoDB with Mongoose
- **API**: Google Books API
