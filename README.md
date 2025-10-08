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
![foto]()

#### ```- penjelasan``` :

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
![foto]()

#### ```- penjelasan``` :

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
![foto]()

#### ```- penjelasan``` :

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
![foto]()

#### ```- penjelasan``` :

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
![foto]()

#### ```- penjelasan``` :

### 6. Mengatur Margin dan Padding 
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan cellspacing pada tag table. 
 
```html
<table border="1" cellpadding="4" cellspacing="0"> 
```

#### ```- hasil```
![foto]()


#### ```- penjelasan``` 

### 7. Menggabungkan Sel Data 
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) 
dan colspan untuk menggabungkan kolom (secara horizontal).  

```html

```

#### ```- hasil```
![foto]()

#### ```- penjelasan``` :

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

```

#### ```- hasil```
![foto]()

#### ```- penjelasan``` :

### 9. Menabahkan Style pada Form 
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut. 
 
```html

```

#### ```- hasil```
![foto]()

#### ```- penjelasan``` :

# pertanyaan dan tugas   

1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
   
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
![foto]()

#### ```- penjelasan``` :



