# Tugas Kecil 2 IF2211 Strategi Algoritma - Convex Hull
## Deskripsi program
Program berupa file Jupyter Notebook ini merupakan program untuk menyelesaikan permasalahan convex hull. Cara kerja program ini adalah dengan menggunakan pendekatan divide and conquer. Singkatnya, kumpulan titik yang akan dicari convex hull-nya dibagi secara terus menerus menjadi dua bagian, yaitu atas dan bawah garis, hingga tidak ada titik di atas garis.

## Persyaratan penggunaan
Terdapat beberapa library yang dibutuhkan untuk menjalankan convex hull ini, yaitu
- Jupyter Notebook: Untuk membuka file notebook (.ipynb) berisi kode sumber yang terdapat pada folder src.
- NumPy: Agar dapat menjalakan library Pandas. 
- Pandas: Untuk memanipulasi dataset yang dijadikan DataFrame sehingga pencarian data terkecil, terbesar, dan sebagainya dapat diperhitungkan dengan method yang tersedia pada Pandas.
- Matplotlib: Sebagai visualisasi convex hull.
- Scikit-Learn: Sebagai penyedia dataset.

Untuk melakukan instalasi keempat modul tersebut, dapat digunakan perintah di bawah ini pada command line. Pastikan Python dan Pip telah ter-install pada sistem yang digunakan. Pada pembuatan tugas ini, versi yang digunakan adalah Python 3.9.5 dan pip 21.1.3.

    pip install jupyter
    pip install numpy
    pip install pandas
    pip install matplotlib
    pip install scikit-learn


## Cara Penggunaan Program
Untuk penggunaan program, lakukan clone terlebih dahulu pada repository ini dengan membuka command line atau terminal lalu mengeksekusi perintah berikut
    
    git clone https://github.com/VanillaMacchiato/tucil2-stima_13520153.git
    cd tucil2-stima_13520153/src/
    jupyter notebook

Setelah itu, Jupyter Notebook akan terbuka pada brower. Pilih file ConvexHull.py dan klik menu `Kernel -> Restart & Run All`. Visualisasi myConvexHull ditampilkan pada bagian terbawah dari notebook tersebut. Kemudian, cell baru dapat ditambahkan agar  myConvexHull dapat digunakan pada data-data lainnya.

## Batasan
Pada umumnya, dataset dengan nilai float atau int dapat digunakan sebagai input untuk myConvexHull. Namun, terdapat beberapa batasan agar tidak terjadi kesalahan pada penggunaan myConvexHull untuk visualisasi. Batasan tersebut adalah.

1. Input ke myConvexHull berupa objek DataFrame yang tidak berisi nilai null.
2. DataFrame harus mempunyai >= 2 kolom.
3. Nama kolom absis dan kolom ordinat disertakan saat membuat objek myConvexHull. Jika tidak disertakan, kolom 0 dan 1 akan digunakan sebagai absis dan ordinat.
4. Output dari myConvexHull, yaitu atribut simplices, adalah list of list of integer dengan list of integer tersebut berisi indeks dari pasangan titik yang membentuk garis pada convex hull.

## Identitas Pembuat
NIM: 13520153

Nama: Vito Ghifari