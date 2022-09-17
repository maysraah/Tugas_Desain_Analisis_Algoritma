Nama : Maysarah<br>
NIM : 2110131120006<br><br>

<h1 align="center">Penjelasan Sederhana Tentang Time Complexity dan Big-O Notation</h1><br>

<p align="justify">Setiap <i>programmer</i> yang baik akan menggunakan cara yang paling efektif dan efisien dalam menyelesaikan suatu permasalahan. Dan untuk bisa melakukan hal tersebut, <b>kita harus bisa meminimalisir kompleksitas dari algoritma yang kita gunakan.</b></p>

<p align="justify">Kompleksitas suatu algoritma dibagi menjadi 2, yaitu <i>Time Complexity</i> dan <i>Space Complexity.</i></p>

<p align="justify"><b>Time Complexity</b> adalah seberapa lama waktu yang diperlukan untuk menjalankan suatu algoritma. Sedangkan <b>Space Complexity</b> adalah seberapa besar memori yang kita gunakan untuk menjalankan suatu algoritma.</p><br><br>

### **Algortima**

<p align="justify">Sederhananya, algoritma adalah serangkaian proses yang dilakukan secara berurutan untuk menyelesaikan sebuah permasalahan. Algoritma bisa bermacam-macam tergantung kepada siapa yang membuat algoritma tersebut.</p>

<p align="justify"><b>Time Complexity Analysis</b> adalah _suatu cara sederhana untuk mengetahui berapa lama waktu yang dibutuhkan untuk menjalankan suatu algoritma dengan input tertentu (n)._ Biasanya lebih dikenal dengan sebutan <b>Big-O Notation.</b></p><br><br>

### **Big-O Notation**

<p align="justify"><b>Big-O Notation</b> adalah cara untuk mengkonversi keseluruhan langkah-langkah suatu algoritma kedalam bentuk <b>Aljabar</b>, yaitu dengan menghiraukan konstanta yang lebih kecil dan koefisien yang tidak berdampak besar terhadap keseluruhan kompleksitas permasalahan yang diselesaikan oleh algoritma tersebut.</p>

Mari kita liat contoh dibawah ini:

<p align="center"><img src="img/img1.jpeg"></p>

<p align="justify">Sederhananya, semua contoh yang ada diatas mengatakan bahwa <i><b>“kita hanya akan melihat faktor yang memiliki dampak paling besar terhadap nilai yang dihasilkan oleh algoritma tersebut”.</b></i></p>

Terdapat beberapa macam **time complexity**, diantaranya:

**O(1) — Constant Time**

<p align="justify"><b>Constant Time</b> artinya banyaknya input yang diberikan kepada sebuah algoritma, tidak akan mempengaruhi waktu proses (runtime) dari algoritma tersebut.</p>

<p align="center"><img src="img/img2.jpeg"></p>

<p align="justify">Contoh diatas, terdapat sebuah fungsi untuk mengambil elemen pertama dari sebuah input array. Kita bisa melihat bahwa berapapun jumlah array yang diberikan kepada fungsi tersebut, dia akan selalu melakukan 1 hal, yaitu mengambil elemen pertama. Itu artinya <b>jumlah input yang diberikan tidak mempengaruhi waktu proses <i>(runtime)</i> dari algoritma tersebut.</b>

<p align="center"><img src="img/img3.jpeg"></p><br><br>

**O(log n) — Logarithmic Time**

<p align="justify"><b>Logarithmic Time</b> artinya ketika kita memberikan input sebesar <i>n</i> terhadap sebuah fungsi, jumlah tahapan yang dilakukan oleh fungsi tersebut berkurang berdasarkan suatu faktor. Salah satu contohnya adalah algoritma <b>Binary Search.</b></p>

<p align="justify"><b>Binary Search</b> adalah algoritma yang kita gunakan dalam mencari posisi nilai dari suatu array dengan cara ‘mengeliminasi’ setengah dari array input untuk mempercepat proses pencarian.</p>

<p align="center"><img src="img/img4.jpeg"></p>

<p align="center"><img src="img/img5.jpeg"></p><br><br>

**O(n) — Linear Time**

<p align="justify">Linear Time adalah ketika <i>runtime</i> dari fungsi kita berbanding lurus dengan jumlah input yang diberikan.</p>

<p align="center"><img src="img/img6.jpeg"></p><br>

<p align="justify">Kita bisa melihat bahwa <b>semakin banyak jumlah input yang diberikan, maka waktu proses/runtime dari fungsi tersebut akan semakin besar.</b></p>

<p align="center"><img src="img/img7.jpeg"></p><br><br>

**O(n²) — Quadratic Time**

<p align="justify"><b>Quadratic Time</b> adalah ketika runtime dari fungsi kita adalah sebesar 

    n^2

dimana _n_ adalah jumlah input dari fungsi tersebut. Hal tersebut bisa terjadi karena kita menjalankan **fungsi linear didalam fungsi linear** (n*n).</p>

<p align="center"><img src="img/img8.jpeg"></p>

<p align="center"><img src="img/img9.jpeg"></p>

<p align="center"><img src="img/img10.jpeg"></p><br><br>

**O(2^n) — Exponential Time**

<p align="justify"><b>Exponential Time</b> biasanya digunakan dalam situasi dimana kita tidak terlalu tahu terhadap permasalahan yang dihadapi, sehingga mengharuskan kita mencoba setiap <b>kombinasi</b> dan <b>permutasi</b> dari semua kemungkinan.</p>

<p align="center"><img src="img/img11.jpeg"></p><br><br>

**Kesimpulan**

<p align="justify">Sebagai <i>programmer</i>, kita sering kali dihadapkan dengan adanya beberapa solusi untuk sebuah permasalahan dan kita dibingungkan dengan pertanyaan <b><i>“mana solusi yang lebih efisien?”.</i></b></p>

<p align="justify">Dengan memahami <b>Big-O Notation</b>, kita akan lebih mudah dalam melihat mana algoritma yang lebih efisien yang bisa kita gunakan untuk menyelesaikan permasalahan yang sedang dihadapi.</p>













