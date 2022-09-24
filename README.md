# Laporan Resmi Praktikum Modul 1 Jaringan Komputer 2022

## Anggota Kelompok C10:

| Nama                   | NRP        |
| ---------------------- | ---------- |
| Pierra Muhammad Shobr  | 5025201062 |
| Barhan Akmal Falahudin | 5025201008 |
| Arief Badrus Sholeh    | 5025201228 |

## Soal 1

> Sebutkan web server yang digunakan pada "monta.if.its.ac.id"!

## Soal 2

> Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?

## Soal 3

> Filter sehingga wireshark hanya menampilkan paket yang menuju port 80!

## Soal 4

> Filter sehingga wireshark hanya mengambil paket yang berasal dari port 21!

## Soal 5

> Filter sehingga wireshark hanya mengambil paket yang berasal dari port 443!

## Soal 6

> Filter sehingga wireshark hanya menampilkan paket yang menuju ke lipi.go.id !

a. Ping ke `lipi.go.id` menggunakan command prompt untuk mendapatkan alamat IP.

![6.a](/screenshot/6.a.png)

Dapat kita lihat bahwa alamat IP dari `lipi.go.id` adalah `203.160.1128.158`

b. Lakukan display filter wireshark menggunakan sintaks `ip.dst <alamat ip>` dengan alamat IP yang sudah didapat

```
ip.dst 203.160.128.158
```

![6.b](/screenshot/6.b.png)

Dapat kita lihat pada kolom Destination bahwa wireshark menampilkan semua paket yang menuju satu alamat IP yaitu `203.160.128.158`

## Soal 7

> Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

a. Melihat alamat IP kita menggunakan `ipconfig` pada command prompt.

![7.a](/screenshot/7.a.png)

Dapat kita lihat bahwa alamat IP dari komputer saya adalah `192.168.43.39` (_pada bagian IPv4 Address_)

b. Lakukan capture filter wireshark menggunakan sintaks `src host <alamat IP>` dengan alamat IP yang sudah didapat.

```
src host 192.168.43.39
```

![7.b](/screenshot/7.b.png)

Dapat kita lihat pada kolom Source bahwa wireshark menampilkan semua paket yang berasal dari alamat IP `192.168.43.39`

## Soal 8

> Telusuri aliran paket dalam file .pcap yang diberikan, cari informasi berguna berupa percakapan antara dua mahasiswa terkait tindakan kecurangan pada kegiatan praktikum. Percakapan tersebut dilaporkan menggunakan protokol jaringan dengan tingkat keandalan yang tinggi dalam pertukaran datanya sehingga kalian perlu menerapkan filter dengan protokol yang tersebut.

## Soal 9

> Terdapat laporan adanya pertukaran file yang dilakukan oleh kedua mahasiswa dalam percakapan yang diperoleh, carilah file yang dimaksud! Untuk memudahkan laporan kepada atasan, beri nama file yang ditemukan dengan format [nama_kelompok].des3 dan simpan output file dengan nama “flag.txt”.

## Soal 10

> Temukan password rahasia (flag) dari organisasi bawah tanah yang disebutkan di atas!

## Kendala

Berikut adalah kendala yang kami alami dalam mengerjakan praktikum modul 1 ini:

-
-
