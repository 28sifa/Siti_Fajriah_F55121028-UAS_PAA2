# Siti Fajriah
# F55121028

1. Bubble Sort & Insertion Sort: Bubble Sort dan Insertion Sort adalah dua algoritma pengurutan sederhana dengan kompleksitas waktu O(n^2) yang cocok untuk daftar yang kecil atau hampir terurut.
Bubble Sort:
a. Worst Case: Dalam Bubble Sort, Worst Case terjadi ketika daftar yang akan diurutkan berada dalam urutan terbalik. Pada setiap iterasi, Bubble Sort akan membandingkan dan menukar pasangan elemen yang tidak terurut. Dalam Worst Case, setiap elemen akan membutuhkan perbandingan dan pertukaran hingga mencapai posisi yang benar. Sehingga, kompleksitas waktu Bubble Sort dalam Worst Case adalah O(n^2), di mana n adalah jumlah elemen dalam daftar.
b. Best Case: Best Case Bubble Sort terjadi ketika daftar sudah dalam urutan terurut dengan benar. Dalam Best Case, Bubble Sort akan melintasi daftar sekali untuk memeriksa apakah ada pertukaran yang dilakukan. Karena daftar sudah terurut, tidak ada pertukaran yang diperlukan.
Sehingga, kompleksitas waktu Bubble Sort dalam Best Case adalah O(n).
c. Average Case: Dalam Average Case, kompleksitas waktu Bubble Sort adalah O(n^2).
Pada rata-rata, Bubble Sort membutuhkan sekitar n/2 iterasi untuk mengurutkan daftar dengan benar. Namun, karena kompleksitas waktu O(n^2) mengacu pada jumlah total perbandingan dan pertukaran yang dilakukan, Bubble Sort masih memiliki kompleksitas waktu O(n^2) pada kasus rata-rata.
Insertion Sort:
a. Worst Case: Dalam Insertion Sort, Worst Case terjadi ketika daftar yang akan diurutkan berada dalam urutan terbalik. Pada setiap iterasi, Insertion Sort memasukkan elemen dari bagian yang belum terurut ke posisi yang benar dalam bagian terurut. Dalam Worst Case, setiap elemen dari bagian yang belum terurut harus dimasukkan ke posisi yang benar dengan melintasi seluruh bagian terurut. Sehingga, kompleksitas waktu Insertion Sort dalam Worst Case adalah O(n^2), di mana n adalah jumlah elemen dalam daftar.
b. Best Case: Best Case Insertion Sort terjadi ketika daftar sudah dalam urutan terurut dengan benar. Dalam Best Case, Insertion Sort hanya perlu melintasi daftar sekali untuk memeriksa apakah ada penyisipan yang dilakukan. Karena daftar sudah terurut, tidak ada penyisipan yang diperlukan. Sehingga, kompleksitas waktu Insertion Sort dalam Best Case adalah O(n).
c. Average Case: Dalam Average Case, kompleksitas waktu Insertion Sort adalah O(n^2).
Pada rata-rata, Insertion Sort membutuhkan sekitar n/2 iterasi untuk mengurutkan daftar dengan benar. Namun, karena kompleksitas waktu O(n^2) mengacu pada jumlah total penyisipan yang dilakukan, Insertion Sort masih memiliki kompleksitas waktu O(n^2) pada kasus rata-rata.
   
2.  Analisis Algoritma TSP (Traveling Salesman Problem) dan Dijkstra dalam Worst Case, Best Case, dan Average Case:
Algoritma TSP (Traveling Salesman Problem):
a. Worst Case: Dalam Worst Case, Algoritma TSP memerlukan kompleksitas waktu eksponensial, yang dikenal sebagai NP-hard. Pada kasus terburuk, ketika jumlah kota yang harus dikunjungi sangat besar, jumlah kemungkinan permutasi rute yang harus diperiksa juga meningkat secara eksponensial. Oleh karena itu, algoritma yang mencoba secara eksplisit menguji setiap kemungkinan permutasi akan memiliki kompleksitas waktu yang sangat tinggi.
b. Best Case: Tidak ada perbedaan dalam hal Best Case dalam Algoritma TSP. Karena TSP merupakan masalah yang kompleks, tidak ada solusi yang menghasilkan waktu yang lebih baik dari yang lain dalam skenario terbaik.
c. Average Case: Dalam Average Case, kompleksitas waktu Algoritma TSP juga sangat tinggi, karena memerlukan pemeriksaan sejumlah besar kemungkinan rute. Namun, ada beberapa algoritma yang dikembangkan untuk mendekati solusi optimal dengan kompleksitas waktu yang lebih baik daripada yang diketahui secara eksplisit.
Algoritma Dijkstra:
a. Worst Case: Dalam Worst Case, kompleksitas waktu Algoritma Dijkstra adalah O((V + E) log V), di mana V adalah jumlah simpul (nodes) dan E adalah jumlah tepi (edges) dalam grafik. Dalam kasus terburuk, ketika grafik memiliki banyak simpul dan tepi yang kompleks, algoritma ini dapat menghabiskan waktu yang signifikan untuk menemukan jalur terpendek antara dua simpul.
b. Best Case: Dalam Best Case, kompleksitas waktu Algoritma Dijkstra juga O((V + E) log V). Karena algoritma ini harus melintasi setiap simpul dan tepi dalam grafik untuk mencari jalur terpendek, kompleksitas waktu tidak berbeda dalam skenario terbaik.
c. Average Case: Dalam Average Case, kompleksitas waktu Algoritma Dijkstra adalah O((V + E) log V). Seperti dalam Worst Case, algoritma ini memerlukan waktu yang sebanding dengan jumlah simpul dan tepi dalam grafik untuk menemukan jalur terpendek.
