# Final_output_DSA501

# DataFrame Display Web App

This simple application scrapes data from [Buffalo State College](https://www.buffalostate.edu/) to create a DataFrame showing the number of undergraduate classes in each department from 2015 to 2023 (excluding summers).

## Prerequisites

- Python 3.x
- Pandas library (`pip install pandas`)
- BeautifulSoup library (`pip install beautifulsoup4`)
- Requests library (`pip install requests`)

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/Vipularora3/Final_output_DSA501.git
    ```

2. Navigate to the project directory:

    ```bash
    cd dataframe_display_app
    ```

3. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Python script to scrape data and generate the DataFrame:

    ```bash
    python scrape_data.py
    ```

2. The script will create an HTML file named `dataframe.html` containing the DataFrame table.

3. To view the DataFrame, open `dataframe.html` in a web browser.

## Customization

- Modify the scraping logic in `scrape_data.py` to suit specific data requirements or website changes.
- Customize the HTML template (`templates/dataframe.html`) for the web page layout or styling.

## Acknowledgments

- This project was created for educational purposes and data exploration.
- Thanks to Buffalo State College for providing the data.

---

Feel free to expand on this README by adding more detailed instructions, explanations, or any additional information relevant to your project!
