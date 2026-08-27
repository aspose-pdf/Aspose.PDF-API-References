---
title: "Matrix"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas ini mewakili matriks transformasi."
type: docs
weight: 900
url: /id/python-net/aspose.pdf/matrix/
---

## Matrix class

Kelas ini mewakili matriks transformasi.

Tipe Matrix menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Matrix() | Constructor<br/>            membuat matriks standar 1 ke 1:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Menginisialisasi instance baru dari kelas Matrix |
| Matrix(matrix_array) | Menginisialisasi instance baru dari kelas Matrix |
| Matrix(matrix) | Menginisialisasi instance baru dari kelas Matrix |
| Matrix(a, b, c, d, e, f) | Menginisialisasi instance baru dari kelas Matrix |
## Properti
| Nama | Deskripsi |
| :- | :- |
| data | Mendapatkan data Matrix sebagai array. |
| a | Anggota A dari matriks transformasi. |
| b | Anggota B dari matriks transformasi. |
| c | Anggota C dari matriks transformasi. |
| d | Anggota D dari matriks transformasi. |
| e | Anggota E dari matriks transformasi. |
| f | Anggota F dari matriks transformasi. |
| elemen | Elemen-elemen dari matriks. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| rotation(alpha) | Membuat matriks untuk sudut rotasi yang diberikan. |
| rotation(rotation) | Membuat matriks untuk sudut rotasi yang diberikan. |
| transform(p) | Mengubah titik menggunakan matriks ini. |
| transform(rect) | Mengubah persegi panjang.<br/>            Jika sudut bukan kelipatan 90 derajat maka persegi panjang pembatas dikembalikan. |
| skew(alpha, beta) | Membuat matriks untuk sudut rotasi yang diberikan. |
| get_angle(rotation) | Menerjemahkan rotasi menjadi sudut (derajat) |
| multiply(other) | Mengalikan matriks dengan matriks lain. |
| add(other) | Menambahkan matriks ke matriks lain. |
| reverse() | Menghitung matriks terbalik. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

