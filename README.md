# Social Blade Data Extraction

This project extracts YouTube channel data from Social Blade using BeautifulSoup and saves the extracted information into a Word document using the `python-docx` library.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Example Output](#example-output)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/social-blade-data-extraction.git
    cd social-blade-data-extraction
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```


## Example Output

The script will generate a Word document named `output.docx` with the extracted data formatted in a readable manner.



## Usage

1. Ensure you have the necessary libraries installed and the HTML content loaded into the `soup` object.
2. Run the script to extract the data and save it to a Word document:
    ```sh
    python extract_data.py
    ```
3. Input the YouTube channel name when prompted.



