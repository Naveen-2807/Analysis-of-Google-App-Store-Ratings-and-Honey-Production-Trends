# Analysis-of-Google-App-Store-Ratings-and-Honey-Production-Trends
PART I:

EDA & Data Preprocessing on Google App Store Rating Dataset.

Domain: Mobile device apps

Context:

The Play Store apps data has enormous potential to drive app-making businesses to success. However, many
apps are being developed every single day and only a few of them become profitable. It is important for
developers to be able to predict the success of their app and incorporate features which makes an app
successful. Before any such predictive-study can be done, it is necessary to do EDA and data-preprocessing on
the apps data available for google app store applications. From the collected apps data and user ratings from
the app stores, let's try to extract insightful information.

Objective:

The Goal is to explore the data and pre-process it for future use in any predictive analytics study.

Data set Information:

Web scraped data of 10k Play Store apps for analyzing the Android market. Each app (row) has values for
category, rating, size, and more.

Attribute Information:

1. App Application name
2. Category Category the app belongs to.
3. Rating Overall user rating of the app
4. Size Size of the app
5. Installs Number of user reviews for the app
6. Type Paid or Free
7. Price Price of the app
8. Content Rating Age group the app is targeted at - children/Mature 21+ /Adult
9. Genres An app can belong to multiple genres (apart from its main category). For eg. a
musical family game will belong to Music, Game, Family genres.
10. Last Updated Date when the app was last updated on play store.
11. Current Ver Current version of the app available on play store.
12. Android Ver Min required Android Version.

PART II:

Data Visualization on Honey Production dataset using seaborn
and matplotlib libraries.

Domain: Food and agriculture

Context:

In 2006, a global concern was raised over the rapid decline in the honeybee population, an integral component
to American honey agriculture. Large numbers of hives were lost to “Colony-Collapse-Disorder”, a
phenomenon of disappearing “worker-bees” causing the remaining “hive-colony” to collapse. Speculation
around the cause of this disorder points to hive-diseases and pesticides harming the pollinators, though no
overall consensus has been reached. Twelve years later, some industries are observing recovery but the
American honey industry is still largely struggling. The U.S. used to locally produce over half the honey it
consumes per year. Now, honey mostly comes from overseas, with 350 of the 400 million pounds of honey
consumed every year originating from imports. This dataset provides insight into honey production supply and
demand in America by state from 1998 to 2012.

Objective:

The Goal is to use Python visualization libraries such as seaborn and matplotlib to investigate the data and get
some useful conclusions.

Attribute Information:

1. numcol Number of honey producing colonies.
2. yield percol Honey yield per colony. (Unit is pounds)
3. total prod Total production (numcol x yieldpercol). (Unit is pounds)
4. price per lb Refers to average price per pound based on expanded sales. Unit is dollars.
5. prodvalue Value of production (total prod x priceperlb). Unit is dollars.
6. Stocks Refers to stocks held by producers. Unit is pounds
7. Year Calendar year.
8. State Different states' names.
