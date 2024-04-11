# Country GDP Visualization

This Shiny web application allows users to explore and visualize country GDP data. Users can upload a CSV file containing GDP data, select a specific country, and analyze its GDP trends over the years through histograms and line charts. Additionally, the application offers k-means clustering analysis, providing insights into potential economic groupings based on GDP patterns.

## Features

- Upload a CSV file containing country GDP data.
- Select a country from the dataset.
- View histograms and line charts illustrating GDP trends over the years.
- Perform k-means clustering analysis on the GDP data to identify potential economic groupings.

## Usage

1. Clone the repository or download the files.
2. Install the required R packages specified in the `Dependencies` section.
3. Run the Shiny application by executing the script.

Upload a CSV file containing country GDP data.

Explore GDP trends by selecting a country and analyzing the generated visualizations.

Optionally, perform k-means clustering to identify economic groupings.

## Dependencies

- Shiny
- ggplot2
- dplyr
- cluster

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


```R
Rscript app.R
