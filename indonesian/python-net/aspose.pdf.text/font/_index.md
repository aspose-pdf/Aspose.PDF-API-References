---
title: "Font"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili objek font."
type: docs
weight: 100
url: /id/python-net/aspose.pdf.text/font/
---

## Font class

Mewakili objek font.

Tipe Font menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| font_name | Mendapatkan nama font dari objek [Font](/pdf/python-net/aspose.pdf.text/font/). |
| decoded_font_name | Kadang-kadang font PDF (biasanya font Cina/Jepang/Korea) dapat memiliki nama font yang khusus.<br/>Nama ini adalah nilai properti font PDF "BaseFont" dan terkadang properti ini<br/>dapat direpresentasikan dalam bentuk heksadesimal. Jika nama ini dibaca langsung, ia dapat ditampilkan<br/>dalam bentuk yang tidak dapat dibaca. Untuk mendapatkan bentuk yang dapat dibaca, diperlukan untuk mendekode nama font dengan<br/>aturan khusus untuk font tersebut. <br/>Properti ini mengembalikan nama font yang telah didekode, jadi gunakan untuk kasus ketika Anda menemui <br/>[font_name](/pdf/python-net/aspose.pdf.text/font/) yang tidak dapat dibaca.<br/>Jika properti [font_name](/pdf/python-net/aspose.pdf.text/font/) memiliki bentuk yang dapat dibaca, properti ini akan sama dengan <br/>[font_name](/pdf/python-net/aspose.pdf.text/font/), sehingga Anda dapat menggunakan properti ini untuk semua kasus ketika Anda perlu<br/>mendapatkan nama font dalam bentuk yang dapat dibaca. |
| base_font | Mendapatkan nilai BaseFont dari objek font PDF. Juga dikenal sebagai nama PostScript dari font. |
| is_embedded | Mendapatkan atau mengatur nilai yang menunjukkan apakah font disematkan.<br/>Font yang berbasis IFont akan secara otomatis menjadi subset dan disematkan |
| is_subset | Mendapatkan atau mengatur nilai yang menunjukkan apakah font merupakan subset.<br/>Font yang berbasis IFont akan secara otomatis menjadi subset dan disematkan |
| is_accessible | Mendapatkan indikasi apakah font ada (terpasang) di sistem. |
| font_options | Properti berguna untuk menyesuaikan perilaku Font |
## Metode
| Nama | Deskripsi |
| :- | :- |
| get_last_font_embedding_error() | Tujuan metode ini - mengembalikan deskripsi kesalahan jika upaya<br/>menyematkan font gagal. Jika tidak ada kasus kesalahan, ia mengembalikan string kosong. |
| save(stream) | Menyimpan font ke dalam stream.<br/>Perhatikan bahwa font disimpan dalam format TTF menengah yang dimaksudkan hanya untuk digunakan dalam salinan dokumen asli yang telah dikonversi.<br/>File font tidak dimaksudkan untuk digunakan di luar konteks dokumen asli. |
| measure_string(str, font_size) | Mengukur string. |

### Lihat Juga

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

