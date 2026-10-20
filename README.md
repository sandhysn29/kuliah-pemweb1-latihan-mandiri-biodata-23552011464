# Kuliah Pemrograman Web I — Latihan Mandiri: Website Biodata Mahasiswa

Repository ini berisi tugas **Latihan Mandiri** mata kuliah **Pemrograman Web I**: membuat website biodata mahasiswa menggunakan HTML, CSS, dan JavaScript dasar.

## Biodata Mahasiswa

| Keterangan | Detail |
| --- | --- |
| Nama | Sandhy Safarudin Nurdiansyah |
| NIM | 23552011464 |
| Program Studi | S1 Teknik Informatika |
| Universitas | Universitas Teknologi Bandung |
| Mata Kuliah | Pemrograman Web I |
| Jadwal Kelas | Jumat, 19:40–21:40 WIB |

## Tentang Tugas

Berdasarkan materi *Dasar Pengembangan Web* (bagian Latihan Mandiri), tugas ini meminta mahasiswa membuat website biodata pribadi yang menampilkan:

- Nama, NIM, program studi, dan alamat
- Foto dan daftar hobi
- Tabel riwayat pendidikan
- Halaman yang didesain menggunakan CSS
- Tombol yang menampilkan pesan (interaksi JavaScript)

**Tantangan tambahan:** tampilan harus tetap rapi pada layar ponsel dengan menerapkan *media query* (desain responsif).

## Kriteria Teknis

- Struktur halaman menggunakan HTML: elemen `head` dan `body`, heading, paragraf, tautan, gambar dengan atribut `alt`, daftar, tabel, dan form sederhana
- Tampilan diatur dengan **CSS eksternal** yang dihubungkan melalui `<link rel="stylesheet">`, menerapkan *box model* (margin, padding, border) dan layout sederhana dengan flexbox
- Interaksi dasar menggunakan **JavaScript eksternal**: mengambil elemen dengan `getElementById`, merespons klik dengan `addEventListener`, dan mengubah teks dengan `textContent`
- Responsif dengan `@media (max-width: 600px)`

> Kode ditulis setara level materi dasar Pemrograman Web I — tanpa framework atau library tambahan.

## Struktur Proyek

```
.
├── index.html        # Halaman utama biodata
├── css/
│   └── style.css     # Desain dan layout halaman
├── js/
│   └── script.js     # Interaksi tombol dan pesan
└── images/           # Foto dan aset gambar
```

Struktur di atas mengikuti contoh pada materi perkuliahan. File website ditambahkan seiring pengerjaan tugas.

## Teknologi

- HTML5
- CSS3
- JavaScript (dasar / vanilla)
