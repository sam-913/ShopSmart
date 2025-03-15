# ShopSmart
# A Personalized Product Recommendation System

## Project Overview
ShopSmart is a personalized product recommendation system that enhances the shopping experience by providing tailored suggestions based on customer purchase history. This project uses collaborative filtering, clustering, and hybrid recommendation techniques to improve user engagement and sales performance.

---

## Features

1. **Collaborative Filtering**
   - Uses Singular Value Decomposition (SVD) for customer-product recommendations.
   - Predicts ratings for products not yet purchased by a customer.

2. **Clustering**
   - Leverages PCA (Principal Component Analysis) for dimensionality reduction.
   - Visualizes customer clusters to identify shopping patterns.

3. **Content-Based Filtering**
   - Integrates product metadata to recommend items based on similar attributes.

4. **Feature Engineering**
   - Extracts temporal features (Year, Month, Day, Hour) from purchase data.
   - Calculates `TotalPrice` for customer spending insights.

5. **Hybrid Recommendations**
   - Combines collaborative and content-based filtering for enhanced accuracy.

---

## Technologies Used

- **Python**: Programming language.
- **Pandas**: Data manipulation and preprocessing.
- **Scikit-learn**: Machine learning and clustering.
- **Surprise**: Collaborative filtering.
- **Matplotlib**: Data visualization.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shopsmart-recommendation-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd shopsmart-recommendation-system
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Dataset

The project uses the [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail) for demonstration purposes. Ensure the dataset file is named `OnlineRetail.xlsx` and placed in the project directory.

---

## How to Run

1. **Preprocess the Data**:
   - Cleans missing values.
   - Generates temporal features (Year, Month, Day, Hour).

2. **Train Collaborative Filtering Model**:
   - Uses SVD to predict ratings.

3. **Perform Clustering**:
   - Applies PCA to visualize customer clusters.

4. **Generate Recommendations**:
   - Produces personalized product recommendations based on collaborative filtering.

5. **Visualize Results**:
   - Creates scatter plots for customer clusters and bar charts for recommendations.

Run the main script:
```bash
python main.py
```

---

## Results

1. **Customer Clusters**:
   - Identifies groups of customers with similar purchasing behavior.

2. **Top Recommendations**:
   - Suggests products tailored to individual customers.

3. **Product Insights**:
   - Highlights popular and high-performing products.

---

## Project Structure

```
shopsmart-recommendation-system/
│
├── data/                   # Dataset folder
├── notebooks/              # Jupyter notebooks for experiments
├── src/                    # Source code
├── main.py                 # Main execution script
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## Future Enhancements

1. **Real-Time Recommendations**:
   - Integrate live data streams for dynamic recommendations.

2. **Enhanced Hybrid Models**:
   - Combine collaborative filtering with advanced deep learning techniques.

3. **Deployment**:
   - Build a web application using Flask or Streamlit for user interaction.

---

## Contributing

Contributions are welcome!

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail) for the dataset.
- Open-source libraries: Pandas, Scikit-learn, Surprise, Matplotlib.
