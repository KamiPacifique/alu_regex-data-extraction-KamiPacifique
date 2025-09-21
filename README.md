# ALU Regex Data Extraction

This project is designed to extract and process data using regular expressions (regex). It provides a user-friendly interface for inputting text, analyzing patterns, and displaying results.

## Features

- **Regex Matching**: Extract specific patterns from text using customizable regular expressions.
- **User Interface**: A clean and responsive form for inputting text and displaying results.
- **Customizable**: Easily modify the CSS and HTML to fit your needs.

## Technologies Used

- **HTML**: For structuring the web page.
- **CSS**: For styling and layout.
- **JavaScript**: For handling regex operations and dynamic interactions.

## Patterns used

- emails: /\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}\b/g,
- urls: /\bhttps?:\/\/[A-Za-z0-9.-]+\.[A-Za-z]{2,}(?:\/[^\s]*)?\b/g,
- phones: /\b(\(?\d{3}\)?[-.\s]?)\d{3}[-.\s]?\d{4}\b/g,
- creditCards: /\b(?:\d{4}[- ]?){3}\d{4}\b/g,
- time: /\b((1[0-2]|0?[1-9]):[0-5][0-9]\s?(AM|PM))\b|\b((2[0-3]|[01]?[0-9]):[0-5][0-9])\b/gi,
- htmlTags: /<\/?[a-zA-Z][^>]*>/g,
- hashtags: /#\w+/g,
- currency: /\$\d{1,3}(,\d{3})*(\.\d{2})?/g

## How to Use
- git clone https://github.com/KamiPacifique/alu_regex-data-extraction-KamiPacifique.git
