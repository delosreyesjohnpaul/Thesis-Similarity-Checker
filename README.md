# Thesis Similarity Checker

This is a Django-based application designed to detect overlapping content and potential plagiarism in documents. It uses cosine similarity measures to evaluate the angle between text vectors, providing a robust method to identify similarities between documents.

## Features

- **Cosine Similarity Algorithm:** Calculates the cosine similarity between text vectors to determine the degree of similarity.
- **Multi-format Support:** Supports text comparison across various file formats including .txt, .docx, and .pdf.
- **Web Search Integration:** Utilizes web search to find similar content online and assess the similarity.
- **Text Comparison:** Allows for both single text and two-text comparison options.

## Usage

1. **Home Page:** Start with uploading your document or entering text to compare.
2. **Web Search (Text):** Enter text to search for similar content on the web.
3. **File Test:** Upload a text (.txt), Word (.docx), or PDF (.pdf) document to check for similarity.
4. **Text Compare:** Compare two pieces of text for potential overlaps or plagiarism.
5. **Two File Compare:** Upload two documents to compare their content.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/delosreyesjohnpaul/Thesis-Similarity-Checker.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Django server:
   ```bash
   python manage.py runserver
   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
