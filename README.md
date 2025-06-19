# BanglaSenti Dataset Preparation

This repository provides the final, cleaned, and ready-to-use BanglaSenti sentiment analysis dataset for open-source, academic, and research use. All data processing, cleaning, and merging steps have been completed. Only the essential files for public delivery are included.

## Files
- `banglasenti.csv` — The final, cleaned, binary-labeled sentiment dataset (columns: `text`, `label`)
- `CITATIONS.md` — Full dataset source and citation information
- `LICENSE` — Apache 2.0 license for open/public use
- `README.md` — This documentation

## Dataset Sources
- **Bangla Sentiment Dataset (Kaggle)**  
  Source: [tasrifnurhimel/sentiment-dataset-bangla-text](https://www.kaggle.com/datasets/tasrifnurhimel/sentiment-dataset-bangla-text)  
  License: Apache 2.0
- **Bangla Sentiments in eLearning (Hugging Face)**  
  Source: [TanjimKIT/Bangla_Sentiments_in_eLearning](https://huggingface.co/datasets/TanjimKIT/Bangla_Sentiments_in_eLearning)  
  License: Apache 2.0  
  DOI: 10.57967/hf/3334

## Data Preview

| text | label |
|------|-------|
| আপনাকে কিভাবে ধন্যবাদ জানাবো আমার ভাষা নেই স্যার, | 1 |
| লাইট আরো ভালো মানের লাগান ভাই | 0 |
| মাশাল্লাহ ।আপনার কথা বলার স্টাইল দারুন। 😌ধন্যবাদ এত সহজভাবে বুঝানোর জন্য | 1 |
| আপনাকে অনেক ধন্যবাদ আপনার মুল্যবান ভিডিও দেওয়ার জন্য আপনার কাছে অনুরোধ করছি দয়া করে । | 1 |
| অনেক সুন্দর উপস্থাপনা, কঠিন বিষয়টিও অনেক সহজ হয়ে যাচ্ছে। ধন্যবাদ ভাই। | 1 |
| ভাইয়া খুব সহজে বুঝতে পারলাম এমনকি আপনার প্রশংসা অতুলনীয় | 1 |

## Usage
- Use `banglasenti.csv` directly for training, evaluation, or research in Bangla sentiment analysis.
- The dataset contains only binary labels: 0 = Negative, 1 = Positive.
- All neutral/ambiguous samples and missing values have been removed.

## License & Attribution
- Distributed under the Apache 2.0 License (see `LICENSE`).
- Please see `CITATIONS.md` for full dataset source and citation requirements.

## About
This repository is intended for public, academic, and downstream use. For integration, link this repo as the data source in your main project documentation. For questions or contributions, see the main project repository.
