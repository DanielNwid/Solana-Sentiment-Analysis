Solana X Sentiment Analysis for Fraud Detection
This project for the Messari Crime Fighting AI Toolkit Hackathon analyzes X sentiment to spot potential Solana scams using Messari’s Signal API. It flags days with unusual activity that might signal a pump and dump scheme.

Key Findings
Analyzed 8 days of X data for Solana in April 2025 and flagged 6 as suspicious:April 19, 2025: 2,955 posts, mood shifted super fast.April 21, 2025: 3,600 posts, a huge spike.April 22, 2025: 4,517 posts, way too positive.  
How to Run

Install dependencies:

pip install requests pandas numpy


Get a Messari API key from Messari and add it to YOUR_API_KEY in the Jupyter Notebook.  
Open solana-sentiment-analysis (2).ipynb in Jupyter Notebook and run all cells.  
Results will be in solana_sentiment_analysis.csv with dates, sentiment scores, tweet volumes, momentum, and flags.

Repository Files
solana-sentiment-analysis (2).ipynb: Jupyter Notebook with code and analysis.
solana_sentiment_analysis.csv: Output file with flagged days (generated after running the code).  


More Details

Full writeup on Substack: Detecting Scams on Solana.
Twitter thread with highlights: View on X https://x.com/Daniel_Onchain/status/1917604639802904927.

Acknowledgments
Thanks to the Messari Crime Fighting AI Toolkit Hackathon, Messari’s Signal API, Helius, and Superteam for their support.
