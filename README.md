# Product Sales Aggregator

## Overview

This web application provides a simple interface to upload CSV files containing product sales data. It then calculates the sum of sales from the uploaded CSV and displays the total in a designated area on the page.

## Features

*   **CSV Upload:** Allows users to upload CSV files for processing.
*   **Sales Aggregation:** Automatically sums the sales figures from the uploaded CSV.
*   **Real-time Display:** Shows the calculated total sales in the `#total-sales` element.

## Usage

1.  Navigate to the application's web page.
2.  Locate the file upload input.
3.  Select a CSV file containing your product sales data.
4.  The total sales will be automatically calculated and displayed in the `#total-sales` section.

## Technical Details

The application utilizes client-side JavaScript to handle file uploads and CSV parsing. Upon file selection, the JavaScript reads the CSV content, iterates through the relevant sales column, and accumulates the sum. The final total is then updated in the DOM.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.