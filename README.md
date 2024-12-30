# linkedin-scraper

This project is a web scraper designed to scrape all posts from an official LinkedIn account using the profile link as input. Follow the steps below to set up and use the scraper:

## Prerequisites
- Python installed on your system
- `pip` for managing Python packages
- Conda environment

## Steps to Set Up and Run the Scraper

### 1. Create a `cookies.txt` File
To authenticate the scraper, you need to provide LinkedIn cookies in Netscape format.

1. Open your browser and navigate to the LinkedIn page.
2. Use a browser extension or developer tools to extract the cookies for LinkedIn.
3. Save the extracted cookies in Netscape format in a file named `cookies.txt`. Place this file in the same directory as the scraper.

### 2. Install Dependencies
The required Python packages are listed in `requirements.txt`. Install them by running the following command in your terminal:

```bash
pip install -r requirements.txt
```

### 3. Run the Scraper Notebook
1. Open `scraper 2.ipynb`.
2. Configure the scraping parameters in the widget:
   - Set the number of posts you want to scrape.
   - Provide the official LinkedIn account profile link.
3. Run the notebook to start scraping. The image and video data will be saved in a folder titled `Scrape_{today's date}` and a `.csv` file will be exported. The `.json` file is there for tracking purposes only.

## Notes
- Ensure your `cookies.txt` file remains valid by updating it if you encounter authentication issues.
- Be mindful of LinkedIn’s scraping policies to avoid account restrictions.

## Disclaimer
This scraper is for educational and personal use only. Make sure you comply with LinkedIn’s terms of service and applicable laws when using this tool.

