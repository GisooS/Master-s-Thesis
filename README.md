# README: Thesis Code Repository

## Thesis Title
**Dynamics of Sustainability Discussions on Reddit: Sentiment, Engagement, and Evolution (2019-2023)**

## Overview
This repository contains the code and scripts developed and used for the analysis presented in my thesis. The research examines sustainability-related Reddit discussions from 2019 to 2023, including sentiment analysis, engagement metrics, and trend analysis.

The tools and techniques include advanced data visualization, sentiment analysis, and the Reddit API for data extraction. Key metrics analyzed were karma, subscriber counts, and post scores.

---

## Repository Structure

- **`RedditAPI.ipynb`**: A Jupyter notebook for interacting with the Reddit API to extract posts and comments from sustainability-related subreddits.

- **`EnSu.ipynb`, `HuSu.ipynb`, `SoSu.ipynb`, `EcSu.ipynb`**: These notebooks analyze different dimensions of sustainability discussions (Environmental, Human, Social, and Economic aspects) based on Reddit data.

- **` Temporal.ipynb`**: A notebook that analyzes temporal trends in sustainability discussions, such as sentiment and engagement changes over time.

- **`Th2.ipynb`**: A central notebook that consolidates analysis from various dimensions for reporting and visualization.

- **` All.ipynb`**: Integrates data and results from all aspects (Environmental, Human, Social, and Economic) to generate comprehensive insights.

- **`client_secret_485612575425-er3n8dgic7oduvajdkrnm55l25pj9236.apps.googleusercontent.com.json`**: Configuration file containing API credentials required for accessing the Reddit API.

---

### Key Libraries Used
- `pandas` (Data manipulation)
- `matplotlib` and `seaborn` (Data visualization)
- `vaderSentiment` (Sentiment analysis)
- `PRAW` (Reddit API wrapper)
- `numpy` (Numerical computations)

---

## How to Use

1. Add your Reddit API credentials to the provided `client_secret_*.json` file.

2. Run the notebooks in the following suggested order:
   - `RedditAPI.ipynb`: Extract relevant data from Reddit.
   - `EnSu.ipynb`, `HuSu.ipynb`, `SoSu.ipynb`, `EcSu.ipynb`: Analyze the respective sustainability dimensions.
   - `Temporal.ipynb`: Perform temporal analysis on extracted data.
   - `All.ipynb`: Consolidate and integrate results.
   - `Th2.ipynb`: Final analysis and reporting.

---

## Results
The results include insights into:
- Sentiment trends in sustainability discussions.
- Engagement patterns in top sustainability posts.
- Evolution of sustainability topics and post popularity from 2019 to 2023.

---

## Citation
If you use this code in your work, please cite my thesis:

```
Author: [Gisoo Shams]  
Title: Dynamics of Sustainability Discussions on Reddit: Sentiment, Engagement, and Evolution  
Year: 2024  
```

---

## Contact
For questions or issues, please contact:
- **Name**: [Gisoo Shams]
- **Email**: [gisoo.shams@studbocconi.it]
