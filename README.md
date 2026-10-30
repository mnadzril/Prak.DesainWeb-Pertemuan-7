# Praktikum Desain Web - HTML Form Dasar: Input & Pengiriman Data

**Nama:** Muhammad Nadzril Ilham Kusuma **NPM:** [4525210084]

## Struktur Folder

```
pertemuan-07/
├── contoh-1/
│   ├── index.html
│   ├── css/style.css
│   └── dokumentasi/   (desktop.png, mobile.png)
└── contoh-2/
    ├── index.html
    ├── css/style.css
    └── dokumentasi/   (desktop.png, mobile.png)
```

## Hasil Tampilan

### Contoh 1 - Form Pencarian Mahasiswa

| Desktop | Mobile |
| :-----: | :----: |
| ![Desktop](contoh-1/dokumentasi/desktop.png) | ![Mobile](contoh-1/dokumentasi/mobile.png) |

### Contoh 2 - Form Pendaftaran Mahasiswa

| Desktop | Mobile |
| :-----: | :----: |
| ![Desktop](contoh-2/dokumentasi/desktop.png) | ![Mobile](contoh-2/dokumentasi/mobile.png) |

## Ringkasan

Pada praktikum ini saya membuat dua form HTML: form pencarian mahasiswa (contoh 1) dan form pendaftaran mahasiswa (contoh 2). Setiap field disusun dalam `div` form-group berisi label dan input, dengan atribut `for` sama dengan `id` input. Setiap kontrol diberi atribut `name` agar datanya punya key saat dikirim ke backend. Contoh 1 memakai input text, number, date, serta tombol submit, reset, dan button biasa. Contoh 2 menambahkan email, password, select, dan textarea.

Masalah yang saya temui adalah memilih method yang tepat. Solusinya, contoh 1 memakai `get` karena untuk pencarian, sedangkan contoh 2 memakai `post` karena mengirim data pendaftaran dan password. Saya juga menambahkan `required`, `min`, dan `max` untuk validasi dasar di browser, namun validasi server tetap diperlukan.
