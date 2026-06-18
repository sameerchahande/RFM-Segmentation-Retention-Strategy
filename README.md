# RFM Segmentation & Retention Strategy

This repository contains the Part 2 capstone project for RFM-based customer segmentation and retention strategy.

## Project Overview

This project builds RFM (Recency, Frequency, Monetary) customer segments and recommends targeted retention actions for a D2C personal-care brand. The segmentation combines RFM features with additional behavioral signals to identify customer groups that need retention attention.

## Dataset

The analysis uses the provided customer snapshot dataset (`rfm_modeling_snapshot.csv`) containing:
- Customer demographics and loyalty tier
- Order history (recency, frequency, monetary value)
- Support ticket data
- Web/app activity metrics
- Campaign engagement data
- Churn labels (for context only; not used in segmentation)

**Snapshot Date:** 2025-09-30

## Repository Structure

```
part-2-capstone/
├── README.md                          # This file
├── requirements.txt                   # Python dependencies
├── rfm_segmentation.ipynb            # Main analysis notebook
├── segments.csv                       # Customer segment assignments
├── retention_strategy.md             # Retention recommendations
├── manual_review_cases.md            # Edge case analysis
└── helpers/
    └── rfm_analysis.py               # RFM utility functions
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/part-2-capstone.git
   cd part-2-capstone
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   venv\Scripts\activate  # Windows
   # OR
   source venv/bin/activate  # Mac/Linux
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Run the Jupyter Notebook

1. Start Jupyter Lab or Notebook:
   ```bash
   jupyter lab
   # OR
   jupyter notebook
   ```

2. Open `rfm_segmentation.ipynb` and run all cells.

The notebook performs:
- RFM feature creation and scoring
- Customer segmentation into 7 distinct segments
- Integration of non-RFM behavioral signals
- Visualization of segment characteristics
- Export of segment assignments to `segments.csv`

### View Results

- **segments.csv**: Contains customer_id, segment_name, and key features for all customers
- **retention_strategy.md**: Detailed retention actions for each segment
- **manual_review_cases.md**: Analysis of 10+ edge-case customers

## Customer Segments

| Segment | Description | Priority |
|---------|-------------|----------|
| Champions | High RFM scores, loyal, low complaints | Maintain |
| Loyal Customers | Consistent buyers, good engagement | Nurture |
| At-Risk Customers | Declining engagement, high churn risk | Urgent |
| Discount-Sensitive | High return rates, deal-dependent | Convert |
| Dormant Customers | Long recency, low activity | Re-engage |
| New Customers | Recent signups, low frequency | Onboard |
| High-Value but Unhappy | High spend but many complaints | Save |

## Retention Budget Prioritization

With a limited campaign budget, the recommended priority order is:

1. **At-Risk Customers** (highest ROI - prevent churn)
2. **High-Value but Unhappy** (protect revenue)
3. **Discount-Sensitive** (convert to full-price)
4. **Dormant Customers** (low cost to re-engage)
5. **New Customers** (invest in onboarding)
6. **Loyal Customers** (maintain with loyalty rewards)
7. **Champions** (lowest priority - already loyal)

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Author

Capstone Project - Part 2: RFM Segmentation & Retention Strategy

## License

MIT