# Spotify Podcast Search Engine Analysis

This project develops a sophisticated information retrieval system designed to process and analyze metadata from Spotify podcasts. Utilizing the Natural Language Toolkit (NLTK) for natural language processing, the project aims to perform comprehensive text analysis, including tokenization, lemmatization, stemming, and sentiment analysis. Key features include the extraction of n-grams, the application of CountVectorizer for feature extraction, and the implementation of advanced text preprocessing techniques to enhance the quality of the dataset for analysis.

The project leverages machine learning models to categorize podcasts, predict listener preferences, and implement a search functionality that allows users to find podcasts based on specific queries. By analyzing podcast descriptions, names, and other metadata, the system can recommend podcasts that align closely with the user's interests.

## Data Acquisition

The podcast metadata is available in a .tsv file format and can be downloaded by making a request on the following site: [Podcasts Dataset](https://podcastsdataset.github.io). Follow the instructions on the site to access the metadata.tsv file, necessary for running this project.

## Key Libraries Used

NLTK (Natural Language Toolkit): Used for text preprocessing, including tokenisation, stop words removal, and stemming.
Pandas: Employed for data manipulation and analysis.
Scikit-learn: Used for feature engineering, text vectorisation, and applying machine learning models.
Requests & BeautifulSoup: Used for web scraping, allowing additional data collection if needed.

## Installation

Before running the project, ensure you have Python 3.9 or later installed on your system. You will also need to install the necessary Python packages.

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required Python packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage


After downloading the metadata.tsv file from the podcast datasets site, place it in the root directory of this project. You can then run the provided Python scripts to start analysing and exploring the podcast data. The main functionalities of this project include data preprocessing, vectorisation, and applying NLP techniques to analyse podcast data.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
