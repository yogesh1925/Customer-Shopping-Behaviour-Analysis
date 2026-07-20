🛍️ Customer Shopping Behaviour Analysis
Python  ·  Pandas  ·  NumPy  ·  Matplotlib  ·  Jupyter Notebook

📌 Overview
An end-to-end Exploratory Data Analysis (EDA) project on a retail customer dataset to uncover shopping patterns, revenue trends, customer segments, and business insights using Python libraries in Jupyter Notebook.

📁 Dataset
Detail	Info
Source	Kaggle — Customer Shopping Behavior Dataset
Records	3,900+ customer transactions
Features	18 columns including Age, Gender, Category, Purchase Amount, Season, Payment Method, Subscription Status, Review Rating, Previous Purchases
🛠️ Tools & Libraries
Tool	Purpose
Python	Core programming language
Pandas	Data cleaning, transformation, aggregation
NumPy	Numerical operations, statistics, array handling
Matplotlib	Charts, subplots, business dashboard
Jupyter Notebook	Interactive development environment
📂 Project Structure
customer-shopping-behaviour-analysis/
│
├── 01_pandas_practice.ipynb        # Data loading, cleaning, filtering, groupby
├── 02_numpy_practice.ipynb         # Arrays, statistics, CLV calculation
├── 03_matplotlib_practice.ipynb    # Charts and business dashboard
├── customer_shopping_behavior.csv  # Dataset
└── README.md                       # Project documentation
🔍 What Was Done
1️⃣ Data Cleaning & Preprocessing — Pandas
Loaded and explored 3,900+ records across 18 columns
Handled missing values in Review Rating using mean imputation
Removed duplicate rows and renamed columns for easier access
Converted data types where needed
Engineered new features: Age Group, Spend Level, Customer Lifetime Value (CLV)
2️⃣ Numerical Analysis — NumPy
Extracted numeric columns as arrays for fast computation
Calculated descriptive statistics: mean, median, std, percentiles
Performed correlation analysis between Age, Purchase Amount, and Rating
Computed CLV = Purchase Amount × Previous Purchases
Used boolean masking to segment high-value customers
3️⃣ Data Visualisation — Matplotlib
Line chart — Average purchase amount trend by age
Bar chart — Total revenue by category with value labels
Horizontal bar — Top 10 items by revenue
Histogram — Distribution of purchase amounts with mean line
Pie chart — Customer gender split
Scatter plot — Age vs Purchase Amount coloured by gender
Box plot — Purchase amount spread across seasons
2×2 Dashboard — Category revenue, age distribution, gender split, seasonal revenue
💡 Key Business Insights
Insight	Finding
🏆 Top Revenue Category	Clothing generates the highest total revenue
📅 Seasonal Trend	Winter and Fall drive the highest seasonal revenue
💳 Subscriber Behaviour	Subscribers spend significantly more than non-subscribers
💰 Top Payment Method	Credit Card and PayPal are most preferred
👥 Gender Split	Roughly equal male and female customers
⭐ High CLV Segment	Top 10% customers by CLV identified for targeting
▶️ How to Run
git clone https://github.com/yourusername/customer-shopping-behaviour-analysis.git
pip install pandas numpy matplotlib jupyter
jupyter notebook
Then run notebooks in order: 01_pandas → 02_numpy → 03_matplotlib

🎯 Skills Demonstrated
✅ Data cleaning and preprocessing
✅ Feature engineering
✅ Exploratory Data Analysis (EDA)
✅ Statistical analysis and correlation
✅ Data visualisation and dashboarding
✅ Business insight generation
✅ Jupyter Notebook documentation
🔗 Connect With Me
💼 LinkedIn: linkedin.com/in/yogeshwaran-subramanian-371909270
🐙 GitHub: [your GitHub URL]
