---
title: Tutorial Membuat Tautan di antara Catatan
author:
  - Abimanyu
description: Semua catatan di sini dibuat dengan aplikasi Obsidian. Obsidian memiliki fitur yang kuat agar setiap pencatat dapat secara digital menautkan catatannya dengan catatan lain dalam jumlah yang tak terhingga, sehingga catatan-catatan tersebut memiliki hubungan satu sama lain yang membentuk jaringan khusus.
permalink:
aliases:
  - membuat link
tags:
  - obsidian
  - tutorial
draft: false
date: 2026-02-08
cover:
---

Semua catatan di sini dibuat dengan aplikasi Obsidian. Obsidian memiliki fitur yang kuat agar setiap pencatat dapat secara digital menautkan catatannya dengan catatan lain dalam jumlah yang tak terhingga, sehingga catatan-catatan tersebut memiliki hubungan satu sama lain yang membentuk jaringan khusus. Kemudian, setiap perubahan yang dibuat oleh pencatat, dalam satu catatan tertentu misalnya, akan secara otomatis diupdate oleh Obsidian, tanpa harus bersusah payah untuk menyunting semua catatannya.

Untuk membuat tautan ini membutuhkan beberapa teknik. ^ffc81a

## tautan ke file catatan

anda dapat menautkan catatan satu dengan catatan lain berdasarkan `file-name` atau judul utama dari catatan lainnya. Misal anda memiliki catatan bernama **Kolonialitas Walter Mignolo** dan anda ingin menghubungkan catatan lain berjudul **Border Thinking**. Maka anda cukup menuliskan:

`[[Border Thinking]]` di bagian manapun dalam catatan **Kolonialitas Walter Mignolo**. ^84e419

## tautan ke judul dalam catatan

### judul dalam satu catatan yang sama

anda dapat menautkan sebuah catatan dengan salah satu judul di dalam catatan tersebut dengan menulis:

`[[#judul-2]]`

## judul dalam catatan yang berbeda

anda juga dapat menautkan catatan dengan judul yang terdapat di catatan lain. Misal menautkan catatan **Kolonialitas Walter Mignolo** dengan judul yang ada di **Border Thinking**:

`[[Border Thinking#judul-3]]`
### sub-judul dalam catatan yang berbeda

untuk menautkan catatan dengan sub-judul yang ada di catatan lain, anda tinggal menuliskan anakan `#` dalam tautan:

`[[Border Thinking#judul-3#subjudul 1]]`

## tautan ke paragraf tertentu dalam catatan

### tautan ke paragraf tertentu di catatan yang sama

di catatan yang sedang anda buka, anda dapat menautkan paragraf satu dengan paragraf lainnya dengan menambahkan `[[^^]]`, kemudian anda tinggal memilih paragraf melalui *pop-up* yang muncul. Misalnya tautan yang berdasarkan paragraf di catatan tutorial ini; [[#^ffc81a]] yang mengacu ke paragraf:

`Untuk membuat tautan ini membutuhkan beberapa teknik.`

### tautan ke paragraf tertentu di catatan yang berbeda

untuk menautkan catatan dengan paragraf tertentu di catatan lainnya lewat penambahan tanda `#^` dalam tautan. Misal, saya ingin menautkan sebuah paragraf dari catatan **Border Thinking** berikut ini:

> Border thinking is an epistemology, an ethic and politics that emerge from the experiences of people taking their destiny in their own hands and not waiting for saviors. Today.

Anda cukup mengetik `#^` dan memilih paragraf tersebut yang muncul di *pop-up* catatan, lalu format tulisan akan berubah dengan sendirinya, di mana paragraf terpilih akan diwakili oleh kode tertentu seperti berikut: `[[Border Thinking#^37066d]]`, dan paragraf yang anda tautkan di catatan akan berubah menjadi:

> Border thinking is an epistemology, an ethic and politics that emerge from the experiences of people taking their destiny in their own hands and not waiting for saviors. Today. ^37066d

## mengubah tampilan teks di tautan

tampilan teks di tautan, tanpa perubahan apa pun, akan berlaku sebagaimana berikut:

- `[[Border Thinking]]` hanya akan menampilkan teks [Border Thinking]()
- `[[Border Thinking#judul-2]]` akan tampil sebagai [Border Thinking#judul-2]()

anda dapat mengubah tampilan teksnya dengan mengetik kode `|` dalam tautan yang anda buat, sebagaimana perubahan berikut:

- `[[Border Thinking|berpikir dari pinggiran]]` akan tampil sebagai [berpikir dari pinggiran]()
- `[[Border Thinking#judul-2|apa yang dimaksud Mignolo]]` akan tampil sebagai [apa yang dimaksud Mignolo]()

juga tautan antar paragraf. misalnya di paragraf di catatan ini

- `[[#^ffc81a|teknik]]` tampilannya menjadi  [[#^ffc81a|teknik]]

