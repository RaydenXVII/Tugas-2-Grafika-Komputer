# Tugas-2-Grafika-Komputer
Tugas Exercise Chapter 3 Grafika Komputer </br>
(Exercise 3.1, 3.2, 3.3) </br>

Nama Randy Deniz Manzarasi </br>
NIM : 1201220445

<b>Exercise 3.1</b> </br>
![Exercise 3 1](https://github.com/RaydenXVII/Tugas-2-Grafika-Komputer/assets/74905981/e44297e5-0ccb-48d8-92e7-b86eb5c06264) </br>

<b>Exercise 3.2</b> </br>
Berikut adalah langkah-langkah menggambar garis dengan algoritma struktural:
1. Langkah awal :</br>
•	Tentukan dua titik ujung garis: (x0, y0) dan (x1, y1).</br>
•	Hitung nilai dx = x1 - x0 dan dy = y1 - y0.</br>
•	Hitung kemiringan garis (m) = dy/dx.</br>
•	Hitung nilai b dari persamaan garis: y = m * x + b.</br>
2. Menggambar Garis</br>
•	Dimulai dari titik awal (x0, y0).</br>
•	Lakukan langkah-langkah berikut hingga mencapai titik akhir (x1, y1):</br>
•	Hitung nilai decision variable (D) menggunakan midpoint algorithm.</br>
•	Pilih pixel berikutnya yang akan digambar berdasarkan nilai D:</br>
•	Jika D <= 0, pilih piksel di sebelah kanan.</br>
•	Jika D > 0, pilih piksel di atas dan sebelah kanan.</br>
•	Perbarui posisi piksel dan nilai D.</br>
3. Optimasi</br>
Gunakan reduksi alternatif untuk pixel yang akan digambar.Hindari floating point arithmetic dan gunakan operasi bilangan bulat untuk komputasi yang lebih efisien.</br></br>
Kesimpulan</br>
Algoritma struktural dapat digunakan untuk menggambar garis dengan efisien. Algoritma ini menggunakan persamaan garis dan midpoint algorithm untuk menentukan pixel berikutnya yang akan digambar. Dengan menggunakan optimasi yang tepat, algoritma ini dapat diimplementasikan dengan operasi bilangan bulat saja, sehingga lebih efisien dan mudah untuk diimplementasikan. </br>

<b>Exercise 3.3</b> </br>
![Screenshot hasil Exercise 3 3](https://github.com/RaydenXVII/Tugas-2-Grafika-Komputer/assets/74905981/09e68a68-8894-4c73-aac6-f85938f85b02)




