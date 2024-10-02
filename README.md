# 📊 BOX OFFICE Data Explorer

Welcome to **BOX OFFICE Data Explorer**, a Streamlit app designed for exploring movie genre performance at the box office. This app offers an interactive experience where users can filter data by movie genres and specific year ranges, view and edit the data, and visualize the results with dynamic line charts.

## Features

- **Pandas for Data Wrangling**: Efficiently filter and manipulate movie data.
- **Altair for Charting**: Create interactive line charts that show gross earnings over time.
- **Editable DataFrame**: Users can interact with and modify data live, enhancing the exploration process.

## How to Use

1. **Select Genres**: Use the drop-down box to choose one or more movie genres of interest.
2. **Pick Year Duration**: Adjust the slider to select the range of years you want to analyze.
3. **View and Edit Data**: The filtered data is displayed in an editable DataFrame for further interaction.
4. **Visualize Trends**: A dynamic line chart visualizes the gross earnings of selected genres over time.

## Libraries Used

- **Streamlit**: For building the interactive interface.
- **Pandas**: For data wrangling and manipulation.
- **Altair**: For creating intuitive and interactive charts.
- **Numpy**: For numerical operations.

## Installation

To run this app locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/interactive-data-explorer.git
   cd interactive-data-explorer
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run main.py
   ```

## Data Source

The app uses a pre-processed movie dataset (`movies_genres_summary.csv`), which includes:
- **Genres**: A variety of movie genres such as Action, Adventure, Drama, Comedy, etc.
- **Year**: The release year of the movies.
- **Gross Earnings**: The box office earnings of each movie.

## Example Visualizations

Once you interact with the app, it will generate editable DataFrames and dynamic charts like the one below:

- **Line Chart**: Displays the box office performance of selected movie genres over the chosen time period.

## Contributing

Feel free to fork this repository and submit pull requests to improve the app. Contributions to enhance its features, optimize performance, or add new functionalities are welcome.
