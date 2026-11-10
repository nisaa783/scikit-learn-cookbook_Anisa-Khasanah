# scikit-learn-cookbook_Anisa-Khasanah

Repositori ini dibuat untuk memenuhi tugas Enrichment for Machine Learning Classes. Berisi reproduksi kode pemrograman serta kajian teoretis dari setiap bab berdasarkan buku scikit-learn Cookbook (Third Edition) karya John Sukup.

## Daftar Isi dan Ringkasan Bab

Chapter 1: Common Conventions and API Elements of scikit-learn
Mempelajari filosofi desain scikit-learn yang konsisten, meliputi objek Estimator, Transformer, Predictor, serta penggunaan Pipeline untuk otomatisasi alur kerja machine learning.

Chapter 2: Pre-Model Workflow and Data Preprocessing
Fokus pada pembersihan data mentah, penanganan missing values, teknik feature scaling (seperti StandardScaler), dan encoding variabel kategorikal.

Chapter 3: Dimensionality Reduction Techniques
Mempelajari cara mereduksi dimensi fitur menggunakan Principal Component Analysis (PCA) untuk unsupervised learning, Linear Discriminant Analysis (LDA) untuk supervised learning, serta t-SNE untuk visualisasi data.

Chapter 4: Building Models with Distance Metrics and Nearest Neighbors
Membahas algoritma K-Nearest Neighbors (KNN) untuk klasifikasi dan regresi berdasarkan berbagai metrik jarak serta hyperparameter tuning.

Chapter 5: Linear Models and Regularization
Mempelajari regresi linear dan teknik regularisasi seperti Ridge (L2) dan Lasso (L1) untuk mengatasi overfitting dan multikolinearitas.

Chapter 6: Advanced Logistic Regression and Extensions
Memperluas regresi logistik untuk klasifikasi multikelas (multinomial) serta penerapan regularisasi pada model linier diskrit.

Chapter 7: Support Vector Machines and Kernel Methods
Mempelajari Support Vector Machines (SVM) untuk mencari hyperplane pemisah optimal dan penggunaan Kernel Trick (seperti RBF) untuk data non-linear.

Chapter 8: Tree-Based Algorithms and Ensemble Methods
Membahas Decision Trees serta metode ensemble seperti Random Forest (Bagging) dan Gradient Boosting Machines (Boosting).

Chapter 9: Text Processing and Multiclass Classification
Mempelajari pemrosesan teks, ekstraksi fitur menggunakan TF-IDF, serta pembangunan model klasifikasi teks.

Chapter 10: Clustering Techniques
Mempelajari unsupervised learning untuk pengelompokan data tanpa label, dengan fokus pada K-Means Clustering dan perhitungan inersia.

Chapter 11: Novelty and Outlier Detection
Mempelajari teknik deteksi anomali dan pencilan menggunakan Isolation Forest, One-Class SVM, Local Outlier Factor (LOF), dan elliptic envelope.

Chapter 12: Cross-Validation and Model Evaluation
Mempelajari teknik validasi silang seperti K-Fold dan Stratified CV, proses tuning hyperparameter dengan GridSearchCV, metrik evaluasi model, serta learning curves.

Chapter 13: Deploying Models in Production
Mempelajari cara serialisasi model menggunakan joblib atau pickle, integrasi pipeline untuk produksi, serta penyajian model machine learning.

## Cara Penggunaan

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation
```bash
# Clone the repository
git clone [https://github.com/farrelrassya/scikit-learn-cookbook.git](https://github.com/farrelrassya/scikit-learn-cookbook.git)
cd scikit-learn-cookbook

# Install dependencies
pip install scikit-learn numpy pandas matplotlib seaborn jupyter

# Launch Jupyter
jupyter notebook
