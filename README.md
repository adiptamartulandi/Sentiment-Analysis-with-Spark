# 🎈 🎉 Sentiment-Analysis-with-Spark 🎊 🎈 📚 

- Pada Repository ini, terdiri dari Code untuk melakukan Sentiment Analysis menggunakan Pyspark dan Tanpa Pyspark.
- Jadi saya membuat 2 versi.
- Versi yang pertama adalah menggunakan pyspark namun secara lokal. Jadi saya menginstall pyspark di laptop saya.
- Versi yang kedua adalah menggunakan library selain pyspark.
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖  

# Contents
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖  

- Code
- Menggunakan Pyspark
- Tanpa Menggunakan Pyspark
- Interpretasi

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

# Code
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

- Seluruh Pengerjaan dilakukan di Jupyter Notebook.
- Dataset tidak saya upload karena ukuranya sangat besar.

# Menggunakan Pyspark
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
- Bagi kalian yang belum install pyspark di laptop bisa datang ke situs ini:
  - https://bigdata-madesimple.com/guide-to-install-spark-and-use-pyspark-from-jupyter-in-windows/
- Disini saya menggunakan 3 Algoritma yaitu Logistic Regression, Naive Bayes, dan Linear SVC.
- Saya tidak menggunakan algoritma seperti Decision Tree, KNN, SVM, Random Forest karena waktu ngerun sangat lama karena datanya terlalu besar.
- Untuk Feature Extraction Text saya menggunakan 2 metode yaitu CountVectorizer + IDF dan TF + IDF.
- Hasilnya adalah model yang menggunakan Count Vectorizer + IDF + Logistic Regression memberikan nilai Akurasi dan AUC yang paling tinggi.
- Nilai Akurasi Skor yang didapat adalah sebesar 79%.
- Nilai AUC yang didapat adalah sebesar 86%.

# Tanpa Menggunakan Pyspark
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

- Algoritma yang digunakan adalah 3 yaitu Logistic Regression, Naive Bayes, dan Linear SVC.
- Feature Extraction Text yang saya gunakan adalah Count Vectorizer dan TF-IDF.
- Hasil model yang saya pilih ...
- Nilai Akurasi Skor sebesar
- Nilai AUC Skor sebesar


# Interpretasi Hasil
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

- Menggunakan Pyspark ternyata dapat mengimprove performa dari AUC Score yaitu bisa mencapai 86% jika dibandingkan model terbaik tanpa menggunakan Pyspar yang hanya mampu mencapai di angka 80%.
- Untuk nilai akurasi model terbaik menggunakan Pyspark dan Tanpa menggunakan Pyspark tidak jauh berbeda yaitu di kisaran angka 79%.
- Namun perlu diingat bahwa ketika menggunakan Pyspark saya tidak melakukan EDA dan Data Cleansing.
