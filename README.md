# Sales Data Summary App

This is a simple, single-page web application designed to fetch and display a summary of sales data from a CSV file. It automatically calculates the total sales from the 'sales' column in `data.csv` and presents it prominently.

## Features

*   **Data Fetching**: Automatically fetches `data.csv` from the same directory.
*   **Sales Calculation**: Parses the CSV, identifies the 'sales' column, and sums its values.
*   **Dynamic Title**: Sets the page title to 'Sales Summary ${seed}'.
*   **Responsive Design**: Built with Tailwind CSS for a modern, responsive user interface.
*   **Error Handling**: Basic error handling for file fetching and data processing.

## Setup

To run this application:

1.  Ensure you have `index.html` and `data.csv` in the same directory.
2.  Open `index.html` in your web browser.

The application will automatically fetch `data.csv`, calculate the total sales, and display it on the page.

## File Structure

*   `index.html`: The main single-page application, containing HTML, CSS (via Tailwind CDN), and JavaScript for data processing.
*   `data.csv`: The comma-separated values file containing the sales data. It is expected to have a column named 'sales'.
*   `README.md`: This file, providing information about the project.
*   `LICENSE`: The MIT License text.

## Technologies Used

*   **HTML5**: For the structure of the web page.
*   **JavaScript**: For fetching, parsing, and processing the CSV data.
*   **Tailwind CSS**: For utility-first styling and responsive design.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
