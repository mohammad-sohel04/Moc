 **# Movie Recommendation System**

**## Overview**

This project implements a content-based movie recommendation system that suggests movies similar to a user's inputted favorite movie. 

**## Key Features**

- **User Input:** Prompts the user to enter their favorite movie.
- **Close Match Finding:** Utilizes `difflib` to find close matches in case of typos or variations in movie titles.
- **Similarity Calculation:** Leverages a pre-computed similarity matrix to determine movies that are most similar to the chosen movie.
- **Recommendation Display:** Presents a list of up to 30 recommended movies, ranked by similarity.

**## Required Libraries**

- Pandas
- NumPy
- difflib

**## Usage**

1. Clone this repository.
2. Ensure you have the required libraries installed.
3. Run the script 
4. Follow the prompts to enter your favorite movie and receive recommendations.

**## Additional Information**

- **Data Source:** The project currently utilizes a pre-existing dataset of movie data. Consider providing details about this dataset (e.g., name, source, features).
- **Similarity Matrix:** Explain how the similarity matrix was constructed (e.g., feature selection, similarity metric).
- **Future Improvements:** Discuss potential enhancements for future iterations, such as:
    - Incorporating collaborative filtering techniques
    - Enhancing user experience with a graphical interface
    - Expanding dataset size
    - Refining similarity calculation methods


