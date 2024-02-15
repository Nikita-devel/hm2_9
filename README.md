# Web Scraping Project - Quotes and Authors

This project involves web scraping using the Scrapy framework to extract quotes and author information from the website [http://quotes.toscrape.com](http://quotes.toscrape.com). The goal is to generate two JSON files: `quotes.json` containing details about quotes from all pages and `authors.json` containing information about the authors of the specified quotes. The structure of the JSON files should align with the previous homework.

## Task Details

### Part 1: Scrapy Web Scraping

- Utilize the Scrapy framework for web scraping. The scraping process is orchestrated by a single script, `main.py`.
- The script should asynchronously fetch data from the target website and extract quotes along with relevant information about authors.
- The `quotes.json` file must capture details such as tags, author, and the quote text.
- The `authors.json` file should include comprehensive information about each author mentioned in the quotes.

### Part 2: Database Interaction

- Implement scripts for loading the generated JSON files (`quotes.json` and `authors.json`) into a cloud database.
- Ensure compatibility with the existing database interaction scripts from previous homework assignments.
- Verify that the previous scripts correctly interact with the newly populated database.

### Additional Task: Scrapy Script Structure

- Organize the Scrapy web scraping script `main.py` to function as a unified crawler script.
- Employ asynchronous and non-blocking operations using the `aiohttp` library to enhance efficiency.
- Optimize the script for readability and maintainability.

## Usage

1. Execute the Scrapy web scraping script:
   ```bash
   python main.py
   ```

2. Confirm the generation of `quotes.json` and `authors.json` files.

3. Run the database interaction scripts to load the data into the cloud database.

## Conclusion

This web scraping project demonstrates the effective use of the Scrapy framework to gather quotes and author information from a target website. The resulting JSON files are structured as per the assignment requirements, and the interaction with the cloud database ensures seamless integration with previous database-related tasks. The script's organization and use of asynchronous operations contribute to its efficiency and maintainability.
