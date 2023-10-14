# Proyek-ML-2023
Ulaslah hal – hal di bawah ini dalam video dan laporan yang kalian buat: 
1. Introduction to dataset
  o Jelaskan dengan singkat latar belakang dan tujuan dataset yang kalian gunakan,
  jumlah records, jumlah features, daftar features yang ada, dll
  o Tujuan machine learning: regression atau classification, pola atau kelas apa yang
  dicari, dll
2. Data cleaning and preprocessing
  o Pengecekan data
  o Cleaning data: misal data yang tidak lengkap (ada yang NaN), data yang bersifat
  outlier
  o Normalisasi data (supaya setiap feature memiliki skala yang sama) jika diperlukan
  o Dan pemrosesan lain yang relevan
3. Pilih algoritma machine learning dan lakukan analisa:
  o Untuk regresi bisa menggunakan (minimal) salah satu model (regresi linier, k-NN)
  dan melakukan analisa (misal menggunakan 4 pertanyaan dari halaman 84):
    1. Apakah ada hubungan antara response dan predictors? (Tes null hypothesis,
    hitung F-statistic atau p-value)
    2. Apakah semua predictors penting untuk memprediksi response, atau hanya
    sebagian saja? (Cek Cp, AIC, BIC, atau adjusted R2 pada test data untuk subset
    data tertentu)
    3. Seberapa baik model dapat fit dengan data yang ada? (Cek RSE dan R2
    )
    4. Dengan mengetahui nilai seperangkat predictors, response apa yang dapat
    diprediksi dan seberapa akurat prediksi tersebut? (Cek confidence interval dan
    regression interval)
  o Untuk klasifikasi bisa menggunakan (minimal)C salah satu model (logistic regression,
    LDA, QDA, Naïve Bayes) dan lakukan analisa, misalnya:
    ▪ Apakah ada hubungan antara response dan predictors? (Tes null hypothesis,
    hitung z-statistic atau p-value)
    ▪ Apakah semua predictors penting untuk memprediksi response (fenomena
    confounding), atau hanya sebagian saja?
    ▪ Apakah hasil prediksi model akurat? (evaluasi dengan confusion matrix dan
    atau ROC/AUC)
4. Gunakan resampling method: validation set dan k-fold cross validation. Bandingkan hasil
   keduanya!
  o Cek MSE
  o Bahas Bias-Variance trade off
5. Jelaskan proses pemilihan model linier dan metode untuk memperbaiki performa model
  o Kasus regresi
    ▪ Gunakan salah satu teknik subset selection (forward selection atau best
    selection). Jelaskan model mana yang akhirnya anda pilih.
    ▪ Gunakan ridge regression atau lasso untuk regularization. Jelaskan
    bagaimana proses regularization bisa memperbaiki model yang dibuat!
    o Kasus klasifikasi
    ▪ Gunakan teknik yang relevan untuk memilih model linier yang tepat
