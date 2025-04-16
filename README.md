# Article Scraper

This project is a simple Python script that scrapes news articles from a given URL. It extracts the article's title and content, and saves them to a text file.

## Features
- Fetches the HTML content from a specified URL.
- Extracts the title of the article.
- Extracts the content (body) of the article.
- Saves the scraped article into a text file (`scraped_article.txt`).

## Requirements
- Python 3.x
- `requests` library
- `beautifulsoup4` library

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/asadrizvi969/Article-Scrapper.git
    ```
2. Install the necessary dependencies:
    ```bash
    pip install requests beautifulsoup4
    ```

## How to Use

1. Open your terminal/command prompt.
2. Navigate to the directory where the `article_scraper.py` script is located.
3. Run the script with a URL of the article you want to scrape:
    ```bash
    python article_scraper.py <URL>
    ```
    Example:
    ```bash
    python article_scraper.py https://www.example.com/some-article
    ```
4. The article's title and content will be saved in a text file named `scraped_article.txt`.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
[Syed Asad Abbas Rizvi](https://github.com/asadrizvi969)
