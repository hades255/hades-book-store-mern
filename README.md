## :book:M.E.R.N Book Search Engine


## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Installation](#installation)
- [Local Usage](#Local-Usage)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Application Screenshot Preview](#application-screenshot-preview)
- [Resources & Credit](#resourcescredit)
- [License](#License)

## Description

This MERN stack application is a book search engine that allows users to search for books, view detailed information about them, and save them to their account. The app uses the Google Books API to fetch book data and stores all user transactions with MongoDB and Mongoose. With high-level authentication using tokens and JWT-decode, users can securely access and manage their saved books.

## User Story

```md
- AS AN avid reader
- I WANT to search for new books to read
- SO THAT I can keep a list of books to purchase
```

## Installation

1. To install application, clone the main project via the HTTP or SSH link on github.

```
git clone
```

2. Once cloned, open the project folder in your text editor and run the following command in terminal to install all dependencies.

- Important note - You will need to run the below command in the 'root', 'client' and 'server' directory paths.

```
npm install
```

## Local-Usage

- To use the MERN Book Search Engine on your local machine, follow these steps:

1. Clone the project repository to your local machine using the following command:

```md
git clone 'https://github.com/hades255/hades-book-store-mern.git'
```

2. Install the project dependencies by running the following command from the project root directory:

```md
npm install
```

3. Start the development server by running the following command:

```md
npm run develop
```

4. Open your browser and navigate to http://localhost:3000 to access the application.

- You can now use the search engine to find books, create an account, save books, and view your saved books list. Note that you will need to have MongoDB installed and running on your machine to use the application.

## Technologies Used

- ![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)
- ![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
- ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
- ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
- ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
- ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

## Features

- The MERN stack book search engine has the following features:

- 1. A user-friendly interface that allows users to search for books by title, author, or keyword.

- 2. Detailed information about each book, including the title, author, description, image, and a link to the book on the Google Books site.

- 3. Secure user authentication with tokens and JWT-decode, ensuring that each user can only access their own data.

- 4. User account creation and login functionality, with options for both new and returning users.

- 5. A saved books page that displays all the books a user has saved to their account, with options to remove books from the list.

- 6. A menu that changes dynamically based on the user's authentication status, showing options for searching books, viewing saved books, and logging out.

- 7. High-performance server-side rendering using React and Apollo Client, ensuring a smooth user experience.

- 8. Modern, clean, and responsive UI design.

- 9. ll transactions are stored with MongoDB and Mongoose, ensuring data security and reliability.

- 10. User-friendly error handling with informative error messages and clear user feedback.

- 11. Scalable architecture that can be easily extended and customized with additional features and functionality.

## Application Screenshot Preview

![ScreenShot-1](./assets/mern_book_search_1_screenshot.png)

##

![ScreenShot-2](./assets/mern_book_search_2_screenshot.png)

##

![ScreenShot-3](./assets/mern_book_search_3_screenshot.png)

## Resources/Credit

- Starter Code Provided by : University of Miami

- Author: Martin Cespedes - [Link to my Github](https://github.com/MartinCespedes)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

```
This project is covered under the MIT License.
```
