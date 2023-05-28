# WhatsApp Chat Analyser

The WhatsApp Chat Analyzer is a Python-based tool for analysing WhatsApp chat data through the use of a web app. It allows users to upload their WhatsApp chat file, perform data preprocessing, and generate insightful visualisations and statistics.

WhatsApp is a popular messenger app, and analysing conversation data can offer useful information about communication trends, user behaviour, and content evaluation.
## Features

- Statistics: Display top statistics such as total messages, total words, media shared, and links shared.
- Timeline Analysis: Visualize monthly and daily chat activity timelines.
- Activity Map: Explore weekly activity patterns and busiest days or months.
- WordCloud: Generate a WordCloud of most frequently used words.
- Most used Words: Identify and visualize the most common words used.
- Emoji Analysis: Analyze emoji usage and present a pie chart of the most frequently used emojis.
## Setup

To run the movie recommendation system locally, follow these steps:

1. Clone the repository:

git clone https://github.com/<your_username>/<repo_name>.git

2. Install the required dependencies:

!pip install -r requirements.txt

3. Run the Streamlit web app:

streamlit run app.py
## Usage/Examples

1. Access the application in your web browser at http://localhost:8501.

2. Upload your WhatsApp chat file (exported in text format).

3. Select the user for analysis (individual user or overall group analysis).

4. Click on "Show Analysis" to view the generated visualizations and statistics.

5. Explore different charts and features in the application to analyze your WhatsApp chat data.


## Technologies/libraries used

Streamlit
Matplotlib
Seaborn
Pandas
emoji
urlextract
re


## Contributing

Contributions to this project are welcome☺. If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request.


## Future Improvements

- Enhance the preprocessing step to handle different chat formats(for eg.exported from iOS devices).
- Add more analysis features, such as sentiment analysis, keyword extraction, or topic modeling.
- Implement user authentication to securely analyze personal chat data.
- Integrate natural language processing techniques for advanced text analysis.
## License

License
This project is licensed under the MIT License [MIT](https://choosealicense.com/licenses/mit/)


## Demo

Demo of the WhatsApp Chat Analyser can be found here

