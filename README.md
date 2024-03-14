# Soal remedial

## Mengclone repository dan membuat file baru

Yang paling pertama kamu harus lakukan adalah mengclone repository ini ke lokal kamu. Lalu buat satu file bernama `Bio.md` dan isi file tersebut dengan tulisan berikut:

```
# Biodataku

Halo, nama saya adalah xxx

Saya merupakan seorang xxx di xxx

Saya memiliki hobi xxx

Saya memiliki keahlian di bidang xxx

Saya memiliki pengalaman kerja di bidang xxx
```

Lalu tambahkan file tersebut ke dalam staging area dan commit dengan pesan "Menambahkan file Bio.md".

Selanjutnya buat branch baru dengan nama `bio-{nama kamu}`. Lalu push branch tersebut ke repository.

Jika kamu sudah selesai, silahkan buat pull request ke branch `main`.

## Mengedit file Bio.md

Untuk sekarang kita akan membuat branch baru **dari branch `bio-{nama kamu}`**. Buat branch baru dengan nama `edit-bio-{nama kamu}`. Lalu pindah ke branch tersebut.

Setelah kamu pindah ke branch tersebut, buka file `Bio.md` dan ubah tulisan `xxx` menjadi biodata kamu sendiri. Lalu tambahkan file tersebut ke dalam staging area dan commit dengan pesan "Mengedit file Bio.md".

## Simulasi konflik

Sekarang kembali ke branch `bio-{nama kamu}`. Lalu buat branch baru dengan nama `edit-bio-Adit`. Lalu pindah ke branch tersebut.

Setelah kamu pindah ke branch tersebut, buka file `Bio.md` dan ubah tulisan `xxx` dengan tulisan berikut:

```
# Biodataku

Halo, nama saya adalah Adit

Saya merupakan seorang Petani di sawah

Saya memiliki hobi berkebun

Saya memiliki keahlian di bidang pertanian

Saya memiliki pengalaman kerja di bidang pertanian
```

Setelah itu tambahkan file tersebut ke dalam staging area dan commit dengan pesan "Mengedit file Bio.md".

## Menggabungkan branch

Setelah kamu selesai membuat branch `edit-bio-Adit`, kembali ke branch `bio-{nama kamu}`. Lalu merge branch `edit-bio-Adit` ke branch `bio-{nama kamu}`, setelah itu merge branch `bio-{nama kamu}` ke branch `main`. Kamu akan menemui konflik ketika melakukan merge, selesaikan konflik tersebut dengan memilih biodata kamu sendiri. Setelah itu push branch `bio-{nama kamu}` ke repository.
