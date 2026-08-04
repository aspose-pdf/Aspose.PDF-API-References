---
title: "Rectangle"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas mewakili persegi panjang."
type: docs
weight: 1320
url: /id/python-net/aspose.pdf/rectangle/
---

## Rectangle class

Kelas mewakili persegi panjang.

Tipe Rectangle menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Menginisialisasi instance baru dari kelas Rectangle |
## Properti
| Nama | Deskripsi |
| :- | :- |
| lebar | Lebar persegi panjang. |
| tinggi | Tinggi persegi panjang. |
| llx | Koordinat X sudut kiri-bawah. |
| lly | Koordinat Y sudut kiri-bawah. |
| urx | Koordinat X sudut kanan-atas. |
| ury | Koordinat Y sudut kanan-atas. |
| sepele | Menginisialisasi persegi panjang trivial yaitu persegi panjang dengan posisi dan ukuran nol. |
| is_trivial | Memeriksa apakah persegi panjang trivial yaitu memiliki ukuran dan posisi nol. |
| is_empty | Memeriksa apakah persegi panjang kosong. |
| is_point | Memeriksa apakah persegi panjang berupa titik yaitu LLX sama dengan URX dan LLY sama dengan URY. |
| empty | Persegi panjang kosong |
## Metode
| Nama | Deskripsi |
| :- | :- |
| rotate(angle) | Memutar persegi panjang dengan sudut yang ditentukan. |
| rotate(angle) | Memutar persegi panjang dengan sudut yang ditentukan. |
| to_rect() | Mengonversi persegi panjang menjadi instance dari System.Drawing.Rectangle. Posisi dan ukuran floating-point dipotong. |
| from_rect(src) | Menginisialisasi persegi panjang baru dari instance System.Drawing.Rectangle yang diberikan. |
| parse(value) | Mencoba mengurai string dan mengekstrak komponen persegi panjang llx, lly, urx, ury darinya. |
| equals(other) | Memeriksa apakah persegi panjang sama yaitu memiliki posisi dan ukuran yang sama. |
| near_equals(other, delta) | Memeriksa apakah persegi panjang hampir sama yaitu memiliki posisi dan ukuran yang hampir sama (hingga delta). |
| intersect(other_rect) | Berpotongan dengan persegi panjang. |
| join(other_rect) | Menggabungkan persegi panjang. |
| is_intersect(other_rect) | Menentukan apakah persegi panjang ini berpotongan dengan persegi panjang lain. |
| contains(point) | Menentukan apakah titik yang diberikan berada di dalam persegi panjang. |
| center() | Mengembalikan koordinat pusat persegi panjang. |
| clone() | Menggandakan objek Rectangle. |
| to_points() | Mengonversi persegi panjang menjadi array titik ("QuadPoints"). |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

