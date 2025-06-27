
<hr />
<h1>Credit Default Risk Classifier</h1>
<p>A machine learning project to predict borrower default risk using Logistic Regression and Decision Tree classifiers.</p>
<h2>Project Overview</h2>
<ul>
<li>Predict loan defaults using financial and credit data</li>
<li>Dataset: 32,000+ loan records</li>
<li>Accuracy: up to 91%, AUC: 0.87+</li>
</ul>
<h2>Tools &amp; Libraries</h2>
<ul>
<li>Python, Jupyter Notebook</li>
<li>Pandas, NumPy, Scikit-learn</li>
<li>Matplotlib, Seaborn</li>
</ul>
<h2>Model Evaluation</h2>

Model | Accuracy | AUC | Precision (Default) | Recall (Default)
-- | -- | -- | -- | --
Logistic Regression | 87% | 0.87 | 0.77 | 0.57
Decision Tree | 91% | 0.88 | 0.98 | 0.58


<h2>Visualizations</h2>
<ul>
<li>ROC &amp; Precision-Recall Curves</li>
<li>Confusion Matrices</li>
<li>Feature Importance (Tree-based)</li>
</ul>
<h2>Structure</h2>
<pre><code>credit-risk-classifier/
├── data/
│   └── credit_risk_dataset.csv
├── notebooks/
│   └── Loan_Default_Forecasting.ipynb
├── figures/
│   └── roc_curve.png
│   └── confusion_matrix.png
├── README.md
└── requirements.txt
</code></pre>
<h2>How to Run</h2>
<pre><code class="language-bash">git clone https://github.com/sumit3178/credit-risk-classifier.git
cd credit-risk-classifier
pip install -r requirements.txt
</code></pre>
<p>Open <code>Loan_Default_Forecasting.ipynb</code> in Jupyter Notebook.</p>
<hr />
<!--EndFragment --></BODY></HTML>
