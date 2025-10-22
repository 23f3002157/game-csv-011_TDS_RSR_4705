# Sales Summary Project

This project is a simple single-page website that fetches sales data from a CSV file, calculates the total sales, and displays the result using Bootstrap 5 for styling.

## Features

- Fetches `data.csv` file to retrieve sales data.
- Computes the total sales from the sales column.
- Displays the total sales in a styled alert box.
- Utilizes Bootstrap 5 for responsive design.

## Getting Started

1. **Clone the repository** or download the files.
2. **Set up a local server** because fetch calls may not work with local file access in browsers.
3. Ensure the `data.csv` file exists in the same directory as `index.html`.
4. Open `index.html` in your browser.

## Files

- `index.html`: The main HTML file that contains the structure and logic of the application.
- `data.csv`: The CSV file that should contain sales data.
- `cap.json`: A JSON file containing the capitals of five countries.

Example of `cap.json`:

```json
{
  "USA": "Washington, D.C.",
  "Canada": "Ottawa",
  "UK": "London",
  "France": "Paris",
  "Germany": "Berlin"
}
```

## Installation

Include Bootstrap 5 in your project via CDN by adding the following link to your `index.html`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
```

## License

MIT License - see [LICENSE](LICENSE) for details.