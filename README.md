This code performs the following tasks:

- It scrapes a Wikipedia page that contains a list of mountains by elevation.
- It extracts the relevant data from the HTML page, including mountain names, heights, and links to individual mountain pages.
- It creates a data frame containing the names, heights, and links of mountains above a certain elevation threshold (6800m in this case).
- It defines functions to convert latitude and longitude from degrees/minutes/seconds format to decimal degrees and to extract latitude and longitude from individual mountain pages.
- It iterates over the table of mountains, downloads the mountain data, and extracts the coordinates, storing them in the data frame.
- Finally, it plots the mountains on a world map using ggplot2, with points colored according to their height, and displays the map.
