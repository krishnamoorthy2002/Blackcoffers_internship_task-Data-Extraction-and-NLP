 Textual Analysis Tool

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A Python-based textual analysis tool that extracts article text from a given input file, performs analysis on the text, and saves the results in an output file.

## Features

- Extracts article text from URLs provided in an input file
- Performs textual analysis on the extracted text
- Computes various variables such as positive score, negative score, polarity score, subjectivity score, average sentence length, percentage of complex words, FOG index, average number of words per sentence, complex word count, word count, syllables per word, personal pronouns, and average word length
- Saves the analysis results in the specified format and order in an output file

## Prerequisites

- Python 3.x
- `pandas` library
- `requests` library
- `BeautifulSoup` library
- `pyphen` library
- `TextBlob` library

## Installation

1. Clone the repository to your local machine or download the code as a ZIP file.
2. Make sure you have Python installed on your machine.
3. Install the required libraries by running the following command in your terminal or command prompt:
   ```bash
    %pip install pandas requests beautifulsoup4 pyphen textblob

## Usage

1. Place the `Input.xlsx` file and the `Output Data Structure.xlsx` file in the same directory as the code.
2. Open a terminal or command prompt and navigate to the directory where the code is located.
3. Run the code using the following command:
```bash
python textual_analysis.py
```
4. The code will process the articles, perform textual analysis, and save the results in the specified output file.
5. Once the code execution is complete, you can open the `Output Data Structure.xlsx` file to view the analysis results.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please create a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE).

