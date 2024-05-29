
# CoinStats Dashboard

## Overview

CoinStats Dashboard is a comprehensive web application for visualizing historical data of various cryptocurrencies. The dashboard provides interactive and dynamic visualizations, allowing users to explore trends and metrics over specified date ranges. It includes features such as date range selection, cryptocurrency selection, and variable selection to display different metrics like price, market capitalization, and 24-hour trading volume.

## Features

- **Interactive Date Slider**: Allows users to select a date range for data visualization.
- **Cryptocurrency Selection**: Provides options to choose from multiple cryptocurrencies including Bitcoin, Ethereum, Bitcoin Cash, Litecoin, and Ripple.
- **Variable Selection**: Displays different metrics such as price in dollars, market capitalization, and 24-hour trading volume.
- **Dynamic Line Charts**: Visualizes the selected data over time with smooth transitions.
- **Tooltips**: Displays detailed information for specific data points on hover.
- **Responsive Design**: Ensures the layout adjusts for optimal viewing on different devices.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript, D3.js for data visualization.
- **Libraries**: Bootstrap for responsive design, jQuery and jQuery UI for interactivity.

## Usage

1. **Navigate to the Dashboard**:
   - Access the CoinStats Dashboard to start exploring cryptocurrency data.

2. **Select Date Range**:
   - Use the date slider located at the top of the dashboard to select the range of dates for which you want to view data. The dates will be updated in real-time above the slider.

3. **Choose Cryptocurrency**:
   - In the dropdown menu labeled "Cryptocurrency", select the cryptocurrency you are interested in (e.g., Bitcoin, Ethereum).

4. **Select Variable**:
   - Use the "Variable" dropdown to choose the data you want to visualize: Price in dollars, Market Capitalization, or 24-hour trading volume.

5. **Interact with the Chart**:
   - Hover over the line chart to see detailed information for specific data points. Tooltips will provide precise values.

6. **Observe Dynamic Updates**:
   - The chart will automatically update based on your selections, providing a dynamic and interactive experience.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/yourusername/coinstats-dashboard.git
   \`\`\`
2. Navigate to the project directory:
   \`\`\`bash
   cd coinstats-dashboard
   \`\`\`
3. Open \`index.html\` in your browser to view the dashboard.

## File Structure

- \`index.html\` : The main HTML file containing the structure of the webpage.
- \`css/style.css\` : Custom CSS styles for the webpage.
- \`js/main.js\` : JavaScript file for handling data visualization using D3.js.
- \`data/coins.json\` : Sample data file containing historical data of cryptocurrencies.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.
