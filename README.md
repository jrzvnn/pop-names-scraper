# Most Popular Names In Philippines Scraper

This repository contains a Python web scraper that extracts data from the "https://forebears.io/philippines/forenames" website. The scraper utilizes the Beautiful Soup library to parse the HTML content and extract relevant information about popular names in the Philippines. The output of the scraper is a CSV file containing the scraped data.

## Content

The dataset includes the following fields:

- `rank`: The position of the name when graded by incidence with all other names in the place.
- `forename`: The personal name given to an individual at or shortly after birth, also known as a first name.
- `incidence`: Number of people who bear the name.
- `frequency`: Ratio and percentage of people who bear the name.
- `gender`: The gender of the specific name based on the percentage.
- `gender_percentage`: The percentage of bearers who are male or female.

## Usage

To use the scraper with Conda and Jupyter Notebook, follow these steps:

1. Clone the repository to your local machine.
2. Create a new Conda environment.
3. Activate the Conda environment.
4. Launch Jupyter Notebook.
5. Open the `names_scraper.ipynb` notebook in Jupyter Notebook.
6. Run the cells in the notebook to execute the scraper and generate the CSV file.
7. Once the scraper completes, the scraped data will be saved as a CSV file.



Feel free to modify the scraper script or customize it according to your specific needs.

## License

This project is licensed under the [MIT License](LICENSE).

