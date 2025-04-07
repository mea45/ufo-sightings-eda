# Exploratory Data Analysis of UFO Sightings Using Python

## Introduction
This is the first project I worked on for my data analytics portfolio. The main goal was to get reacquainted with Python and the different packages I used for data visualization a couple of years ago. This is also the first project I used Jupyter Notebook for. The dataset that is used in this project comes from [Kaggle](https://www.kaggle.com/datasets/NUFORC/ufo-sightings). It contains over 80,000 reports of UFO sightings including location, date, time and duration of the sightings. Almost all sightings come with a short comment. 

There are two parts to this projects. In the [first part](https://github.com/manalelabdellaoui/ufo-sightings-eda/blob/main/preprocessing.ipynb), the dataset was cleaned up and prepared for further analysis. In the [second part](https://github.com/manalelabdellaoui/ufo-sightings-eda/blob/main/exploratory_data_analysis.ipynb), we took a deeper dive into the data and performed some explantory analysis. 

## Dataset
- `datetime`: date and time of the alleged UFO sighting;
- `city`: city in which the UFO was sighted;
- `state`: state in which the UFO was sighted;
- `country`: country in which the UFO was sighted;
- `shape`: shape of the sighted UFO;
- `duration`: duration of the UFO sighting in seconds (there was also a second duration column with a different format that was not used in this project);
- `comments`: comments attached to the reported UFO sighting;
- `date_posted`: date on which the UFO sighting was reported;
- `latitude`: latitude of the location of sighting;
- `longitude`: longitude of the location of sighting.

In the part 2, an addition column, `comments_length`, was added indicating the length of the comment attached to the reported UFO sighting. It is the sum of all characters in the string.

## Findings
- **📅 Time Trends**: Sightings have increased over time, likely due to improvements in communication rather than actual frequency.
- **🌙 Time of Day**: Most sightings occur between 8 PM and 11 PM, with a peak on Saturday nights—times when people are more likely to be outdoors and less distracted.
- **☀️ Seasonality**: Sightings spike during the summer months, especially in the Northern Hemisphere.
- **🗺️ Geography**: Over 92% of reports come from the U.S., with clusters in North America, Europe, Australia, and India.
- **🕒 Reporting Delay**: Most sightings are reported within weeks; 75% are submitted within 119 days of the event.
- **⏱️ Duration**: The majority of sightings last only a few minutes.
- **✍️ Comments**: Many report descriptions are short and often cut off due to a character limit (~135 characters). Word analysis shows common themes like “light,” “night,” and color descriptions.
- **🛸 Shapes**: The most frequently reported UFO shapes are "light", "fireball", and "flash". Geometric shapes tend to be reported later and less frequently.
- **🌍 Mapping**: No clear shape-based geographic clustering was observed; sightings are spread in line with population density.
- **🧠 Text Insights**: Word clouds and top-word analyses reveal recurring themes in what people observe and how they describe their encounters.
