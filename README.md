# Simple E-Learning Website

This is a basic e-learning website where users can view and download books and study materials. The website is built using HTML, CSS, and JavaScript. Users can either read the books online in an in-browser PDF reader or download them to their local system.

## Features

- **Browse Books**: View a list of available books.
- **Read Online**: Click on a book to open it in a PDF reader.
- **Download**: Download books to your local system for offline reading.
- **Responsive Design**: The website adjusts well to different screen sizes.

## Folder Structure

```bash
/simple-e-learning-website
│
├── /books
│   ├── book1.pdf
│   ├── book2.pdf
│   └── book3.pdf
│
├── index.html
└── style.css
```

- **/books/**: This folder contains the PDF files for the books.
- **index.html**: The main webpage that displays the list of books and links to read or download.
- **style.css**: CSS file to style the webpage.

## How to Use

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your browser.
3. Add your own books (PDF files) to the `/books` folder.
4. Update the `index.html` file with your book names and links as needed.

## How to Add New Books

1. Place the new book PDF inside the `/books` folder.
2. Open `index.html` in a text editor.
3. Add a new section for the book following this template:

   ```html
   <div class="book-item">
       <h3>Book Title</h3>
       <a href="books/your-new-book.pdf" target="_blank">Read Online</a>
       <a href="books/your-new-book.pdf" download>Download</a>
   </div>
   ```

4. Save and refresh the browser to see the updated book list.

## Customization

- You can easily customize the look and feel by editing the `style.css` file.
- Modify the `index.html` file to change the book list and descriptions.

## License

This project is open-source and free to use. Modify and distribute as needed.
```

This `README.md` will help others understand the basic structure and usage of your simple e-learning website project!
