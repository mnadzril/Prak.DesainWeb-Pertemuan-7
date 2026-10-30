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

## Desktop
<img width="433" height="389" alt="image" src="https://github.com/user-attachments/assets/32a6928d-15e3-4980-8638-ee9741fa6861" />

## Mobile
<img width="186" height="349" alt="Screenshot 2026-10-30 145514" src="https://github.com/user-attachments/assets/5610bce4-00c9-460a-a929-40d192ca0b68" />



### Contoh 2 - Form Pendaftaran Mahasiswa

## Desktop 
<img width="291" height="405" alt="image" src="https://github.com/user-attachments/assets/19090789-3356-454f-ac1e-d602eb4afb58" />

## Mobile 
<img width="1179" height="3702" alt="127 0 0 1_2222_contoh%202_index html(iPhone 16)" src="https://github.com/user-attachments/assets/a10c530c-c373-4491-8013-658f90f5804b" />

## Ringkasan

Pada praktikum ini saya membuat dua form HTML: form pencarian mahasiswa (contoh 1) dan form pendaftaran mahasiswa (contoh 2). Setiap field disusun dalam `div` form-group berisi label dan input, dengan atribut `for` sama dengan `id` input. Setiap kontrol diberi atribut `name` agar datanya punya key saat dikirim ke backend. Contoh 1 memakai input text, number, date, serta tombol submit, reset, dan button biasa. Contoh 2 menambahkan email, password, select, dan textarea.

Masalah yang saya temui adalah memilih method yang tepat. Solusinya, contoh 1 memakai `get` karena untuk pencarian, sedangkan contoh 2 memakai `post` karena mengirim data pendaftaran dan password. Saya juga menambahkan `required`, `min`, dan `max` untuk validasi dasar di browser, namun validasi server tetap diperlukan.
