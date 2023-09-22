# Praktikum Modul 1 Jarkom

## Anggota Kelompok

| NRP        | Nama                 |
| ---        | ---                  |
| 5025211058 | Nadya Zuhria Amana   |
| 5025211127 | Nadif Mustafa        |

<br>

## Daftar Isi

- [Praktikum Modul 1 Jarkom](#praktikum-modul-1-jarkom)
  - [Anggota Kelompok](#anggota-kelompok)
  - [Daftar Isi](#daftar-isi)
  - [Soal 1](#soal-1)
  - [Soal 2](#soal-2)

## Soal 1

User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.

- Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut?
- Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut?
- Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?
- Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

**Jawaban:**

Karena aktivitas yang dilakukan adalah mengunggah suatu file, maka cari packet dengan yang mengandung kata "STOR".

*Gambar filter*

Didapatkan sequence number dan acknowledgement number dari packet tersebut:

*Gambar number*

Dari informasi packet di atas, didapatkan bahwa nama file yang dikirim adalah "c75-GrabThePisher.zip", sehinggga kita perlu mencari packet response yang mengandung kata "GrabThePisher".

*Gambar filter*

Didapatkan sequence number dan acknowledgement number dari packet tersebut:

*Gambar number*

*Gambar submission*

## Soal 2

Sebutkan web server yang digunakan pada portal praktikum Jaringan Komputer!

**Jawaban:**

Lakukan filtering menggunakan ip address portal praktikum jarkom.

*Gambar filter*