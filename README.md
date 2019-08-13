REGRESSION MODELING
# The Tokyo 2020 Olympic Champions
PREDICTING THE MEDAL TABLE OF THE SUMMER GAMES

Next year on July 24th, 2020, an expected 11,091 athletes from 206 nations will gather in Tokyo, Japan to celebrate at the opening ceremony of the Games of the XXXII Olympiad. They will compete for gold, silver and bronze medals in 339 events across 33 sports, honoring the long-standing tradition of the modern Olympic Games, which began in Athens, Greece in 1896.

As with many international sporting mega-events, professional forecasters and enthusiastic fans enjoy predicting the outcome of the Olympic Games. The national medal table is a common metric for quantifying the overall performance of each country, aggregating the number of gold, silver, bronze and total medals collected by the individual athletes of each national team.

Daniel Johnson, an economics professor from Colorado College, used socio-economic data to predict national Olympic performance from 2000 to 2008. His model predicted the total medal count of each country at the Beijing 2008 Olympics with 94% accuracy, relying on per-capita income, population, political structure, climate, home-field advantage and geographic proximity.

A model of the Sochi 2014 Olympics employed economic trade information, namely the total value of national exports, as well as geographic data, such as land area and latitude. Subsequently, the Rio 2016 Olympics was modeled with similar national information, including comparative levels of national wealth along with historic performance in previous Olympic Games.

Randi Griffin posted a complete Kaggle dataset containing the records of each athlete and event from the Athens 1896 Olympic Games through the Rio 2016 Olympic Games. With 271,116 records and 15 columns, let’s build our own machine learning regression model to predict the medal table of the Tokyo 2020 Olympic Games, which we can train using the historic Olympic record!

[Continue reading the full story curated by Towards Data Science, a Medium publication...](https://towardsdatascience.com/the-tokyo-2020-olympic-champions-ad6bcc7fac72?source=friends_link&sk=0e8010953cc217ccec0211249313898c)

## Repository Contents

* [Project Features](#project-features)
* [Data Products](#data-products)
* [Source Code](#source-code)
* [Output Results](#output-results)
* [Contribute](#contribute)

## Project Features
SPORTS | MACHINE LEARNING

<p align="center">
  <img src="/img/Tokyo_2020.png" width="400" title="Tokyo 2020 Summer Olympic Games">
</p>

## Data Products
PANDAS

Two CSV files are available containing athlete results and Olympic country identifiers (NOCs).

271,116 athlete records contain the following data:

**[Athletes and Event Results](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)**
* ID - Unique number for each athlete
* Name - Athlete's name
* Sex - M or F
* Age - Integer
* Height - In centimeters
* Weight - In kilograms
* Team - Team name
* NOC - National Olympic Committee 3-letter code
* Games - Year and season
* Year - Integer
* Season - Summer or Winter
* City - Host city
* Sport - Sport
* Event - Event
* Medal - Gold, Silver, Bronze, or NA

## Source Code

## Output Results

## Contribute

**Contact**
* [Email](mailto:adam.c.dick@gmail.com)
* [LinkedIn](https://www.linkedin.com/in/adamcdick/)
* [Medium](https://medium.com/@adam.c.dick)
* [Scholar](https://scholar.google.com/citations?user=eMO88ogAAAAJ&hl=en)

**Acknowledgements**
* Logo by [The Tokyo Organising Committee of the Olympic and Paralympic Games](https://tokyo2020.org/jp/games/plan/data/tokyo2020-guidebook-en.pdf)
* Dataset by [Randi H Griffin](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)

**License**
* [MIT License](https://github.com/acdick/toyko_2020_olympic_medals/blob/master/LICENSE)