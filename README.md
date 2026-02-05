<h1>📊 Customer Segmentation using Machine Learning</h1>

<h2>🔍 Project Overview</h2>
<p>
This project focuses on <b>customer segmentation</b> using <b>unsupervised machine learning</b>.
Customers are grouped based on their demographic and behavioral data to help businesses
make <b>data-driven decisions</b>.
</p>

<p>
The project uses the <b>K-Means Clustering algorithm</b> to segment customers based on
<b>Age, Annual Income, and Spending Score</b>. The trained model is saved as a
<b>.pkl file</b> and deployed using a <b>production-level Streamlit dashboard</b>.
</p>

<hr>

<h2>🧠 Algorithm Used</h2>
<ul>
  <li>K-Means Clustering (Unsupervised Machine Learning)</li>
  <li>Feature Scaling using StandardScaler</li>
  <li>Model Evaluation using Silhouette Score</li>
</ul>
<hr>
<h2>🖥️ Tech Stack</h2>
<ul>
  <li>Python</li>
  <li>Pandas, NumPy</li>
  <li>Scikit-learn</li>
  <li>Matplotlib, Seaborn</li>
  <li>Streamlit</li>
  <li>Pickle (.pkl)</li>
</ul>

<hr>
<h2>📁 Project Structure</h2>
<pre>
customer-segmentation/
│
├── customer-segmentation.ipynb
├── app.py
├── Mall_Customers.csv
├── customer_segmentation_model.pkl
└── README.md
</pre>

<hr>

<h2>▶️ How to Run</h2>
<pre>
pip install pandas numpy scikit-learn matplotlib seaborn streamlit
streamlit run app.py
</pre>

<hr>

<h2>🏆 Conclusion</h2>
<p>
This project demonstrates how <b>machine learning can transform raw customer data into
valuable business insights</b> and how ML models can be deployed in a
<b>company-level production environment</b>.
</p>