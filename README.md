# Quotes Web Scraper

This Python project uses Selenium to scrape quotes and their authors from [quotes.toscrape.com](http://quotes.toscrape.com/) and saves the data to a CSV file for easy use in Excel or Google Sheets.

## Features

- Automatically navigates through multiple pages (up to a set maximum).
- Extracts both quote text and author for each quote.
- Handles end-of-pages gracefully.
- Outputs results to a clean CSV file (`scraped_quotes.csv`).

## Requirements

- Python 3.x
- [Selenium](https://pypi.org/project/selenium/)
- [webdriver-manager](https://pypi.org/project/webdriver-manager/)
- Google Chrome browser (for ChromeDriver)

## Installation

1. **Clone this repository:**
    ```sh
    git clone https://github.com/YourUsername/your-repo-name.git
    cd your-repo-name
    ```

2. **Install dependencies:**
    ```sh
    pip install selenium webdriver-manager
    ```

## Usage

1. Run the script:
    ```sh
    python y.py
    ```
2. The script will open Chrome, scrape quotes from the website, and save them to `scraped_quotes.csv` in the project directory.

## Customization

- **Change the number of pages:**  
  Edit the `max_pages` variable in the script to scrape more or fewer pages.
- **Change the target website:**  
  Update the `driver.get("http://quotes.toscrape.com/")` line to scrape a different site (structure may need adjustment).

## Output

- The CSV file will have two columns: `author` and `quote`.

## License

This project is licensed under the MIT License.

---

*Created June 2025*
