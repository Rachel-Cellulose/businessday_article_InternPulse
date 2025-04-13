# BusinessDay Nigeria Articles Sentiment Analysis

This project performs sentiment analysis on news articles from BusinessDay Nigeria to uncover the general sentiment conveyed in media coverage of Nigeria's economy from 2021 to the present.

## Objectives

- Scrape articles from BusinessDay Nigeria.
- Preprocess and clean the collected text data.
- Perform sentiment and polarity scoring (positive, neutral, negative).
- Visualize sentiment trends over time.
- Provide insights into how the economic narrative has evolved through media reporting.

## Tasks

1. **Data Collection**  
   - Scrape articles across all pages of the target data source.
   
2. **Text Preprocessing**  
   - Tokenization
   - Lowercasing
   - Removing punctuation and special characters
   - Removing stop words
   - Lemmatization or stemming

3. **Sentiment & Polarity Analysis**  
   - Classify articles into positive, neutral, or negative categories.
   - Assign polarity scores to quantify emotional tone.

4. **Visualization**  
   - Generate bar charts, line graphs, word clouds, and pie charts to present findings.

## Deliverables

- A Jupyter Notebook containing the complete analysis (code and explanations).
- A comprehensive report discussing:
  - Research questions
  - Methodology
  - Key findings
- Technical documentation covering:
  - Process followed
  - Tools and libraries used
  - Challenges encountered and solutions
- A presentation deck (5–10 slides) summarizing the project.

## Tech Stack

- Python
- BeautifulSoup
- Requests
- Pandas
- NLTK / SpaCy (for text processing)
- Scikit-learn / TextBlob / Vader (for sentiment analysis)
- Matplotlib / Seaborn / WordCloud (for visualization)

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/businessday-sentiment-analysis.git
cd businessday-sentiment-analysis
