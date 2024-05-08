#### Nama : Adrian Aryaputra Hamzah
#### NPM : 2206811474
#### Kelas : ADPRO - B
#### ASDOS : GEN

# 2.1. Original code of broadcast chat
![alt text](img1.png)
![alt text](img2.png)
![alt text](img3.png)
![alt text](img4.png)

Untuk melakukan run pada server dapat dengan `cargo run --bin server` sedangkan untuk run client `cargo run --bin client`

Berdasarkan output yang dihasilkan, pada awalnya, setiap client yang run akan langsung terhubung kepada server; ketika kita mengirimkan pesan dari satu klien, maka setiap klien dan server akan menerima pesan tersebut.

Setiapkali klien memasukan pesan melalui baris perintah, pesan tersebut akan langsung dikirim ke server; server akan menerukan ke seluruh klien yang terhubung.


# 2.2: Modifying port
![alt text](img5.png)
![alt text](img6.png)
![alt text](img7.png)
![alt text](img8.png)
Gambar pertama menunjukkan server dan klien dengan port yang berbeda (server di port 2000, klien di port 8080), yang menyebabkan ketidakcocokan sehingga koneksi antara keduanya gagal.

<hr>

![alt text](img9.png)
![alt text](img10.png)
![alt text](img11.png)
![alt text](img12.png)
Gambar kedua memperlihatkan kondisi ketika klien dan server menggunakan port yang sama, yaitu 8080. Dengan kesesuaian ini, koneksi antara klien dan server berhasil. Ini menegaskan bahwa jika port klien diubah, maka port server juga harus disesuaikan karena komunikasi antara server dan klien memerlukan keselarasan dua arah.
