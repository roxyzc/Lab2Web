### TUGAS Lab2Web

## HASIL

### Gambar 1

<img src="./img/img1.png" style="margin: auto; width:200px;"><br><br>

### Gambar 2

<img src="./img/img2.png" style="margin: auto; width:200px;"><br><br>

### Gambar 3

<img src="./img/img3.png" style="margin: auto; width:200px;"><br><br>

## PENJELASAN

<p>Code di atas merupakan contoh sederhana dari form input HTML yang menggunakan bahasa pemrograman PHP. Halaman ini memperlihatkan form input sederhana dengan tiga elemen yaitu Nama, Tanggal dan Pekerjaan, dan juga sebuah tombol "Kirim".

Form ini meminta pengguna untuk memasukkan nama, tanggal lahir, dan pekerjaan, dan setelah tombol "Kirim" ditekan, data akan dikirim ke server untuk diproses. Setelah itu, informasi tersebut akan ditampilkan kembali kepada pengguna sebagai "Hasil" dari pengisian form.

Pada bagian PHP, terdapat kondisi if yang mengecek apakah tombol "Kirim" telah ditekan dengan menggunakan fungsi isset($\_POST["submit"]). Jika iya, maka informasi yang dimasukkan ke dalam form akan ditampilkan kembali menggunakan echo.

Pada bagian hasil, informasi yang akan ditampilkan adalah nama, tanggal lahir, pekerjaan, dan umur yang dihitung dengan menggunakan fungsi date_diff(). Selain itu, juga akan ditampilkan informasi gaji berdasarkan jenis pekerjaan yang dipilih oleh pengguna. Jika pengguna memilih "Mahasiswa", maka gaji akan ditampilkan sebagai "RP. 0", jika pengguna memilih "Karyawan", maka gaji akan ditampilkan sebagai "RP. 4000000", dan jika pengguna memilih "Tidak ada", maka gaji akan ditampilkan sebagai "RP. 0".

</p>
