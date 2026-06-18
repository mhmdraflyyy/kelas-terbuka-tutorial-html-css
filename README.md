# 📖 Kelas Terbuka - HTML Learning Notes



Repository ini berisi catatan dan latihan HTML yang telah saya pelajari selama proses belajar web development dari channel youtube Kelas Terbuka - Basic Web Dev Series.



## 📚 Sesi 1 - Heading & Paragraph



### `<h>`



Digunakan untuk membuat heading atau judul pada halaman web. Tersedia dari `<h1>` hingga `<h6>`.



### `<p>`



Digunakan untuk membuat paragraf.



### `<b>`



Digunakan untuk menampilkan teks dengan format tebal (bold).



### `<i>`



Digunakan untuk menampilkan teks dengan format miring (italic).



---



## 📚 Sesi 2 - Underline, Subscript, dan Superscript



### `<u>`



Digunakan untuk memberikan garis bawah pada teks (underline).



### `<sup>`



Digunakan untuk membuat teks superscript (teks kecil di atas).



Contoh:



```html

x<sup>2</sup>

```



### `<sub>`



Digunakan untuk membuat teks subscript (teks kecil di bawah).



Contoh:



```html

H<sub>2</sub>O

```



---



## 📚 Sesi 3 - Line Break dan Horizontal Rule



### `<br>`



Digunakan untuk membuat pindah baris tanpa membuat paragraf baru.



### `<hr>`

Digunakan untuk membuat garis horizontal sebagai pemisah antar bagian konten.

---

## 📚 Sesi 4 - Strong, Emphasis, Quote, dan Blockquote

### `<strong>`

Digunakan untuk memberikan penekanan penting pada teks. Secara tampilan biasanya terlihat tebal, mirip seperti `<b>`, tetapi `<strong>` memiliki makna bahwa teks tersebut penting.

Contoh:

```html
<strong>Belajar HTML itu penting.</strong>
```

### `<em>`

Digunakan untuk memberikan penekanan pada teks. Secara tampilan biasanya terlihat miring, mirip seperti `<i>`, tetapi `<em>` memiliki makna penekanan pada isi teks.

Contoh:

```html
<em>HTML adalah dasar dari pembuatan website.</em>
```

### `<q>`

Digunakan untuk membuat kutipan pendek di dalam satu baris. Browser biasanya akan otomatis menambahkan tanda kutip pada teks.

Contoh:

```html
<p>Guru saya berkata, <q>Belajar coding harus konsisten.</q></p>
```

### `<blockquote>`

Digunakan untuk membuat kutipan panjang atau kutipan yang ditampilkan dalam blok tersendiri.

Contoh:

```html
<blockquote>
  Belajar web development membutuhkan latihan, konsistensi, dan rasa ingin tahu.
</blockquote>
```

---

## 📚 Sesi 5 - Extra Tags

### `<abbr>`

Digunakan untuk menampilkan singkatan atau kepanjangan dari suatu istilah. Biasanya digunakan bersama atribut `title`, sehingga saat kursor diarahkan ke teks, akan muncul penjelasan singkatnya.

Contoh:

```html
<abbr title="HyperText Markup Language">HTML</abbr>
```

### `<cite>`

Digunakan untuk menandai judul karya, seperti buku, artikel, film, lagu, atau sumber referensi.

Contoh:

```html
<p>Saya belajar HTML dari <cite>Kelas Terbuka - Basic Web Dev Series</cite>.</p>
```

### `<dfn>`

Digunakan untuk menandai istilah yang sedang didefinisikan atau dijelaskan.

Contoh:

```html
<p><dfn>HTML</dfn> adalah bahasa markup yang digunakan untuk membuat struktur halaman web.</p>
```

### `<del>`

Digunakan untuk menampilkan teks yang sudah dihapus atau tidak digunakan lagi. Biasanya browser akan menampilkan teks dengan garis coret.

Contoh:

```html
<p>Harga lama: <del>Rp50.000</del></p>
```

---

## 🧪 Sesi Latihan - Text Formatting

Pada sesi latihan ini, saya membuat halaman HTML sederhana berjudul **"The Story of Ucup"**. Latihan ini bertujuan untuk menerapkan beberapa tag HTML yang sudah dipelajari sebelumnya, terutama tag untuk membuat struktur teks, kutipan, format miring, sitasi, dan singkatan.

### 📌 Materi yang diterapkan

Dalam latihan ini, beberapa tag HTML yang digunakan antara lain:

### `<h1>` dan `<h2>`

Digunakan untuk membuat judul utama dan subjudul pada cerita.

Contoh:

```html
<h1>The Story of Ucup</h1>
<h2>Chapter - 1</h2>
```

### `<p>`

Digunakan untuk membuat paragraf cerita.

Contoh:

```html
<p>Ucup telah melewati harinya selama sepuluh hari di kamarnya.</p>
```

### `<i>`

Digunakan untuk membuat teks menjadi miring.

Contoh:

```html
<i>cerita</i>
```

### `<cite>`

Digunakan untuk menandai judul karya atau sumber referensi.

Contoh:

```html
<cite>Lord of The Ring: Twin Tower</cite>
```

### `<q>`

Digunakan untuk membuat kutipan pendek di dalam paragraf.

Contoh:

```html
<q>My precious!!!</q>
```

### `<blockquote>`

Digunakan untuk membuat kutipan panjang atau kutipan yang ditampilkan dalam bentuk blok.

Contoh:

```html
<blockquote>
  <i>Sekali teman, tetap teman.</i>
</blockquote>
```

### `<abbr>`

Digunakan untuk menampilkan singkatan dengan keterangan tambahan menggunakan atribut `title`.

Contoh:

```html
<abbr title="Karbon Dioksida">CO</abbr><sub>2</sub>
```

### `<sub>`

Digunakan untuk membuat teks kecil di bawah, biasanya digunakan pada rumus kimia.

Contoh:

```html
CO<sub>2</sub>
O<sub>2</sub>
```

### `<hr>`

Digunakan untuk membuat garis horizontal sebagai pemisah antar bagian cerita.

Contoh:

```html
<hr>
```

---

# Kesimpulan Latihan

Dari latihan ini, saya memahami bahwa HTML tidak hanya digunakan untuk menampilkan teks biasa, tetapi juga dapat digunakan untuk memberikan struktur dan makna pada teks. Tag seperti `<cite>`, `<q>`, `<blockquote>`, `<abbr>`, dan `<sub>` membantu membuat isi halaman menjadi lebih jelas, rapi, dan mudah dipahami.

---

## 📚 Sesi 7 - List

Pada sesi ini saya mempelajari beberapa jenis list dalam HTML, yaitu ordered list, unordered list, list item, dan definition list.

### `<ol>`

Digunakan untuk membuat daftar yang memiliki urutan atau nomor. Biasanya digunakan ketika urutan data itu penting.

Contoh:

```html
<ol>
  <li>Pasta 1 bungkus</li>
  <li>Daging cincang 1 kg</li>
  <li>Tomat 0.25 kg</li>
</ol>
```

### `<ul>`

Digunakan untuk membuat daftar yang tidak memiliki urutan. Biasanya ditampilkan dengan tanda bullet atau titik.

Contoh:

```html
<ul>
  <li>Pasta 1 bungkus</li>
  <li>Daging cincang 1 kg</li>
  <li>Tomat 0.25 kg</li>
</ul>
```

### `<li>`

Digunakan untuk membuat item atau isi dari sebuah list. Tag ini digunakan di dalam `<ol>` atau `<ul>`.

Contoh:

```html
<ul>
  <li>Bawang merah 2 siung</li>
  <li>Bawang putih 2 siung</li>
</ul>
```

### Nested List

Nested list adalah list yang berada di dalam list lain. Biasanya digunakan untuk membuat daftar bertingkat.

Contoh:

```html
<ul>
  <li>Bumbu dapur
    <ol>
      <li>Garam</li>
      <li>Gula</li>
    </ol>
  </li>
</ul>
```

### `<dl>`

Digunakan untuk membuat definition list, yaitu daftar yang berisi istilah dan penjelasannya.

Contoh:

```html
<dl>
  <dt>Siapkan Pasta</dt>
  <dd>Rebus spaghetti hingga matang, lalu angkat dan tiriskan.</dd>
</dl>
```

### `<dt>`

Digunakan untuk menuliskan istilah atau judul yang akan dijelaskan dalam definition list.

Contoh:

```html
<dt>Membuat saus spaghetti</dt>
```

### `<dd>`

Digunakan untuk menuliskan penjelasan dari istilah yang ada pada `<dt>`.

Contoh:

```html
<dd>Panaskan wajan, lalu tumis bawang putih dan bawang merah hingga harum.</dd>
```

---

## 🎯 Progress Belajar

* [x] Heading (`<h1>` - `<h6>`)
* [x] Paragraph (`<p>`)
* [x] Bold (`<b>`)
* [x] Italic (`<i>`)
* [x] Underline (`<u>`)
* [x] Superscript (`<sup>`)
* [x] Subscript (`<sub>`)
* [x] Line Break (`<br>`)
* [x] Horizontal Rule (`<hr>`)
* [x] Strong (`<strong>`)
* [x] Emphasis (`<em>`)
* [x] Inline Quote (`<q>`)
* [x] Blockquote (`<blockquote>`)
* [x] Abbreviation (`<abbr>`)
* [x] Citation (`<cite>`)
* [x] Definition (`<dfn>`)
* [x] Deleted Text (`<del>`)
* [x] Ordered List (`<ol>`)
* [x] Unordered List (`<ul>`)
* [x] List Item (`<li>`)
* [x] Definition List (`<dl>`)
* [x] Definition Term (`<dt>`)
* [x] Definition Description (`<dd>`)


🚀 Repository ini akan terus diperbarui seiring bertambahnya materi HTML yang saya pelajari.



