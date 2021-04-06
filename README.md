# Dasar CSS

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/css.png)

  CSS (Cascading Style Sheets) adalah kode yang kamu gunakan untuk memberikan gaya pada halaman web kamu. Dasar-dasar CSS akan menjelaskan apa sajakah yang kamu butuhkan untuk memulai. Kami akan menjawab pertanyaan-pertanyaan seperti: Bagaimana saya dapat membuat teks saya menjadi berwarna hitam atau merah? Bagaimana saya dapat membuat konten saya tampil sedemikian rupa pada layar? Bagaimana saya dapat mendekor halaman web saya dengan latar belakang gambar atau warna-warna?


# Langkah-langkah Praktikum
# 1. Membuat dokumen HTML
Buatlah dokumen HTML seperti berikut :

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/1.JPG)

Selanjutnya buka pada browser untuk melihat hasilnya

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/1,1.JPG)

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/2.JPG)

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/ubah%202%2C2.jpg)

# 2. Mendeklarasikan CSS Internal
Kemudian tambahkan deklarasi CSS internal seperti berikut :

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/3.JPG)

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/ubah%203%2C3.jpg)

# 3. Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag < p > seperti berikut.

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/4.JPG)

Simpan kembali dan refresh

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/4,4.JPG)

# 4. Membuat CSS Eksternal
Buatlah file dengan nama style_eksternal.css

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/filebaru.JPG)

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/5.JPG)

Kemudian Tambhkan tag < link > untuk merujuk file css yg sudah di buat pada bagian < head >

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/6.JPG)

Selanjutnya refresh kembali browser dan lihat perubahannya

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/6,6.JPG)

# 5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kode berikut :

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/7.JPG)

Kemudian simpan kembali dan refresh browser untuk melihat perubahnnya.

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/7,7.JPG)

# Pertanyaan Dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/5.JPG)

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/7.JPG)

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/7,7.JPG)

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

Biasanya H1 hanya digunakan satu kali dalam sebuah halaman web, yaitu sebagai judul utama (judul besar), Sedangkan Intro di gunakan untuk memisahkan perintah dalam satu kesatuan
( h1 )sebagai Selector penanda bagian mana yang akan kita rubah style dengan CSS, menambahkan id untuk bagian tag sehingga kita dapat mengidentifikasi nanti ketika styling.Kita menggunakan tag header untuk membungkus pengantar h1 elemen. Selain menggambarkan keseluruhan dokumen, header-tag juga harus digunakan untuk menjelaskan masing-masing bagian.

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/7,7.JPG)

![imag](https://github.com/fdlhrauf/Lab2Web/blob/main/me.JPG)

Karena CSS eksternal digunakan untuk menggabungkan CSS ke website dengan menggabungkan file, dengan cara tersebut, perubahan apapun yang dibuat pada file CSS akan tampil pada websit.e secara keseluruhan

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( < p id = "paragraf - 1" class = "text - paragraf" > )

Semuanya akan tampak. Namun Class mampu memanggil sekaligus atau berkali-kali pada satu halaman, sedangkan ID tidak bisa di panggil lebih dari satu.
Semua akan jadi 1 class dan dapat memanggil sekaligus atau berkali-kali sedangkan ID tidak bisa memanggil satu persatu


# Nama : Siti Fadillah Rauf
# Kelas : TI.19.A1
# NIM : 311910206
