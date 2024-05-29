<img src="https://lh6.googleusercontent.com/YnesmZ6jQv1uqZMDfykSnsOLGbdF8xdYrgf9hyNQ7b_k2I40lYT-KhpV1J79z6eWSo54rXs9fuz7qs_Z5xyscoqzKb5vOaPizFeuko3107z6HuZpr8LBwicffPYvz6z8sRV7ykjRqUytqRj0VOgKqGUlHJRKfu6BDxgZuve6Lmetvkgh2d4GXEIAMg" alt="Banner Image" style="width: 100%;">
# Data Engineering Challenge - Groover Artist Popularity 🌟

Welcome to the Data Engineering Challenge for Groover, where our goal is to help artists reach music industry professionals and establish meaningful connections to build their careers. This challenge focuses on evaluating and improving how artist data is stored and managed, particularly in relation to their popularity on Spotify.

## Challenge Overview 📊

Your task is to analyze and enrich Groover's dataset with Spotify's popularity metrics to ensure our data accurately represents each artist's current standing. You will work with multiple data tables and integrate external data from Spotify's API.

### Data Description 🗂️

You are provided with four tables:
1. **Artist Table**: Contains `user ID` and `artist name`.
2. **Spotify Artist Table**: Contains `user ID` and `spotify ID`.
3. **Artist Tag Table**: Contains `user ID` and `tag ID`.
4. **Genre Tag Table**: Contains `ID`, `band ID`, and `tag name`.

All data can be accessed from the repository.

### Goals 🎯

- Retrieve the popularity score for each artist from Spotify's API.
- Validate and ensure consistency between the artist names on our platform and those listed on Spotify.
- Write an SQL query to list all artists with their Spotify ID, user ID, genres, the total number of genres they are assigned to, and the total number of artists assigned to each genre.

### Constraints ⏳

- Allowed programming languages: Python & SQL
- Completion window: 7 days from the receipt of this document.

## Installation 🛠️

### Prerequisites

- Python 3.8+
- Anaconda or Miniconda

### Setting Up Your Environment

1. Clone this repository to your local machine.
2. Create a Conda environment:
3. Install required packages

### Prepare the Data

Data is available under the `raw_data/` directory in the repository. Ensure all data files are correctly placed before proceeding.

## Running the Notebook

To start the Jupyter Notebook: jupyter notebook-name

Navigate to the `groover-internal-explained.ipynb` notebook in the Jupyter interface and run the cells sequentially to perform the data cleaning, analysis, and integration tasks.

## Additional Information

- Ensure you follow all API rate limits and terms of use when querying Spotify's API.
- Refer to the `docs/` directory for more detailed information about the database schema and API configuration.

## Conclusion

This challenge not only tests your ability to work with complex datasets but also your ability to integrate and verify external data sources. Good luck, and we look forward to your insights and improvements to our data handling capabilities!

