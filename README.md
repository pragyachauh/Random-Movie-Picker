
# Random Movie Picker

This code aims to generate the name and respective year of a random movie by reading data from an imported excel file downloaded from a personal Letterboxd watchlist. I created this because I was indecisive about choosing a movie one day in my free time.





## Libraries 
* Math
* Pandas
* Random
## Usage

    1. This program reads from an excel file called (`watchlist.xlsx`) exported from my Letterboxd watchlist data with columns for "Name" (movie title) and "Year".
    2. `file_loc` variable with the correct file path to your Excel file.
    3. The code reads the "Name" and "Year" columns from the Excel file using pandas and stores the data in a DataFrame (`df`).
    4. It calculates the number of movies in the DataFrame (`count`).
    5. A random index is generated using `randrange` from the `random` module.
    6. The movie name and year are retrieved from the DataFrame using the random index.
    7. The selected movie name and year are printed to the console."# Random-Movie-Picker" 
"# Random-Movie-Picker" 
