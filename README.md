# TUGASUAS-NAURA-SALSABILA--244

Tugas data analitik pemogragraman dan pengkodean

![Figure_1](https://github.com/naurasalsabila06/TUGASUAS-NAURA-SALSABILA--244/assets/167267738/6453fa39-a6bd-412a-a6bc-3919421b5946)
Scatterplot ini menunjukan rentang usia dan pendapatan
Histogram of gaji menunjukan grafik gaji dan juga frequency
Box plot of usia menunjukan rentangnya usia
Barplot jenis kelamin menunjukan perbedaan pria dan perempuan

INTERPRETASI 
Lima Baris Pertama Data:
Menampilkan lima baris pertama data untuk mendapatkan gambaran umum tentang isi data:
yaml
Copy code
   usia   gaji jenis_kelamin
0    25  5000         pria
1    30  6000       wanita
2    22  4500         pria
3    28  7000       wanita
4    35  8000         pria
Informasi Umum Tentang Data:
Memberikan informasi umum seperti jumlah entri, kolom, tipe data, dan jumlah nilai yang tidak kosong:
kotlin
Copy code
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 20 entries, 0 to 19
Data columns (total 3 columns):
 #   Column        Non-Null Count  Dtype
---  ------        --------------  -----
 0   usia          20 non-null     int64
 1   gaji          20 non-null     int64
 2   jenis_kelamin 20 non-null     object
dtypes: int64(2), object(1)
memory usage: 608.0+ bytes
•	Jumlah entri: 20
•	Kolom: 3 (usia, gaji, jenis_kelamin)
•	Tidak ada nilai yang hilang dalam data.
Ringkasan Statistik Tentang Data:
Menyajikan statistik deskriptif untuk kolom numerik (usia dan gaji):
yaml
Copy code
            usia         gaji
count  20.000000    20.000000
mean   30.500000  6810.000000
std     6.020797  1616.833734
min    22.000000  4500.000000
25%    25.250000  5750.000000
50%    30.000000  6800.000000
75%    36.750000  8000.000000
max    41.000000  9500.000000
•	Usia rata-rata: 30.5 tahun
•	Gaji rata-rata: 6810
•	Usia minimum: 22 tahun
•	Usia maksimum: 41 tahun
•	Gaji minimum: 4500
•	Gaji maksimum: 9500
Jumlah Data yang Hilang dalam Setiap Kolom:
Semua kolom tidak memiliki data yang hilang:
go
Copy code
usia            0
gaji            0
jenis_kelamin   0
dtype: int64
Jumlah Nilai Unik dalam Setiap Kolom:
Jumlah nilai unik dalam setiap kolom:
go
Copy code
usia            20
gaji            20
jenis_kelamin    2
dtype: int64
•	usia dan gaji masing-masing memiliki 20 nilai unik.
•	jenis_kelamin memiliki 2 nilai unik (pria dan wanita).
Tipe Data dari Setiap Kolom:
Menampilkan tipe data dari setiap kolom:
vbnet
Copy code
usia             int64
gaji             int64
jenis_kelamin   object
dtype: object
Visualisasi:
1.	Scatter Plot: Usia vs. Gaji
o	Memvisualisasikan hubungan antara usia dan gaji.
o	Terlihat bahwa seiring bertambahnya usia, gaji cenderung meningkat.
2.	Histogram: Distribusi Gaji
o	Menampilkan distribusi gaji dari 4500 hingga 9500.
o	Mayoritas gaji berada di rentang 5000 hingga 8000.
3.	Box Plot: Usia
o	Menampilkan distribusi usia.
o	Mayoritas usia berada di antara 25 hingga 37 tahun.
4.	Bar Plot: Jenis Kelamin
o	Menampilkan jumlah data untuk setiap jenis kelamin.
o	Data dibagi sama rata antara pria dan wanita.
Kesimpulan:
•	Data terdiri dari 20 entri dengan kolom usia, gaji, dan jenis_kelamin.
•	Tidak ada nilai yang hilang dalam data

