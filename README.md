# K-Fold with SLP
K-Fold Cross Validation using SLP Implementation on Pure Python

# Pendahuluan
Single Layer Perceptron (SLP) merupakan salah satu teknik jaringan saraf tiruan yang paling sederhana. Jaringan ini hanya memiliki lapisan input dan lapisan output. Jaringan ini termasuk supervised learning, artinya metode pembelajarannya dilakukan melalui contoh-contoh. Jaringan akan ditraining dengan sekumpulan contoh-contoh yang diketahui input dan outputnya. Selama proses belajar tersebut jaringan akan menyesuaikan nilai bobotnya agar menghasilkan output yang diinginkan.

K-fold Cross Validation adalah salah satu metode Cross Validation yang populer dengan melipat data sebanyak K dan mengulangi (men-iterasi) experimennya sebanyak K juga. Misalnya sekelompok data berjumlah 150 dan ditentukan k=5, berarti 150 data dibagi menjadi 5 blok yang berisi masing-masing 30 data. Kemudian, perlu ditentukan mana yang training data dan mana yang test data, sehingga perlu memilih blok yang akan digunakan sebagai data validasi sehingga blok-blok lainnya dapat digunakan untuk training. Blok yang dipilih untuk menjadi data validasi selalu berbeda-beda pada setiap layer sampai semua blok data terpilih sebagai data validasi.

# Langkah Implementasi
1.	Tentukan input file berisi dataset (dalam percobaan ini menggunakan file .csv) 
2.	Bagi file menjadi beberapa nilai k atau layer(fold) yang telah ditentukan
3.	Tentukan nilai theta awal, dapat menggunakan random number 
4.	Lakukan pemisahan atau pemilihan blok training dan validasi pada setiap layer 
5.	Lakukan training pada dan validasi pada blok-blok yang telah ditentukan 
6.	Hitung rata-rata error rate dan accuracy setiap layer. 
7.	Hitung rata-rate error rate dan accuracy per epoc, yang merupakan rata-rata error rate dan accuracy dari semua layer

# Input
The given input example is a dataset in .csv

# Output
The output produced will be plotted graph

