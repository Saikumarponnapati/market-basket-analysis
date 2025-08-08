
# Market Basket Analysis using Apriori Algorithm

This project demonstrates how to perform **Market Basket Analysis** using association rule mining techniques. The **Apriori algorithm** is used to find frequent itemsets and generate rules that can be used for product recommendations and sales strategy.

## 📁 Project Structure

```
marketbasketanalysis.ipynb  # Jupyter Notebook with full analysis and visualization
```

## 📊 Objective

- Discover associations between products purchased together.
- Generate actionable rules using support, confidence, and lift.
- Visualize item frequencies and rule metrics.

## 🔍 Key Features

- Data Preprocessing for transaction formatting
- Generation of Frequent Itemsets using the Apriori algorithm
- Association Rule Mining using metrics like support, confidence, and lift
- Visualization of frequent items and rule patterns

## 🧠 Algorithms Used

- **Apriori Algorithm** (from `mlxtend`)
- **Association Rule Mining**

## 📦 Libraries Used

- pandas
- matplotlib
- seaborn
- mlxtend (for `apriori` and `association_rules`)

## 🚀 How to Run

1. Install required libraries:
```bash
pip install pandas matplotlib seaborn mlxtend
```

2. Open the notebook:
```bash
jupyter notebook marketbasketanalysis.ipynb
```

3. Run all cells to view the analysis and results.

## 📈 Outputs

- Bar charts showing frequent itemsets
- Association rules with metrics: support, confidence, lift
- Filtered rules for strong product associations

## 💼 Use Cases

- Recommender Systems
- Market Basket Optimization
- Cross-selling Strategy

## 📄 License

This project is intended for educational and non-commercial purposes.
