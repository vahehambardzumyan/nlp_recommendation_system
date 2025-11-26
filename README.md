# Armenian News Website Analysis

## Overview
This Jupyter Notebook (`ML_MiniProject1_Vahe_Hamabardzumyan.ipynb`) presents a mini project focused on analyzing Armenian news websites. The goal is to improve Armenian NLP (Natural Language Processing) by scraping and analyzing real news text to identify linguistic patterns, sentiment, tone, and bias in media coverage of political, economic, and security issues.

Key objectives:
- Enhance the quality of Armenian datasets for training LLMs, which currently perform poorly due to limited and low-quality data.
- Understand how media shapes public perception through automated analysis of evolving sentiment and bias.

## Sections in the Notebook
1. **Problem Statement**: Explains the motivation, including challenges in Armenian NLP and media influence.
2. **Data Scraping**: Demonstrates web scraping using BeautifulSoup to fetch news content from Armenian websites (e.g., panarmenian.net). Includes example code for requesting and parsing a URL.

The notebook includes markdown cells for explanations, an image embed, and code cells for package installation and scraping.

**Note**: The provided notebook content appears truncated in the document. Full execution may require additional cells for data processing, analysis, or visualization (e.g., using libraries like pandas, NLTK, or spaCy for NLP tasks).

## Requirements
- Python 3.x
- Jupyter Notebook or JupyterLab
- Dependencies (install via `pip`):
  ```
  pip install requests beautifulsoup4 selenium
  ```
  - `requests`: For HTTP requests.
  - `beautifulsoup4`: For HTML parsing.
  - `selenium`: For advanced scraping (if dynamic content is needed).

Additional libraries may be required based on unshown cells (e.g., pandas for data handling, matplotlib for visualizations).

## How to Run
1. Clone or download the repository containing the notebook.
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
   (Create a `requirements.txt` file with the above packages if needed.)
3. Open the notebook:
   ```
   jupyter notebook ML_MiniProject1_Vahe_Hamabardzumyan.ipynb
   ```
4. Run cells sequentially. Ensure internet access for scraping examples.
5. For ethical scraping: Respect website terms, use delays between requests, and avoid overloading servers.

## Potential Extensions
- Expand scraping to multiple articles or sites.
- Add NLP tasks: Tokenization, sentiment analysis, topic modeling (e.g., using Hugging Face transformers for Armenian language support).
- Visualize results (e.g., word clouds, sentiment trends over time).

## Author
Vahe Hamabardzumyan

## License
This project is for educational purposes. No license specified; assume personal use only unless otherwise stated.

For questions or contributions, contact the author.