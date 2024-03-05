# Spotify Podcast Search Engine Analysis

This project develops a sophisticated information retrieval system designed to process and analyse metadata from Spotify podcasts. Utilising the Natural Language Toolkit (NLTK) for natural language processing, the project aims to perform comprehensive text analysis, including tokenisation, lemmatisation, stemming, and sentiment analysis. Key features include the extraction of n-grams, the application of CountVectorizer for feature extraction, and the implementation of advanced text preprocessing techniques to enhance the quality of the dataset for analysis.

The project leverages machine learning models to categorise podcasts, predict listener preferences, and implement a search functionality that allows users to find podcasts based on specific queries. By analysing podcast descriptions, names, and other metadata, the system can recommend podcasts that align closely with the user's interests.

## Data Acquisition

The podcast metadata is available in a .tsv file format and can be downloaded by making a request on the following site: [Podcasts Dataset](https://podcastsdataset.github.io). Follow the instructions on the site to access the metadata.tsv file, necessary for running this project.

## Key Libraries Used

#### NNatural Language Processing and Text Analysis
- NLTK (Natural Language Toolkit): Used for various natural language processing tasks such as lemmatisation, stopwords removal, tokenisation, and sentiment analysis.
- Scikit-learn: Employed for text vectorisation (with CountVectorizer), as well as applying machine learning models.
  
#### Data Manipulation and Analysis
- Pandas: Used for data manipulation and analysis, particularly for handling structured data such as data frames.
- NumPy: For numerical computing, especially operations on multi-dimensional arrays.
  
#### Web Scraping
- Requests: Allows making HTTP requests to download web page content.
- BeautifulSoup: Used for parsing HTML and extracting necessary data from web pages.
  
#### Information Retrieval
- PyTerrier: A framework for developing and evaluating information retrieval models, based on the Terrier IR system. Used for indexing, searching, and evaluating information retrieval models.
  
#### Other Standard Python Libraries
- String: Used for common string operations.
- Re (Regular Expressions): Employed for advanced string matching and manipulation through regular expressions.
  
#### Additional Features and Tools
urllib.request: In some contexts, this library might be used for opening and reading URLs, although requests is generally preferred for its ease of use.

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

