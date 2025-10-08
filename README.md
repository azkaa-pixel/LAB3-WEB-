# LAB3-WEB

Nama : Ghefira Azka Fardani 

NIM : 312410521

Kelas : TI.24.A5

### 1. Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut. 

```html
<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>HTML Lanjutan</title> 
</head> 
<body> 
    <header> 
        <h1>Membuat List</h1> 
    </header> 
</body> 
</html> 
```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%201.jpeg)

#### ```- penjelasan``` :
Kode ini membuat kerangka dasar halaman web dengan judul ```“Membuat List”``` yang akan digunakan untuk menampilkan berbagai jenis daftar.

### 2. Membuat Ordered List 
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut. 

```html
<section id="order-list"> 
    <h2>Ordered List</h2> 
    <ol> 
        <li>Pemrograman Web</li> 
        <li>Sistem Informasi</li> 
        <li>Basis Data 2</li> 
    </ol> 
</section> 
```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%202.jpeg)

#### ```- penjelasan``` :
Menampilkan daftar berurutan menggunakan tag ```<ol>``` dan ```<li>```.
Setiap item akan otomatis diberi nomor sesuai urutannya.

### 3. Membuat Unorderd List 
Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada section unordered-list, seperti berikut. 
```html
<section id="unorder-list"> 
    <h2>Unordered List</h2> 
    <ul type="square"> 
        <li>Jaringan Komputer</li> 
        <li>Struktur Data</li> 
        <li>Algoritma &amp; Pemrograman</li> 
    </ul> 
</section> 
```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%203.jpeg)

#### ```- penjelasan``` :
Menampilkan daftar tanpa nomor, menggunakan simbol kotak (```type="square"```) untuk setiap item.

### 4. Membuat Description List 
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list. 
 
```html
<section id="unorder-list"> 
    <h2>Description List</h2> 
    <dl> 
        <dt>Fakultas Teknik</dt> 
        <dd>Teknik Industri</dd> 
        <dd>Teknik Informatika</dd> 
        <dd>Teknik Lingkungan</dd> 
        <dt>Fakultas Ekonomi dan Bisnis</dt> 
        <dd>Akuntansi</dd> 
        <dd>Manajemen</dd> 
        <dd>Bisnis Digital</dd> 
    </dl> 
</section> 
```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%204.jpeg)

#### ```- penjelasan``` :
Membuat daftar istilah dan penjelasan dengan tag ```<dt>``` untuk judul dan ```<dd>``` untuk deskripsinya.

### 5. Membuat Tabel 
Buat file baru dengan nama lab3_tabel.html seperti berikut. 

```html
<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>HTML Lanjutan</title> 
</head> 
<body> 
    <header> 
        <h1>Membuat Table</h1> 
    </header> 
</body> 
</html> 
```

#### ```- penjelasan``` :
Kode ini berfungsi untuk ```membuat kerangka dasar halaman HTML``` yang akan digunakan dalam latihan pembuatan tabel.
Di dalamnya terdapat elemen ```<header>``` dengan judul ```“Membuat Table”``` sebagai bagian pembuka halaman.
Bagian ```<body>``` masih kosong karena tabel akan ditambahkan pada langkah berikutnya.

##### Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut: 
```html
<table border="1" cellpadding="4" cellspacing="0"> 
    <thead> 
        <tr> 
            <th>No.</th> 
            <th>Fakultas</th> 
            <th>Program Studi</th> 
        </tr> 
    </thead>     <tbody> 
        <tr> 
            <td>1.</td> 
            <td>Teknik</td> 
            <td>Teknik Informatika</td> 
        </tr> 
        <tr> 
            <td>2.</td> 
            <td>Teknik</td> 
            <td>Teknik Industri</td> 
        </tr> 
        <tr> 
            <td>3.</td> 
            <td>Teknik</td> 
            <td>Teknik Lingkungan</td> 
        </tr> 
    </tbody> 
</table> 
```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%205.jpeg)

#### ```- penjelasan``` :
Kode ini digunakan untuk menampilkan tabel data sederhana yang berisi daftar fakultas dan program studi.
Bagian ```<thead>``` berisi judul kolom seperti nomor, fakultas, dan program studi, sedangkan ```<tbody>``` berisi isi data dari tabel tersebut.
Atribut ```border```, ```cellpadding```, dan ```cellspacing``` digunakan untuk menampilkan garis tabel dan mengatur jarak antar sel agar tampilan tabel lebih rapi.

### 6. Mengatur Margin dan Padding 
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan cellspacing pada tag table. 
 
```html
<table border="1" cellpadding="4" cellspacing="0"> 
```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%206.jpeg)


#### ```- penjelasan``` 
Tag ```<table>``` digunakan untuk memulai pembuatan tabel pada halaman web.
Atribut ```border="1"``` menampilkan garis batas tabel, ```cellpadding="4"``` memberi jarak di dalam sel antara teks dan tepi sel,
sedangkan ```cellspacing="0"``` menghapus jarak antar sel agar tabel terlihat lebih rapat dan rapi.

### 7. Menggabungkan Sel Data 
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) 
dan colspan untuk menggabungkan kolom (secara horizontal).  

```html
<table border="1" cellpadding="6" cellspacing="0"> 
    <thead> 
        <tr> 
            <th>No.</th> 
            <th>Fakultas</th> 
            <th>Program Studi</th> 
        </tr> 
    </thead>     <tbody> 
        <tr> 
            <td>1.</td> 
            <td rowspan="3">Teknik</td> 
            <td>Teknik Informatika</td> 
        </tr> 
        <tr> 
            <td>2.</td> 
            <td>Teknik Industri</td> 
        </tr> 
        <tr> 
            <td>3.</td> 
            <td>Teknik Lingkungan</td> 
        </tr> 
    </tbody> 
</table> 
```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%207.jpeg)

#### ```- penjelasan``` :
Kode ini menampilkan tabel dengan penggabungan sel secara vertikal menggunakan atribut ```rowspan="3"```.
Atribut tersebut membuat kolom “Fakultas” hanya menampilkan satu sel bertuliskan “Teknik” yang mencakup tiga baris sekaligus.
Selain itu, atribut ```cellpadding="6"``` memberi jarak di dalam sel agar isi tabel tampak lebih luas dan rapi.

### 8. Membuat Form 
Buat file baru dengan nama lab3_form.html seperti berikut. 
 
```html
<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>HTML Lanjutan</title> 
</head> 
<body> 
    <header> 
        <h1>Membuat Form</h1> 
    </header> 
</body> 
</html> 
```
##### Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut: 
```html
<form action="proses.php" method="post"> 
    <fieldset> 
        <legend>Data Pelanggan</legend> 
        <p> 
            <label for="nama">Nama</label> 
            <input type="text" id="nama" name="nama"> 
        </p> 
        <p> 
            <label for="alamat">Alamat</label> 
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>         </p> 
        <p> 
            <label>Jenis Kelamin</label> 
            <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l">Laki-laki</label>  
            <input id="jk_p" type="radio" name="kelamin" value="P" /><label for="jk_p">Perempuan</label> 
        </p> 
        <p><input type="submit" value="Login"></p> 
    </fieldset> 
</form> 
```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%208.jpeg)

#### ```- penjelasan``` :
Bagian ini berisi ```struktur halaman HTML``` yang digunakan untuk membuat form input data pelanggan.
Form dibuat dengan tag ```<form>``` dan diarahkan ke file ```proses.php``` menggunakan metode ```POST```.
Di dalamnya terdapat elemen ```<fieldset>``` untuk membingkai form dan ```<legend>``` sebagai judulnya.
Form ini memiliki tiga bagian input utama, yaitu kolom ```Nama```, ```Alamat```, dan pilihan ```Jenis Kelamin``` dengan dua opsi radio button (Laki-laki dan Perempuan).
Terakhir, terdapat tombol ```Submit (Login)``` untuk mengirim data yang sudah diisi ke server.

### 9. Menabahkan Style pada Form 
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut. 
 
```html
<style> 
    form p > label {         display: inline-block;         width: 100px; 
    } 
    form input[type="text"], form textarea {         border: 1px solid #197a43; 
    } 
    form input[type="submit"] {         border: 1px solid #197a43;         background-color: #197a43;         color: #ffffff;         font-weight: bold;         padding: 5px 15px; 
    } 
</style> 

```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%209.jpeg)

#### ```- penjelasan``` :
Kode CSS ini digunakan untuk memperindah tampilan form agar terlihat lebih rapi dan menarik.
Bagian ```form p > label``` mengatur posisi label agar sejajar dengan input menggunakan lebar tetap 100 piksel.
Properti pada ```input[type="text"]``` dan ```textarea``` memberi garis tepi berwarna hijau (#197a43).
Sementara itu, tombol ```submit``` diberi warna latar hijau, teks putih, serta padding agar tampil lebih menonjol dan mudah diklik.

# pertanyaan dan tugas   

##### 1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
   
## jawaban : 
tambahkan kode ini pada file ```lab3_form.html```

```html
<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>HTML Lanjutan</title> 
    <style> 
        form p > label {         
            display: inline-block;         
            width: 120px; 
        } 
        form input[type="text"], form textarea, form select {         
            border: 1px solid #197a43; 
        } 
        form input[type="submit"] {         
            border: 1px solid #197a43;         
            background-color: #197a43;         
            color: #ffffff;         
            font-weight: bold;         
            padding: 5px 15px; 
            cursor: pointer;
        } 
    </style> 
</head> 
<body> 
    <header> 
        <h1>Membuat Form</h1> 
    </header> 

    <form action="proses.php" method="post"> 
        <fieldset> 
            <legend>Data Pelanggan</legend> 

            <p> 
                <label for="nama">Nama</label> 
                <input type="text" id="nama" name="nama"> 
            </p> 

            <p> 
                <label for="alamat">Alamat</label> 
                <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>         
            </p> 

            <p> 
                <label>Jenis Kelamin</label> 
                <input id="jk_l" type="radio" name="kelamin" value="L" />
                <label for="jk_l">Laki-laki</label>  
                <input id="jk_p" type="radio" name="kelamin" value="P" />
                <label for="jk_p">Perempuan</label> 
            </p> 

            <!-- Tambahan Dropdown -->
            <p>
                <label for="kota">Pilih Kota</label>
                <select id="kota" name="kota">
                    <option value="jakarta">Jakarta</option>
                    <option value="bandung">Bandung</option>
                    <option value="surabaya">Surabaya</option>
                    <option value="yogyakarta">Yogyakarta</option>
                </select>
            </p>

            <!-- Tambahan Listbox Multiple -->
            <p>
                <label for="hobi">Pilih Hobi</label><br>
                <select id="hobi" name="hobi[]" multiple size="4">
                    <option value="membaca">Membaca</option>
                    <option value="olahraga">Olahraga</option>
                    <option value="menyanyi">Menyanyi</option>
                    <option value="traveling">Traveling</option>
                </select>
            </p>

            <p>
                <input type="submit" value="Login">
            </p> 

        </fieldset> 
    </form> 
</body> 
</html>
```

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB3-WEB-/blob/d5658ac0e3bf7423795ac68552b5b54e094bd923/praktikum%203/ss%2010.jpeg)

#### ```- penjelasan``` :
Kode ini merupakan versi pengembangan dari form sebelumnya dengan tambahan ```dropdown menu``` dan ```listbox multiple selection```.
Bagian CSS digunakan untuk mempercantik tampilan form dengan mengatur jarak, warna border hijau (#197a43), serta tampilan tombol submit agar lebih menarik dan interaktif.

Form ini menampilkan beberapa input, yaitu:

- ```Nama``` dan ```Alamat``` menggunakan elemen teks dan textarea.
- ```Jenis Kelamin``` menggunakan radio button.
- ```Pilih Kota``` menggunakan dropdown (```<select>```) agar pengguna dapat memilih satu kota.
- Pilih Hobi menggunakan listbox dengan atribut ```multiple```, memungkinkan pengguna memilih lebih dari satu hobi sekaligus.

Seluruh data yang diisi akan dikirim ke file ```proses.php``` menggunakan metode ```POST``` saat tombol Login ditekan.



