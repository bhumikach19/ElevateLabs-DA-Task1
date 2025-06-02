# Netflix Movies and TV Shows Data Analysis Project

This project performs data cleaning and preprocessing on a Netflix dataset containing information about movies and TV shows available on the platform.

## Dataset Description

The dataset (`Netflix_movies_and_tv_shows_clustering.csv`) contains the following features:
- show_id: Unique identifier for each show
- type: Type of content (Movie/TV Show)
- title: Title of the show
- director: Director of the show
- cast: List of actors/actresses
- country: Country of origin
- date_added: Date when the show was added to Netflix
- release_year: Year when the show was released
- rating: Content rating (e.g., TV-MA, PG-13, R)
- duration: Length of the show (in minutes for movies, seasons for TV shows)
- listed_in: Categories/genres
- description: Brief description of the show

## Setup Instructions

1. Clone this repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook EL_Task1_DA.ipynb
   ```

## Project Structure

- `EL_Task1_DA.ipynb`: Main Jupyter notebook containing the data cleaning and preprocessing steps
- `Netflix_movies_and_tv_shows_clustering.csv`: Original dataset file
- `Netflix_Cleaned.csv`: Cleaned and preprocessed dataset
- `requirements.txt`: List of Python dependencies
- `README.md`: Project documentation

## Data Cleaning Steps

1. Column Standardization:
   - Renamed columns to lowercase with underscores
   - Standardized text fields (e.g., director names)

2. Data Quality Checks:
   - Checked for missing values
   - Removed duplicate rows
   - Verified data types

3. Data Type Conversion:
   - Ensured proper data types for all columns
   - Standardized text fields

4. Output:
   - Generated cleaned dataset as 'Netflix_Cleaned.csv'

## Data Statistics

- Initial dataset size: 7,787 rows × 12 columns
- Final cleaned dataset size: 4,808 rows × 12 columns
- Missing values were found in:
  - director (2,389 missing)
  - cast (718 missing)
  - country (507 missing)
  - date_added (10 missing)
  - rating (7 missing)

## Dependencies

- pandas: Data manipulation and analysis
- numpy: Numerical computing
- jupyter: Interactive notebook environment 