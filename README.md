# Bionic Reading

Bionic Reading is a web application that leverages advanced text formatting techniques to enhance reading efficiency. By converting PDF files into a visually optimized format, the application aims to improve reading comprehension and speed.

## Features

- **User-Friendly Interface:** The application provides a simple and intuitive interface for users to upload PDF files.
- **Text Formatting:** Bionic Reading employs a unique text formatting algorithm that enhances readability by highlighting key portions of words.
- **Customizable Styling:** Users can easily customize the visual styling of the formatted text to suit their preferences.

## How It Works

1. **Upload PDF:** Choose a PDF file using the "Choose PDF" button or copy text directly by clicking the "Copy Text" button.

2. **Conversion:** Upon clicking the "Convert" button, the application utilizes a backend server to extract text from the PDF file using the pdf-parse library.

3. **Text Formatting:** The extracted text undergoes a special formatting process. The application highlights specific portions of words to create a unique visual representation that aids in bionic reading.

4. **Result Display:** The formatted text is displayed in the result area, providing users with an enhanced reading experience.

## Getting Started

To run the project locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/jasmeetSSalh/bionic-reading
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the application:

   ```bash
   npm start
   ```

   The application will be accessible at [http://localhost:3000](http://localhost:3000).

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Libraries:** pdf-parse

## Contributing

If you would like to contribute to Bionic Reading, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to the creators of pdf-parse for providing a reliable PDF parsing solution.
- Inspired by the concept of bionic reading and the desire to enhance reading experiences.

Feel free to explore, contribute, and improve Bionic Reading for a better reading experience!
