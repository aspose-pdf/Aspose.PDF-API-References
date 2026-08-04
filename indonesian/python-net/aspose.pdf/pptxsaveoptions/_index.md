---
title: "PptxSaveOptions"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Opsi penyimpanan untuk ekspor ke format SVG"
type: docs
weight: 1290
url: /id/python-net/aspose.pdf/pptxsaveoptions/
---

## PptxSaveOptions class

Opsi penyimpanan untuk ekspor ke format SVG

Tipe PptxSaveOptions menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PptxSaveOptions() | Menginisialisasi sebuah instance baru dari kelas PptxSaveOptions |
## Properti
| Nama | Deskripsi |
| :- | :- |
| warning_handler | Callback untuk menangani peringatan apa pun yang dihasilkan. <br/>            WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. <br/>            Continue adalah aksi default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus dihentikan. |
| save_format | Format penyimpanan data. |
| close_response | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam response. |
| extract_ocr_sublayer_only | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks <br/>            untuk dokumen PDF dengan sublayer OCR. |
| try_merge_adjacent_same_background_images | Kadang-kadang PDF berisi gambar latar belakang (halaman atau sel tabel)<br/>              yang dibangun dari beberapa gambar latar belakang berulang yang ditempatkan berdekatan.<br/>              Dalam kasus seperti itu, renderer format target (mis. MsWord untuk format DOCS) terkadang menghasilkan<br/>              batasan visual antara bagian-bagian gambar latar belakang,<br/>              karena teknik mereka dalam menghaluskan tepi gambar (anti-aliasing) berbeda dari Acrobat Reader.<br/>               Jika tampaknya dokumen yang diekspor mengandung batasan visual semacam itu antara <br/>              bagian-bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan <br/>              efek yang tidak diinginkan. <br/>                PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi,<br/>              jadi, harap gunakan opsi ini hanya ketika memang diperlukan. |
| slides_as_images | Jika diatur ke true maka semua konten dikenali sebagai gambar (satu per halaman) |
| image_resolution | Mendapatkan atau mengatur resolusi gambar (dpi). Default adalah 192 dpi. |
| separate_images | Jika diatur ke true maka gambar dipisahkan dari semua grafik lainnya |
| optimize_text_boxes | Mengaktifkan atau menonaktifkan pengenalan kolom teks |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

