# Project_Text_classification_Email_Spam
![image](https://github.com/user-attachments/assets/bec6a29f-3a06-44cb-a8a0-3e4cc4381ca6)
# Dataset
![image](https://github.com/user-attachments/assets/d0fe860c-9040-4281-8a37-e06fd8210d66)

# Latar Belakang dan Masalah
Spam email telah menjadi salah satu masalah besar di dunia digital saat ini. Setiap hari, jutaan email spam dikirimkan ke pengguna internet, mengganggu produktivitas dan seringkali berisi konten yang merugikan, seperti penipuan atau malware. Pengguna sering kali membuang waktu untuk memilah antara email yang sah dan spam. Oleh karena itu, diperlukan sebuah sistem otomatis yang dapat mengklasifikasikan email dengan akurat sebagai spam atau bukan spam (ham). Dengan menggunakan teknik pembelajaran mesin, kita dapat mengembangkan model yang mampu mengenali pola dalam email dan memisahkan spam dari email yang sah. Membangun model klasifikasi email spam akan meningkatkan efisiensi, mengurangi gangguan, dan meningkatkan keamanan pengguna.
# Tujuan dan Target Pencapaian
# Data loading
Proses ini melibatkan pemuatan dataset email yang berisi email spam dan non-spam (ham). Data akan diimpor dari sumber yang relevan (misalnya dataset UCI Spam, Enron Spam, atau dataset kustom) yang berisi teks email beserta label spam/non-spam.
![Screenshot 2025-03-17 150207](https://github.com/user-attachments/assets/9d7bcd6b-76de-46f2-b3d9-608861af7623)

# Data Cleaning
Tahap ini mencakup pembersihan data untuk memastikan kualitas yang baik. Pembersihan ini termasuk menghapus email yang duplikat, menangani nilai yang hilang, serta membersihkan teks email dari karakter-karakter yang tidak relevan seperti HTML tags, spasi ganda, dan simbol yang tidak diperlukan.
# EDA (Exploratory Data Analysis)
Di tahap ini, dilakukan eksplorasi data untuk memahami distribusi email spam dan ham, serta identifikasi pola-pola yang dapat membantu dalam klasifikasi. EDA juga mencakup analisis frekuensi kata-kata yang sering muncul dalam email spam dan ham, serta melihat hubungan antar fitur untuk memahami karakteristik email yang dapat mempengaruhi prediksi.
# Feature Engineering
Pada tahap ini, fitur yang relevan akan diekstraksi dari teks email, seperti menghitung frekuensi kata-kata tertentu, mengidentifikasi n-gram, atau menggunakan teknik representasi teks seperti TF-IDF atau Word2Vec. Teknik ini akan memperkaya informasi dalam dataset untuk meningkatkan performa model.
# Model Architecture Definition
Setelah data dipersiapkan, langkah selanjutnya adalah mendefinisikan arsitektur model pembelajaran mesin yang akan digunakan untuk klasifikasi. Untuk model yang digunakan dalam klasifikasi teks proyek ini yaitu model berbasis deep learning seperti LSTM.
# Model Training
Pada tahap ini, model yang telah didefinisikan akan dilatih menggunakan dataset yang sudah diproses. Proses ini melibatkan pembagian data menjadi set pelatihan dan set pengujian, kemudian melakukan pelatihan model dengan algoritma yang dipilih untuk mempelajari pola dalam data dan melakukan klasifikasi spam.
# Model Evaluasi
Setelah pelatihan selesai, model dievaluasi menggunakan berbagai metrik evaluasi seperti akurasi, presisi, recall, F1-score, dan kurva ROC-AUC. Evaluasi ini penting untuk memastikan bahwa model dapat mengklasifikasikan email dengan akurat dan dapat diandalkan, serta untuk menganalisis trade-off antara deteksi spam dan menghindari kesalahan klasifikasi (false positives atau false negatives).
# Conclusion
