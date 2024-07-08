![Uber and Lyft Dataset Boston MA](https://github.com/DarlyP/Uber-and-Lyft-Dataset-Boston-MA/blob/main/Notebook/UberLyft.jpeg)

# Uber and Lyft Dataset Boston MA

---


## Data Source

Kaggle: [[Uber and Lyft Dataset Boston, MA](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma).

---

## Introduction

Sebagai perusahaan penyedia layanan taksi seperti Lyft atau Uber, memahami faktor-faktor yang mempengaruhi harga layanan sangat penting untuk meningkatkan strategi penetapan harga dan daya saing di pasar. Dengan menggunakan analisis Linear Regression pada dataset dari Kaggle, perusahaan dapat mengidentifikasi bagaimana parameter-parameter tertentu, seperti waktu pemesanan, lokasi penjemputan, dan kondisi lalu lintas, mempengaruhi harga taksi. Wawasan ini memungkinkan perusahaan untuk mengoptimalkan harga, menentukan strategi promosi yang efektif, meningkatkan kualitas layanan, memberikan estimasi harga yang akurat kepada pelanggan, dan mengelola armada taksi dengan lebih efisien.

---

## Kesimpulan

Kesimpulan yang diperoleh dari analisis data ini adalah sebagai berikut:

- Model regresi linear berhasil dibentuk menggunakan pipeline dengan *hyperparameter fit intercept*. Parameter terbaik yang ditemukan adalah ketika *fit intercept* bernilai *False*.

- RMSE yang dihasilkan dari model ini bernilai rendah, yaitu sekitar 3, sedangkan pada R² diperoleh nilai 89,5%. Pada data train dan test ditemukan nilai yang tidak jauh berbeda, yang menandakan tidak ada *overfitting*.

- Nilai QQ plot yang divisualisasikan menunjukkan bahwa data tidak terdistribusi normal, yang ditandai dengan kurva yang menyimpang ke atas.

- Nilai Durbin Watson yang diperoleh mendekati 2, yang berarti tidak ada *Auto Correlation*.

- Visualisasi *homoscedasticity* dilakukan dan hasilnya menunjukkan bahwa data hasil pemodelan mengindikasikan adanya *heteroskedastisitas*.

- Dari sudut pandang bisnis perusahaan, menyimpulkan bahwa cuaca tidak berpengaruh signifikan terhadap tarif taksi dari Uber dan Lyft berarti perusahaan dapat fokus pada faktor-faktor yang lebih mempengaruhi penetapan harga, seperti jarak tempuh, lokasi penjemputan, tujuan, jenis kendaraan, dan nama layanan. Hal ini memungkinkan perusahaan untuk mengoptimalkan strategi penetapan harga berdasarkan analisis data yang lebih akurat terhadap faktor-faktor ini. Dengan memperhatikan parameter-parameter ini, perusahaan dapat mengambil langkah-langkah yang lebih tepat untuk menarik pelanggan dengan harga yang kompetitif, serta meningkatkan kepuasan pelanggan dengan menawarkan layanan yang sesuai dengan preferensi mereka.

---

**Disclaimer**: Notebook ini dibuat semata-mata untuk tujuan pembelajaran dan eksplorasi. Tidak ada maksud untuk menyinggung atau merugikan pihak mana pun. Segala konten dan analisis yang disajikan didasarkan pada data publik yang tersedia secara online. Saya melakukan proses ini untuk meningkatkan pemahaman tentang teknik dan metodologi analisis data, serta untuk mengasah keterampilan dalam mengimplementasikan algoritma dan model yang relevan dalam konteks pembelajaran data science.

Dalam melakukan analisis ini, saya berusaha menjaga objektivitas dan profesionalitas dalam menginterpretasikan data yang ada. Segala kesimpulan atau rekomendasi yang disampaikan merupakan hasil dari analisis pribadi dan tidak bermaksud sebagai saran profesional dalam kapasitas tertentu. Saya berharap informasi yang diperoleh dari notebook ini dapat bermanfaat bagi siapa pun yang membacanya untuk kepentingan belajar dan pengembangan keterampilan analisis data.
