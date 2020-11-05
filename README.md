# HTML Tutorials
Pada github ini kita akan belajar untuk memahami dasar-dasar HTML.

## Memulai HTML
Untuk memulai HTML kita dapat menggunakan format terbaru yaitu HTML5. Code tersebut terdiri atas head dan body. head berfokus pada pengaturan utama dari web yang akan dibangun seperti judul dan lainnya. body berfungsi mengatur tampilan web atau interface web.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
## Menampilkan Teks Judul Default
Teks judul pada HTML dapat ditampilkan menggunakan tag h1,h2,h3,h4,h5,h6. Keenam tipe teks yang akan ditampilkan telah diatur secara default mulai yang terbesar dari h1 sampai yang terkecil adalah h6. berikut adalah contoh teksnya:
```
<h1>My CSS Website</h1>
<h2>My CSS Website</h2>
<h3>My CSS Website</h3>
<h4>My CSS Website</h4>
<h5>My CSS Website</h5>
<h6>My CSS Website</h6>
```
## Menampilkan Teks Paragraf
Menampilkan teks paragraf dapat dilakukan dengan menggunakan tag p di HTML.
```
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
```
## Menampilkan Teks link
Teks link berfungsi untuk menghubungkan page yang satu dengan page yang lainnya, dalam HTML dapat menggunakan tag a.
```
<a class="button" href="#">Read More</a>
```
## Menampilkan Gambar
Untuk menampilkan gambar di HTML dapat menggunakan tag img. isinya adalah src yaitu source dari gambar yang akan ditampilkan, width dan height untuk mengatur tinggi dan lebar serta alt untuk memberikan bentuk teks atau caption ketika gambar tidak loading karena jaringan atau kendala lainnya.
```
 <img src="img.jpg" width="500" height="600" alt=""> 
```
## Membuat List
Ada dua tipe list yang dapat dibuat yaitu tipe ul dan tipe li. tipe ul hanya akan mencetak lingkaran penanda list. untuk menjadikan nomor yang berurutan maka gunakan ol atau order list.
```
<!--List-->
        <ul>
            <li>List 1</li>
            <li>List 2</li>
            <li>List 3</li>
        </ul>

        <ol>
            <li>List 1</li>
            <li>List 2</li>
            <li>List 3</li>
        </ol>
```
## Membuat Tabel
Tabel dalam HTML sendiri terdiri atas head dan body. head adalah yang menjadi keterangan isi dari body. body adalah nilai yang ada dalam tabel atau isi tabel tersebut.
```
 <!--Table-->
        <table>
        <thead>
            <tr>
                <th>Nama</th>
                <th>Email</th>
                <th>Usia</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Devin</td>
                <td>dev@insomnia.com</td>
                <td>22</td>
            </tr>
            <tr>
                <td>Purnawan</td>
                <td>Pur@insomnia.com</td>
                <td>23</td>
            </tr>
            <tr>
                <td>Syah</td>
                <td>Syah@insomnia.com</td>
                <td>32</td>
            </tr>
        </tbody>
        </table>
```
## Membuat Form di HTML
Form adalah salah satu hal yang penting karena banyak digunakan dalam membangun kerangka website. berikut adalah implementasi form dalam HTML.
```
<!--form-->
        <form action="process.php" method="POST">
            <div>
                <label> First Name </label>
                <input type="text" name="firsName" placeholder="Masukkan Nama Awal">
            </div>
            <br>
            <div>
                <label> Last Name </label>
                <input type="text" name="lastName">
            </div>
            <br>
            <div>
                <label> Email </label>
                <input type="email" name="email">
            </div>
            <br>
            <div>
                <label> Gender </label>
                <select name="gender">
                    <option value="1">Man</option>
                    <option value="2">Woman</option>
                    <option value="0">Other</option>
                </select>
            </div>
            <br>
            <div>
                <label> Pesan </label>
                <textarea name="pesan" cols="20" rows="5"></textarea>
            </div>
            <br>
            <div>
                <label> Age </label>
                <input type="number" name="age" value="20">
            </div>
            <br>
            <div>
                <label> Birthday </label>
                <input type="date" name="birthday">
            </div>
            <br>
            <div>
                <input type="submit" name="Submit" value="Submit" >
            </div>
        </form>

```
## Button dalam HTML
Button atau tombol dapat dibuat dengan tag button yang ada dalam HTML.
```
<!--button-->
        <button>Klik Sekarang</button>
```

Sebenarnya masih banyak lagi tag yang ada di HTML, semua yang berada di atas hanya sebagiannya aja. teman-teman dapat mencarinya di browser, sangat banyak referensi HTML yang tersedia.
