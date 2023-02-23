## Objective
Build a simple web application that allows users to search for books using the Open Library API and display the search results. Users should be able to select a book from the search results to view more details about the book.

## Requirements
- Use React and Redux to build the application.
- Use the GoodReads API to search for books. The API documentation can be found here: `https://www.goodreads.com/api/index`. You will need to create a GoodReads account to get an API key: Navigate to `https://www.goodreads.com/api/keys` and apply for an API key. For “Application name” and “Company name” feel free to just write whatever you want and no need to include an application URL, callback URL, or support URL. You should then see your API key. (For this project, we’ll care only about the “key”, not the “secret”.)
- Display the search results as a list of books with their titles, authors, cover images and ratings.
- When a user clicks on a book from the search results, display more details about the book, including its title, author, cover image, publication date, and a brief description.
- Write unit tests for your components using Jest.

## Evaluation Criteria
- The code should be well-organized and maintainable.
- The application should be responsive and easy to use.
- The Redux store should be used to manage the state of the application.
- The application should handle errors gracefully and display meaningful error messages to the user.
- The unit tests should be comprehensive and cover all important functionality.

## Bonus
- Allow users to add books to a "favorites" list.
- Add pagination to the search results if there are more than 20 results.
- Use TailwindCSS to style the application.

## Submission
- The interviewee should provide a GitHub repository containing the code for the application, along with instructions for running the application locally and running the tests. The repository should also include a README.md file with a brief overview of the application and any additional notes or comments the interviewee would like to provide.