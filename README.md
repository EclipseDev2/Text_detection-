# Text Sentiment Analysis App

This is a simple sentiment analysis app built using Python with a Tkinter GUI, NLTK for sentiment analysis, and various other libraries for text processing and visualization.

## Features

- **Sentiment Analysis**: The app analyzes the sentiment of the text entered by the user. It detects if the text is positive, negative, or neutral based on the sentiment score.
- **Live Text Update**: As the user types in the text field, the app updates and displays the current text with the analysis results.
- **GUI Interface**: Built with Tkinter for a simple and responsive user interface.
  
## Prerequisites

Make sure you have the following installed on your system:

- **Python 3.x** (version 3.6 or above recommended)
- **pip** (Python package installer)

## Installation

1. Clone this repository or download the code files.
   
    ```bash
    git clone https://github.com/EclipseDev2/text-sentiment-analysis-app.git
    cd text-sentiment-analysis-app
    ```

2. Create a virtual environment (optional but recommended):

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. If you don't have the `vader_lexicon` resource installed, the app will automatically download it when you run the code.

## Dependencies

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib**: For creating visualizations like plots.
- **nltk**: For natural language processing, including the SentimentIntensityAnalyzer.
- **tkinter**: For creating the GUI interface (this is typically pre-installed with Python).

You can install the dependencies manually using:

```bash
pip install pandas numpy matplotlib nltk
```

If you're missing Tkinter, you may need to install it separately:

- **Linux**: `sudo apt-get install python3-tk`
- **macOS/Windows**: Tkinter is usually pre-installed with Python.

## Running the App

1. Ensure that the virtual environment is activated (if using one).
2. Run the application:

    ```bash
    python app.py
    ```

3. The application window will open. Type a sentence in the text box, and the app will display the sentiment analysis results (positive, negative, or neutral).
