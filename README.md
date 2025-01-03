# Haveloc Scraper

The Haveloc Scraper is a Python-based web scraper designed to automate the process of extracting data from Haveloc's email and notification system. This tool is useful for collecting information, processing attachments, and uploading relevant data to Supabase.

## Features

- **Headless Chrome Scraping**: Uses Selenium with ChromeDriver to navigate the Haveloc website.
- **Email Processing**: Automatically logs into Haveloc, fetches emails, and processes them for important information.
- **Attachment Handling**: Downloads and extracts data from attachments.
- **Data Extraction**: Extracts data from email tables and uploads it to Supabase.
- **Error Logging**: Captures errors and logs them for troubleshooting.

## Docker Integration

This project includes Docker support, making it easy to containerize and run the tool. The Dockerfile sets up a Python environment and prepares the bot to be run in a Docker container.

## Prerequisites

- Python 3.x
- Selenium (install via `pip install selenium`)
- ChromeDriver (must be installed and available in the path or specified manually in the script)
- Supabase client libraries for Python
