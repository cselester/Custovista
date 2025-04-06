# Custovista AI Pipeline

This project demonstrates an end-to-end AI pipeline for Customer360 insights, providing a comprehensive view of customer behavior and risk, and is named **Custovista**. This includes:

- **Data Ingestion:** Generates synthetic customer and transaction data using Faker.
- **Segmentation:** Segments customers using RFM analysis.
- **Fraud Detection:** Identifies potentially fraudulent transactions and customers.
- **Recommendation:** Recommends products based on customer segments and risk profiles.
- **Oversight:** Escalates high-risk cases for human review.


## Getting Started

### Prerequisites

- **Google Colab:** This project is designed to run in Google Colab.
- **Python 3.9+:** Ensure you have Python 3.9 or higher installed.
- **Libraries:** The required libraries are listed in `requirements.txt`.
  - You can install them using `pip install -r requirements.txt` in a Colab notebook cell.

### Running the Pipeline

1. **Open `run.py` in Google Colab:** Upload the `run.py` file to your Colab environment.
2. **Install dependencies:** In a Colab notebook cell, run `!pip install -r requirements.txt` to install the necessary libraries.
3. **Execute the pipeline:** Run all the cells in the `run.py` notebook.
4. **View Results:** The final customer insights will be saved to `output/final_customer360_result.csv`.


## Components

- **`ingestion_agent.py`:** Responsible for generating synthetic customer and transaction data.
- **`segmentation_agent.py`:** Segments customers based on RFM analysis.
- **`fraud_detection_agent.py`:** Detects fraudulent transactions and assesses customer risk.
- **`recommendation_agent.py`:** Provides product recommendations.
- **`oversight_panel_agent.py`:** Flags high-risk cases for review.


## Running the Gradio UI

1.  **Install Gradio:**
