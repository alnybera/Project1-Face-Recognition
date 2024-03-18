# Project1-Face-Recognition (Gender Classification using InterceptionV2)
Project 1 
## Introduction & Overview
Deteksi gender wajah melibatkan penggunaan algoritma-algoritma canggih dan teknik-teknik pembelajaran mesin untuk menganalisis fitur-fitur wajah dan mengklasifikasikan individu berdasarkan jenis kelamin mereka. Teknologi ini memiliki potensi besar dalam berbagai domain, termasuk namun tidak terbatas pada penegakan hukum, analisis ritel, dan hiburan.
Data yang digunakan adalah data Data CelebA (Celebrities Attributes Dataset) yang merupakan salah satu dataset yang populer dalam bidang pengenalan wajah dan atribut wajah. Dataset ini memiliki lebih dari 200 ribu gambar wajah yang diambil dari selebriti publik yang beragam dan diberi label dengan berbagai atribut, termasuk gender, umur, warna rambut, dan lainnya. Secara khusus untuk deteksi gender wajah, data CelebA menyediakan label gender untuk setiap gambar dalam dataset. Label tersebut biasanya berupa nilai biner yang menunjukkan apakah wajah pada gambar adalah laki-laki atau perempuan. Data ini digunakan untuk melatih model pembelajaran mesin dalam mengenali pola-pola yang berkaitan dengan perbedaan gender dalam wajah.
![image](https://github.com/alnybera/Project1-Face-Recognition/assets/163568585/03ac289c-6cb6-4212-91f8-f20a9e0e5f09)
Project Face recognition kali ini menggunakan arsitektur Interception ResnetV2
Interception ResNet-V2 merupakan sebuah modifikasi dari arsitektur ResNet-V2 yang ditambahkan dengan komponen "interception" untuk meningkatkan kemampuan pemahaman fitur dalam jaringan. Konsep "interception" memungkinkan jaringan untuk menggabungkan informasi dari berbagai tingkat resolusi atau kedalaman, sehingga memperkaya representasi fitur yang diekstraksi. Model improvement yang digunakan adalah Hyperparameter Tunning - Hyperband. Hasil model yang diuji menggunakan Conffusion matrix menghasilkan nilai 0.59
##Requirements
Python 3.9
Tensorflow dan Keras
Scikit-Learn
Numpy
Pandas
Matplotlib
Seaborn
##Contact
Jika Anda memiliki saran, penyempurnaan, atau perbaikan, jangan ragu untuk menghubungi saya di bernadeta.alnybera@gmail.com
