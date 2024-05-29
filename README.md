# Book Palace

## Project Description
Book Palace is an innovative online bookstore that enables users to explore, search for, and purchase their favorite books with ease. The project aims to provide a seamless and interactive shopping experience for book lovers, featuring a wide range of genres, authors, and best-selling titles.

## Usage Scenarios
1. **Exploring Books:** Users land on the homepage, where they can browse through various genres and new releases.
2. **Searching for Books:** Users utilize the search bar to find specific books based on titles or authors.
3. **Viewing Book Details:** By clicking on a book, users can access detailed information about the book, such as synopsis, author, and price.
4. **Adding Books to Cart:** Users can add books to their shopping cart and proceed to checkout.
5. **Managing User Profile:** Users can create an account, log in, and manage their profile and order history.

## Instructions for Running the Project Using Yarn
To run Book Palace locally with Yarn, follow these steps:

1. **Clone the repository**:
   - Use the command: `git clone https://github.com/silacan/bookpalace2.git`
   - This command clones the Book Palace repository to your local machine.

2. **Navigate to the project directory**:
   - Change to the directory with: `cd bookpalace`

3. **Install dependencies**:
   - Install the required packages with: `yarn install`
   - This step installs all dependencies defined in `package.json`.

4. **Start the application**:
   - If a start script is specified in `package.json`, execute: `yarn start`
   - Open [http://localhost:3000](http://localhost:3000) 

.

## Additional Notes
- **Search Functionality:** The search functionality in `index.html` simulates filtering books based on user input. This feature does not connect to a backend service but is managed locally with JavaScript.
- **Local Storage Usage:** When users click "Add to Cart" on a book's detail page, the title is stored in `localStorage`, and the user is redirected to the `cart.html` page where the cart contents are displayed.
- **Running a Server:** If your project includes HTML files that make network requests, consider using a static server to serve your files:
  - Install a static server: `yarn global add serve`
  - Serve your project: `serve -s .`
  - This command starts a server to host your files, typically accessible at `http://localhost:3000`.

This README.md provides the necessary information to understand, setup, and use the Book Palace project. 
