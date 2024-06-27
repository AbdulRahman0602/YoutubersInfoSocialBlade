# YouTube Data Scraping and Reporting Project

This project utilizes Python to scrape YouTube channel statistics from Social Blade and generate reports in PDF, Word (docx), and Excel formats.

## Installation

To run this project, ensure you have Python 3.x installed along with the following libraries:

- `bs4` (Beautiful Soup 4): For web scraping.
- `requests`: For making HTTP requests.
- `docx`: For creating Word documents.
- `openpyxl`: For creating Excel spreadsheets.
- `reportlab`: For creating PDF documents.

You can install these dependencies using pip:

```bash
pip install beautifulsoup4 requests python-docx openpyxl reportlab
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your/repository.git
   cd repository
   ```

2. **Run the script:**

   Modify the `cname` variable in the script to specify the YouTube channel name or ID you want to scrape:

   ```python
   cname = input("Enter YouTube channel name or ID: ")
   getinfo(f'https://socialblade.com/youtube/c/{cname}_')
   ```

   This script will scrape data from Social Blade for the specified channel and generate three types of files:
   - `{cname}.pdf`: PDF report containing channel statistics.
   - `{cname}.docx`: Word document containing detailed statistics.
   - `{cname}.xlsx`: Excel spreadsheet containing tabular data.

3. **Generated Files:**

   - `{cname}.pdf`: Contains a summary of the channel's basic information and statistics.
   - `{cname}.docx`: Includes detailed statistics such as total uploads, subscribers, video views, and earnings over time.
   - `{cname}.xlsx`: Provides a structured table of daily statistics including dates, subscribers change, total subscribers, views change, total views, and estimated earnings.

## Notes

- Ensure the internet connection is stable as the script relies on fetching real-time data from Social Blade.
- Customize the script further as per your project requirements or integrate it into a larger data analysis pipeline.

---

Feel free to adjust the installation instructions and usage details according to your project's specifics and any additional features you plan to incorporate.
