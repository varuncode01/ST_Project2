<h1 align="center">🚀 ML Project: Predicting Run Time Categories & Booking Cancellations</h1>

<p align="center">
  <strong>Data-driven approach to understanding and predicting booking behavior</strong>
</p>

<hr/>

<h2>📌 Objective</h2>
<ul>
  <li>Predict <strong>Average Run Time Category</strong> for bookings.</li>
  <li>Analyze patterns behind <strong>booking cancellations</strong>.</li>
  <li>Improve customer experience and reduce operational inefficiencies using ML models.</li>
</ul>

<h2>📊 Dataset Overview</h2>
<p>The dataset contains features such as:</p>
<ul>
  <li>Waiting Days</li>
  <li>Booking Channel</li>
  <li>Lead Time</li>
  <li>Previous Cancellations</li>
  <li>Customer Segment</li>
</ul>

<h2>🧠 ML Models Used</h2>

<h3>Regression Models</h3>
<ul>
  <li>Logistic Regression (Baseline)</li>
  <li><strong>Random Forest Regressor</strong> ✅ <em>(Best Performing)</em></li>
  <li>K-Nearest Neighbors Regressor</li>
</ul>

<h3>Classification Models</h3>
<ul>
  <li>Logistic Regression Classifier</li>
  <li>Random Forest Classifier</li>
  <li>K-Nearest Neighbors Classifier</li>
</ul>

<h2>🏆 Final Model Selection</h2>
<p><strong>Selected Model:</strong> <code>RandomForestRegressor</code></p>

<table>
  <tr><th>Metric</th><th>Value</th></tr>
  <tr><td>R² Score</td><td>0.997</td></tr>
  <tr><td>MAE</td><td>0.1536</td></tr>
  <tr><td>RMSE</td><td>0.3876</td></tr>
</table>

<p><strong>Why?</strong> It demonstrated excellent accuracy, low error, and strong generalization on unseen data.</p>

<h2>🔍 Feature Importance (Explainability)</h2>
<ul>
  <li><strong>Waiting Days</strong>: Strongest predictor of cancellations.</li>
  <li><strong>Lead Time</strong>: Longer lead time increased likelihood of dropout.</li>
  <li><strong>Booking Channel</strong>: Certain platforms had better conversion.</li>
  <li><strong>Previous Cancellations</strong>: Highly indicative of repeat behavior.</li>
</ul>

<p>Tools used: <code>.feature_importances_</code>, SHAP, LIME.</p>

<h2>📊 Visual Results</h2>
<p>
  For all model visualizations — including prediction vs actual plots, confusion matrices, and feature importance charts — please refer to the <code>ML_Project2.ipynb</code> notebook.
</p>
<ul>
  <li>🔍 Model performance visualized across 3 regression techniques</li>
  <li>📉 Classification evaluation with confusion matrices</li>
  <li>📌 Feature importance explained using built-in tools</li>
</ul>

<h2>📈 Business Impact</h2>
<ul>
  <li>Minimize cancellations with proactive engagement.</li>
  <li>Optimize waiting time and channel efficiency.</li>
  <li>Drive data-backed strategies for customer satisfaction and cost savings.</li>
</ul>

<h2>🧰 Technologies Used</h2>
<ul>
  <li>Python 3.x</li>
  <li>Pandas, NumPy</li>
  <li>Scikit-learn</li>
  <li>Matplotlib, Seaborn</li>
  <li>SHAP / LIME (for explainability)</li>
</ul>

<h2>📁 Folder Structure</h2>

<pre>
ML_Project2/
├── ML_Project2.ipynb       # Main notebook
├── README.md               # This documentation file
├── 📊 Visuals/              # Prediction vs Actual charts, confusion matrices
</pre>

<h2>✅ Conclusion</h2>
<p>
  The <strong>RandomForestRegressor</strong> delivered outstanding prediction performance with strong interpretability.
  This project provides a reliable machine learning solution for anticipating booking behavior and enhancing business processes through predictive analytics.
</p>

