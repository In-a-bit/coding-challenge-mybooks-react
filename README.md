# My Books Web Application - Coding Challenge

Hello! We are really excited getting to know you, and would like also to know how it is to be working with you.

We would like to ask you to complete this relatively small project to help us understand how you approach, design and express your solutions.

Please see this is less then a rigid test, and more of an opportunity to express yourself and show your love for coding.

This exercise is also available online on our [Github site](https://github.com/In-a-bit/coding-challenge-mybooks-react/)

## Specs

Please create a books favorites organizer system.

* The system should consist only of **frontend web application**.
  * If data is needed to be saved, the browser facilities should be used instead of a backend app.
* **Login screen** that does a fake login
  * No authentication needed. The user is transferred to the next page after login
* Books list screen
  * **Book list** - The list is fetched from google books api. The API can be used without authentication for GET queries.(The `key` prop can be removed from the URL query).
  * **Book item** - Each book will be presented in a box detailing some of the book main **details**.
  * **Pagination** controls that will allow to fetch **next/previous** page of books
  * **Show-More** - Each book will have a show-more button that will **transfer or open another** window showing the book **details in depth**.
  * **Favorite** - Each book will have a **favorite-toggle button** that will **save** the book to the user favorites. If the book is already in the favorites list, then it need to be **shown as such**.
  * **Bonus - Favorite page** - A page that show only the the favorites books of the user.

## Instructions

* Create this application using React. You can use any UI components library you already know. We recommend [MUI](https://mui.com/).
* Please provide the project as a public Github project.
* Bonus - Host the app somewhere (Ex github pages, netlify..) where it will easily be seen and played from the start.

## References

* [google books api](https://developers.google.com/books/docs/v1/using#WorkingVolumes)
