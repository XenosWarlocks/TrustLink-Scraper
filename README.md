# TrustLink-Scraper

TrustLink-Scraper is a Python project that scrapes faculty profiles from the USC Dornsife website, extracts emails, and cleans the collected data. The project is divided into two scripts: `main.py` for scraping and `cleaner.py` for cleaning the data.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/XenosWarlocks/TrustLink-Scraper.git
    cd TrustLink-Scraper
    ```

2. Create and activate a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Scraping Data

To scrape the data, run the `main.py` script:

```bash
python main.py


TrustLink-Scraper/
```
```│
├── README.md
├── requirements.txt
└── dataset/
    ├── main.py
    ├── cleaner.py
└── output
    ├── scraped_data.csv
    └── cleaned_data.csv
