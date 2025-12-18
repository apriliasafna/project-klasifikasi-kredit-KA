# Klasifikasi Kelancaran Pembayaran Kredit

Project ini merupakan tugas mata kuliah yang bertujuan untuk melakukan klasifikasi kelancaran pembayaran kredit menggunakan beberapa algoritma Machine Learning, yaitu Logistic Regression, Random Forest, dan Artificial Neural Network (ANN).

## Deskripsi Project

Klasifikasi kelancaran pembayaran kredit dilakukan untuk memprediksi apakah seorang nasabah memiliki status pembayaran kredit yang lancar atau tidak lancar berdasarkan karakteristik dan informasi finansial yang dimiliki. Project ini membandingkan performa beberapa model Machine Learning untuk memperoleh model dengan hasil evaluasi terbaik.

## Dataset

Dataset yang digunakan dalam project ini berisi data karakteristik nasabah kredit, termasuk informasi demografis, kondisi keuangan, dan riwayat kredit. Karena ukuran dataset cukup besar, dataset tidak diunggah langsung ke GitHub.

Dataset dapat diakses melalui Google Drive pada tautan berikut:
**(https://drive.google.com/drive/folders/1Q_WzmY3j1z7gCeddJyQLL92r4wY2SdCe?usp=drive_link)**

Sebagai tambahan, struktur dataset dapat dipahami melalui notebook yang disertakan dalam repository ini.

## Tahapan Pengerjaan

Tahapan yang dilakukan dalam project ini meliputi:

1. Data understanding dan eksplorasi data
2. Data preprocessing (cleaning, encoding)
3. Penerapan dua skenario preprocessing data:

   * **Skenario 1**: Data ditangani outlier terlebih dahulu kemudian dilakukan scaling
   * **Skenario 2**: Data tidak dilakukan penanganan outlier dan langsung dilakukan scaling
4. Penanganan ketidakseimbangan kelas menggunakan metode Random Over Sampling (ROS) dan Synthetic Minority Over-sampling Technique (SMOTE)
5. Pembangunan model klasifikasi
6. Evaluasi model menggunakan confusion matrix dan metrik performa

## Penanganan Ketidakseimbangan Data

Dataset kredit yang digunakan memiliki distribusi kelas yang tidak seimbang antara kelas pembayaran lancar dan tidak lancar. Untuk mengatasi permasalahan tersebut, digunakan dua metode oversampling, yaitu Random Over Sampling (ROS) dan Synthetic Minority Over-sampling Technique (SMOTE).

Selain itu, penelitian ini menerapkan dua skenario preprocessing data untuk menganalisis pengaruh penanganan outlier terhadap performa model. Pada skenario pertama, data terlebih dahulu ditangani outlier-nya sebelum dilakukan proses scaling. Sementara pada skenario kedua, data tidak dilakukan penanganan outlier dan langsung masuk ke tahap scaling. Kedua skenario ini kemudian dikombinasikan dengan metode ROS dan SMOTE untuk membandingkan performa model klasifikasi secara menyeluruh.

## Algoritma yang Digunakan

* Logistic Regression
* Random Forest
* Artificial Neural Network (ANN)

## Evaluasi Model

Evaluasi model dilakukan menggunakan confusion matrix serta metrik akurasi, precision, recall, dan F1-score untuk membandingkan kinerja masing-masing algoritma dalam melakukan klasifikasi.

## Tools dan Library

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* TensorFlow / Keras

## Cara Menjalankan Project

1. Buka file notebook (`.ipynb`) menggunakan Google Colab atau Jupyter Notebook.
2. Pastikan dataset telah diunduh dari Google Drive dan diletakkan pada path yang sesuai.
3. Jalankan setiap cell secara berurutan untuk melihat proses dan hasil pemodelan.
