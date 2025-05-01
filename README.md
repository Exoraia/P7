# Pertemuan 7 REST API Development

<details>
<summary>

### Latihan 3 </summary>
Latihan 3 berisikan pembangunan sistem CRUD menggunakan Java dengan konsep REST API. Jika kita menjalan main class dari file itu maka kode ini akan berjalan, namun tidak memiliki tampilan apa apa, maka dari itu kita perlu menggunakan Postman untuk menguji coba API tersebut
</details>

<details>
<summary>

### Latihan 4 </summary>
Latihan 4 merupakan hasil dari pengujian API menggunakan Postman, berikut merupakan pengujian dari masing masing fungsi yakni:

#### GET All Books:
![GET All Books](screenshot/lat4-get-all.png)

#### GET Book ID = 1
![GET Book by ID](screenshot/lat4-get-1.png)

#### POST Book
![POST Book](screenshot/lat4-post.png)

#### PUT Book ID = 1
![PUT Book](screenshot/lat4-put-1.png)

#### DELETE Book ID = 1
![DELETE Book](screenshot/lat4-delete-1.png)
</details>

<details>
<summary>

### Latihan 5 </summary>
Latihan 5 merupakan kelanjutan dari latihan 3 dan 4 dimana kali ini kita dapat melihat interface secara langsung, jadi apa yang kita ubah pada REST API menggunakan Postman akan dapat dilihat di tampilan ini. Akan tetapi, kita tidak dapat menambah, menghapus, mengubah atau melakukan apapun pada tampilan ini dan perlu menjalankan ulang programnya untuk melihat perubahan yang telah dilakukan

#### Tampilan tanpa data
![GUI Awal](screenshot/lat5-gui-before.png)

#### Data ditambah di dalam Postman
![Data di Postman](screenshot/lat5-get-all-postman.png)

#### Tampilan setelah menambahkan data dengan Postman
![GUI setelah Postman](screenshot/lat5-gui-after.png)

</details>

<details>
<summary>

### Latihan 6 </summary>
Pada Latihan 6, telah ditambahkan fitur baru yaitu refresh, maka dari itu kita tidak perlu menjalankan ulang jika ada terjadi perubahan dalam API. Hal ini dimungkinkan oleh function loadDataFromAPI(). Function itulah yang memungkinkan kita untuk me-refresh data API jika ada perubahan

#### Tampilan sebelum di refresh
![Sebelum di refresh](screenshot/lat6-gui-pre-refresh.png)

#### Tampilan setelah di refresh
![Setelah di refresh](screenshot/lat6-gui-post-refresh.png)

</details>

<details>
<summary>

### Latihan 7 </summary>
Pada Latihan 7, kita akan coba membuat antarmuka untuk menambahkan data menggunakan API yang telah dibuat di LibraryApp.java nya. Kodenya dapat dilihat di src/main/java/com/pbo2/latihan7

Pada Latihan 7, ditambahkan fitur baru yaitu Add Book dimana kita dapat menambahkan data yang ada di Rest API menggunakan tampilan yang ada tanpa menggunakan Postman, selain itu ada 2 kolom baru untuk menambah Judul Buku dan Author

#### Sebelum Menambah Data
![Latihan 7 - Sebelum](screenshot/lat7-gui-before.png)

#### Proses Penambahan Data
![Latihan 7 - Menambahkan Data](screenshot/lat7-gui-adding.png)

#### Hasil Penambahan
![Latihan 7 - Setelah](screenshot/lat7-gui-after.png)

</details>

<details>
<summary>

### Tugas </summary>
Pada bagian Tugas, ditambahkan 2 fitur terakhir yakni Delete dan Edit, dengan ditambahkannya 2 fungsi ini kita dapat melakukan GET, POST, PUT, dan DELETE, melalui tampilan tanpa menggunakan Postman 

#### Menambahkan Data
##### Tampilan Form Input  
![Tugas - Adding](screenshot/tugas-adding.png)

##### Hasil Output setelah Submit  
![Tugas - Adding Output](screenshot/tugas-adding-output.png)

#### Mengedit Data
##### Tampilan Sebelum Edit  
![Tugas - Editing](screenshot/tugas-editing.png)

##### Tampilan Setelah Edit  
![Tugas - Editing After](screenshot/tugas-editing-after.png)

#### Menghapus Data
##### Konfirmasi Penghapusan  
![Tugas - Deleting Confirmation](screenshot/tugas-deleting-confirmation.png)

##### Notifikasi Berhasil Dihapus  
![Tugas - Deleting Success](screenshot/tugas-deleting-success.png)

##### Tampilan Setelah Data Dihapus  
![Tugas - Deleting After](screenshot/tugas-deleting-after.png)