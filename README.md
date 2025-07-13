# BanglaSenti Dataset Preparation: Bangla Sentiment Analysis CSV Dataset for NLP & Machine Learning

**BanglaSenti** is a comprehensive, open-source Bangla sentiment analysis dataset in CSV format, designed for natural language processing (NLP), machine learning, and deep learning research. This dataset is ideal for training, fine-tuning, and benchmarking models such as Bangla-BERT and other transformer-based architectures. All data processing, cleaning, deduplication, and column trimming have been completed using Google Sheets data format functions and Apps Script, ensuring high quality and usability. Only the essential files for public delivery are included.

## Files Included
- `banglasenti.csv` — The final, cleaned, sentiment-labeled dataset (columns: `text`, `label`). Ready for direct use in NLP and machine learning projects.
- `CITATIONS.md` — Full dataset source and citation information for proper academic and research attribution.
- `LICENSE` — Apache 2.0 license for open/public use, allowing free use in research and commercial projects.
- `README.md` — This documentation, optimized for search engines and user clarity.

## Dataset Sources
- See [`CITATIONS.md`](./CITATIONS.md) for all dataset sources and citation details.

## Main Project Repository
- [LoRA Fine-Tuning of BanglaSenti on XLM-RoBERTa-Base Using Google TPUs](https://github.com/niloydebbarma-code/LoRA-Fine-Tuning-of-BanglaSenti-on-Bangla-BERT-Base-Using-Google-TPUs)

## Data Preview

| text | label |
|------|-------|
| আপনাকে কিভাবে ধন্যবাদ জানাবো আমার ভাষা নেই স্যার, | 1 |
| লাইট আরো ভালো মানের লাগান ভাই | 0 |
| মাশাল্লাহ ।আপনার কথা বলার স্টাইল দারুন। 😌ধন্যবাদ এত সহজভাবে বুঝানোর জন্য | 1 |
| মেঘের আড়ালে তুমি (হার্ডকভার) | 2 |
| দ্য গডফাদার (হার্ডকভার) | 1 |
| নীললোহিতের সেরা ৯ (হার্ডকভার) | 2 |

## Usage & Applications
- Use `banglasenti.csv` directly for training, evaluation, or research in Bangla sentiment analysis, text classification, and NLP tasks.
- The dataset contains three sentiment labels for supervised learning:
  - 0 = Negative
  - 1 = Positive
  - 2 = Neutral
- The dataset has been expanded with more data and now includes neutral samples, making it suitable for multi-class classification.
- Perfect for use with BERT, Bangla-BERT, and other transformer models, as well as traditional machine learning algorithms.

## License & Attribution
- Distributed under the Apache 2.0 License (see `LICENSE`).
- Please see `CITATIONS.md` for full dataset source and citation requirements. Proper attribution is required for academic and commercial use.

## About
This repository is intended for public, academic, and downstream use. For integration, link this repo as the data source in your main project documentation. For questions or contributions, see the main project repository. Keywords: Bangla sentiment analysis, Bangla dataset, CSV, NLP, machine learning, BERT, Google Sheets, deduplication, open-source, text classification, transformer, research, academic, fine-tuning.

## Dataset Size
- Total rows (including header): 122,578
- File size: 17 MB
