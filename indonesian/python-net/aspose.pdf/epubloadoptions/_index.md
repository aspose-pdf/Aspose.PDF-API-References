---
title: "EpubLoadOptions"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Berisi opsi untuk memuat/mengimpor file EPUB ke dalam dokumen pdf."
type: docs
weight: 310
url: /id/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

Berisi opsi untuk memuat/mengimpor file EPUB ke dalam dokumen pdf.

Tipe EpubLoadOptions menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| EpubLoadOptions() | Membuat opsi muat default untuk mengonversi file EPUB menjadi dokumen pdf. <br/>            Ukuran halaman pdf default - A4 300dpi 2480 X 3508. |
| EpubLoadOptions(page_size) | Menginisialisasi instance baru dari kelas EpubLoadOptions |
## Properti
| Nama | Deskripsi |
| :- | :- |
| warning_handler | Callback untuk menangani peringatan apa pun yang dihasilkan. <br/>            WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. <br/>            Continue adalah aksi default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus dihentikan. |
| load_format | Mewakili format file yang dijelaskan oleh [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| page_size | Mendapatkan atau mengatur ukuran halaman output untuk impor. |
| margin | Mendapatkan referensi pada objek yang mewakili informasi margin. |
| margins_area_usage_mode | Mewakili mode penggunaan area margin - mendefinisikan perlakuan <br/>              terhadap instruksi (jika ada) CSS dari dokumen yang diimpor<br/>              yang terkait dengan penggunaan margin. |
| page_size_adjustment_mode | PERHATIAN! Fitur ini telah diimplementasikan tetapi belum dipublikasikan ke API publik karena masalah blokir pada <br/>              OSHARED layer yang terdeteksi pada dokumen contoh.<br/>              <br/>             <br/>              Mewakili mode penggunaan ukuran halaman selama konversi.<br/>             Format (seperti HTML, EPUB, dll), biasanya memiliki desain mengambang, sehingga memungkinkan menyesuaikan ukuran halaman yang diperlukan.<br/>             Namun terkadang konten memiliki posisi horizontal atau ukuran yang ditentukan yang <br/>             tidak memungkinkan menempatkan konten ke dalam ukuran halaman yang diperlukan.<br/>               Dalam kasus tersebut kita dapat menentukan apa yang harus dilakukan (misalnya ketika ukuran konten tidak cocok <br/>             dengan ukuran halaman awal yang diperlukan dari dokumen PDF hasil). |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

