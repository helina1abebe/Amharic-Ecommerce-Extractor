# **Amharic E-commerce Data Extractor**

## **Project Overview**
The **Amharic E-commerce Data Extractor** is a tool designed to transform unstructured Telegram posts from Ethiopian e-commerce channels into structured, machine-readable data. This data is used to build a centralized platform for EthioMart, enabling better vendor analysis and decision-making for micro-lending opportunities.

---

## **Key Features**
- Scrape data (text, images, metadata) from Telegram channels.
- Preprocess Amharic text for Named Entity Recognition (NER).
- Fine-tune pre-trained models for Amharic NER tasks to extract entities like:
  - Product names and types.
  - Prices and monetary values.
  - Location mentions.
- Compare multiple models for performance and interpretability.
- Create a vendor scorecard for business analytics.

---

## **Project Structure**
```plaintext
Amharic-Ecommerce-Extractor/
├── data/                     # Contains raw and labeled datasets
├── models/                   # Saved fine-tuned models
├── scripts/                  # Python scripts for various tasks
│   ├── scrape_telegram.py    # Script to scrape Telegram data
│   ├── preprocess_data.py    # Script to preprocess and clean data
│   ├── label_data.py         # Script for annotating data
│   ├── train_model.py        # Script to fine-tune the NER model
│   ├── evaluate_model.py     # Script to evaluate and compare models
│   ├── vendor_analytics.py   # Script to generate vendor metrics and scorecard
├── reports/                  # Generated reports and visualizations
├── requirements.txt          # List of Python dependencies
└── README.md                 # Project documentation
