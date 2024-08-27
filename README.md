
## Overview

This project explores the Android App Market on Google Play by analyzing and visualizing various app attributes. Using Python and popular data analysis libraries, the project examines app pricing, size, ratings, and user sentiment to uncover key trends and insights.

## Project Structure

- **`apps.csv`**: Dataset containing details of Google Play apps, including features like Price, Size, and Rating.
- **`user_reviews.csv`**: Dataset with user reviews for apps, including sentiment analysis attributes (Sentiment, Sentiment Polarity, Sentiment Subjectivity).
- **`notebooks/`**: Jupyter notebooks containing the analysis code and visualizations.
- **`images/`**: PNG files of all visualizations generated during the analysis.

## Key Objectives

1. **Data Cleaning and Preprocessing**: 
   - Handle missing values, correct data types, and remove duplicates.
  
2. **Exploratory Data Analysis (EDA)**:
   - Explore the distribution of app prices, sizes, ratings, and categories.
   - Analyze trends and correlations between key app features.
   
3. **Sentiment Analysis**:
   - Analyze user review sentiment to gauge satisfaction and its impact on ratings.

4. **Data Visualization**:
   - Generate visualizations to highlight important findings using seaborn and matplotlib.

## Setup and Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/android-app-market-analysis.git
    cd android-app-market-analysis
    ```

2. **Install Required Packages**:
    Make sure you have Python 3.x installed. Install the necessary packages using pip:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run Jupyter Notebooks**:
    Open and run the Jupyter notebooks in the `notebooks/` directory to perform the analysis and generate visualizations.
    ```bash
    jupyter notebook notebooks/
    ```

4. **View Visualizations**:
    The generated visualizations can be found in the `images/` directory.

## Key Findings

- **App Pricing**: Majority of apps are free, with paid apps showing a wide range in prices.
- **App Size**: Most apps are between 10MB and 50MB, with some categories having larger apps on average.
- **App Ratings**: The average app rating is around 4.1, with high-rated apps being more prevalent.
- **User Sentiment**: Positive sentiment is correlated with higher ratings, while negative reviews often highlight key issues.

_______________________

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
