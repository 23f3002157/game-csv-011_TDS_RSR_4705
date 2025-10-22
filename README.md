# Currency Picker and Big Bang Story

This project implements a currency picker that allows users to choose between multiple currencies (USD, EUR, GBP) and dynamically updates the total sales value based on the selected currency. Additionally, a text file contains an informative 300-word story on the Big Bang.

## Features

- Currency selection dropdown to choose between USD, EUR, and GBP.
- Fetches total sales data from a CSV file and displays it in the selected currency.
- Uses Bootstrap for styling to provide a responsive design.

## Installation

To run this project, simply clone the repository and open `index.html` in your browser. Ensure that `data.csv` is present in the same directory with the correct format for the total sales calculation.

## Usage

1. Open the `index.html` file in your web browser.
2. Select a currency from the dropdown.
3. The total sales will be recalculated and displayed in the chosen currency.

## Changes Made

- Added a `<select>` element to allow currency selection.
- Introduced `currencyRates` object to handle conversion rates for USD, EUR, and GBP.
- Modified the `fetchTotalSales()` function to convert the total sales value based on the selected currency and format the output accordingly.

## Data Source

- Ensure the presence of a `data.csv` file containing sales data in the following format:
  ```
  Product Name,Units Sold,Price
  ```

## Story

The `story.txt` file contains a 300-word story on the Big Bang, discussing the origin of the universe, the formation of matter, and the evolution of cosmic structures.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.