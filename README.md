Klasifikasi Kematangan Pisang dengan K-Nearest Neighbor (KNN)
Metodologi
Pendekatan menggunakan tiga pembagian data yang sudah disediakan oleh dataset:

Train	Disimpan sebagai referensi oleh KNN
Validation	Dipakai untuk mencari nilai K terbaik
Test	Dipakai satu kali di akhir untuk mengukur performa akhir model

Alur kerja:
1. Ekstraksi fitur (Mean HSV) dari Train, Validation, dan Test set
2. Tuning nilai K menggunakan Validation set
3. Evaluasi akhir menggunakan Test set (akurasi, confusion matrix, classification report)
4. Contoh prediksi beberapa gambar

Sumber dataset: https://www.kaggle.com/datasets/shahriar26s/banana-ripeness-classification-dataset/data
