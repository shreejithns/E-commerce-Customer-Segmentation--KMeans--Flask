# 🛍️ Customer Segmentation for E-Commerce using KMeans

Segment your e-commerce customers intelligently based on behavior and demographics using Machine Learning. This project uses **KMeans Clustering** to group customers by spending score, income, and frequency — giving businesses powerful insight into their audience.

---

## 🚀 Features

- 🧮 **Customer Clustering** using KMeans
- 📊 **Interactive Visualizations**:
  - Elbow Method Plot
  - PCA 2D & 3D Projections
  - Pie & Bar Charts for Segment Distribution
- 🔍 **Silhouette Score** for cluster validation
- 👨‍💼 Simple UI for shop owners
- 👨‍💻 **Data Science Mode** toggle for advanced visual analysis
- ⬇️ **CSV Export** of clustered data with segment labels:
  - Budget Shoppers
  - High Spenders
  - Occasional Buyers
  - Loyal Customers

---

## 🛠 Tech Stack

| Component        | Tech Used                 |
|------------------|---------------------------|
| Language         | Python 3.x                |
| Backend          | Flask Web Framework       |
| ML Libraries     | Scikit-learn, Pandas, NumPy |
| Visualization    | Matplotlib, Seaborn       |
| Frontend         | Tailwind CSS, HTML5, Jinja2 Templates |

---

## 🧠 How It Works

1. **Upload** a customer CSV file with features like `Spending Score`, `Income`, etc.
2. The backend **preprocesses** the data and runs **KMeans clustering**.
3. Clusters are visualized using interactive charts and PCA plots.
4. Output includes **segment labels** and a downloadable CSV for marketing analysis.

---

## 📁 Folder Structure

```
├── app.py                # Main Flask application
├── templates/            # HTML templates (Jinja2)
├── static/               # Tailwind CSS, JS, and assets
├── data/                 # Sample input CSV and output
├── clustering/           # ML logic and plots
├── outputs/              # Labeled customer segments
├── requirements.txt      # Python dependencies
├── README.md
```

---

## 🧪 Sample Segments

- 🧍 Budget Shoppers
- 💸 High Spenders
- 🔁 Occasional Buyers
- 🔁 Loyal Customers

---

## 📥 Setup Instructions

### 🔹 Step 1: Clone the Repo

```bash
git clone https://github.com/yourusername/ecommerce-customer-segmentation.git
cd ecommerce-customer-segmentation
```

### 🔹 Step 2: Install Requirements

```bash
pip install -r requirements.txt
```

### 🔹 Step 3: Run the App

```bash
python app.py
```

Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) to use the dashboard.

---

## 📊 Input Format

Example CSV format:

| CustomerID | Age | Income | SpendingScore | Frequency |
|------------|-----|--------|----------------|-----------|
| 101        | 25  | 50K    | 60             | 8         |

---

## 📦 What You Get in the Download

- ✅ Full source code (`app.py`, HTML templates, static assets)
- ✅ Pre-designed UI with Tailwind CSS
- ✅ Sample dataset and output files
- ✅ Project Report + PPT (Bonus for students)
- ✅ Readme + setup guide

---

## 📜 LICENSE

This project is released under the **MIT License**.

---

## 🙋‍♂️ AUTHOR

Built with ❤️ by **Shreejith N S**  
🔗 [linkedin.com/in/shreejithnsdev](https://linkedin.com/in/shreejithnsdev)  
💻 [github.com/shreejithns](https://github.com/shreejithns)

---

## 🤝 CONTRIBUTIONS

Pull requests, forks, and issues are welcome! Let's improve it together.
