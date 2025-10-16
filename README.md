# Markdown to HTML Viewer

This project provides a simple, single-file HTML application (`index.html`) designed to convert a Markdown file (`input.md`) into formatted HTML and render it directly in the browser. It leverages modern web technologies for a responsive and clean user experience.

## Features

*   **Markdown Conversion**: Automatically fetches and converts `input.md` to HTML.
*   **Responsive Design**: Built with Tailwind CSS, ensuring a great experience on devices of all sizes.
*   **Safe Rendering**: Utilizes DOMPurify to sanitize the converted HTML, protecting against potential XSS attacks.
*   **Clean Styling**: Markdown content is styled beautifully using Tailwind CSS Typography plugin.

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: A utility-first CSS framework for rapid UI development and responsive design.
*   **Marked.js**: A fast Markdown parser and compiler written in JavaScript.
*   **DOMPurify**: A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML, and SVG.

## Usage

To use this application:

1.  **Save the files**: Ensure `index.html` and your `input.md` file are in the *same directory*.
2.  **Open `index.html`**: Simply open `index.html` in your web browser.

The page will automatically load `input.md`, convert its content to HTML, sanitize it, and display it in a beautifully formatted layout.

## Project Structure

```
.
├── index.html
├── input.md
└── README.md
└── LICENSE
```

## Contributing

Feel free to fork this repository, open issues, or submit pull requests.

## License

This project is open source and available under the [MIT License](LICENSE).