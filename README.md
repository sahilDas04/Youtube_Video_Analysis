

# Youtube Video Analysis

This project is a Streamlit application for analyzing the sentiment of comments on a YouTube video. It fetches comments from a given YouTube video URL, analyzes their sentiment, and displays various visualizations based on the analysis. The application also provides an option to download the comments with their sentiment scores as a CSV file.

## Features

- **Fetch Comments:** Retrieve comments from a specified YouTube video.
- **Sentiment Analysis:** Analyze the sentiment of each comment using TextBlob.
- **Visualizations:**
  - Display a histogram of sentiment distribution.
  - Plot sentiment over time.
  - Show an overall sentiment score with a gauge chart.
- **CSV Download:** Download the comments with sentiment scores as a CSV file.

## Requirements

- Python 3.x
- Streamlit
- google-api-python-client
- pandas
- textblob
- matplotlib
- numpy
- re

## Installation

**Clone the repository:**

```
git clone https://github.com/yourusername/youtube-comments-sentiment-analysis.git
cd youtube-comments-sentiment-analysis
```
**Install the required packages:**

```
pip install -r requirements.txt
```

**Run the Streamlit application:**

```
streamlit run video_analysis.py
```

## Usage


**1. Enter YouTube API Key:**

Replace the api_key variable in the main function with your YouTube API key.

**2. Enter YouTube Video URL:**

In the Streamlit interface, enter the URL of the YouTube video you want to analyze.

**3. Fetch and Analyze Comments:**

Click the "Fetch and Analyze Comments" button to retrieve and analyze the comments.

**4. View Results:**

View the data frame of comments with sentiment scores.

See the histogram of sentiment distribution.

Check the sentiment over time plot.

Observe the overall sentiment score on the gauge chart.

**5. Download CSV:**

Click the "Download data as CSV" button to download the comments with sentiment scores as a CSV file.


## project structure

```
youtube-comments-sentiment-analysis/
│
├── app.py                  # Main Streamlit application file
├── requirements.txt        # List of required packages
├── README.md               # Project README file
├── LICENSE                 # Project license file
└── images/
    └── you-tube-sentiment-analysis.png  # Image for README
```
## License

[MIT](https://choosealicense.com/licenses/mit/)

This project is licensed under the MIT License - see the LICENSE file for details.
## Acknowledgements

 - [Streamlit](https://streamlit.io/)
 - [Google API Python Client](https://github.com/googleapis/google-api-python-client)
 - [TextBlob](https://textblob.readthedocs.io/en/dev/)
  - [Matplotlib](https://matplotlib.org/) 
  - [Numpy](https://numpy.org/)

