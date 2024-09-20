# Movie Recommendation System

This project is a film recommendation system built using **Python**, **machine learning**, and **Streamlit**. The project is not yet fully finished, but it can already recommend movies based on the available data.

Once the app is running, you can use it to get movie recommendations by typing the name of a movie in the search box.

## Project Structure

Inside the main folder, you will find a sub-folder called **"movies_recommendation_system"** that contains:

- `home.py`: The main file to run the recommendation system.
- 3 `.pkl` data files: These are used for movie data and model information.
- A presentation of the project.

## How to Run

1. Navigate to the **"movies_recommendation_system"** folder.
2. Run the following command in your terminal to start the application:
    ```bash
    streamlit run home.py
    ```

That's it! The movie recommendation system will start in your browser.

## Features

- Movie recommendations based on user input.
- Fetches data from the **TMDb API** for detailed movie information.
- Includes movie posters and links to more details.
  
  > Note: The "Details" button may not work for all movie links, possibly due to API limitations. However, try searching for **"Spider-Man"** for a working example.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please open an issue or submit a pull request.
