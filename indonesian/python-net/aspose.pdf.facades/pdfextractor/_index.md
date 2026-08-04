---
title: "PdfExtractor"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas untuk mengekstrak gambar dan teks dari dokumen PDF."
type: docs
weight: 210
url: /id/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

Kelas untuk mengekstrak gambar dan teks dari dokumen PDF.

Tipe PdfExtractor menampilkan anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfExtractor() | Menginisialisasi objek [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/) baru. |
| PdfExtractor(document) | Menginisialisasi sebuah instance baru dari kelas PdfExtractor |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| start_page | Mendapatkan atau mengatur halaman awal dalam rentang halaman tempat operasi ekstraksi akan dilakukan. |
| end_page | Mendapatkan atau mengatur halaman akhir dalam rentang halaman tempat operasi ekstraksi akan dilakukan. |
| extract_text_mode | Mengatur mode untuk hasil ekstraksi teks. |
| text_search_options | Mendapatkan atau mengatur opsi pencarian teks. |
| extract_image_mode | Mengatur mode untuk proses ekstraksi gambar. |
| is_bidi | Benar ketika teks memiliki simbol Ibrani atau Arab. Kasus ini harus dipertimbangkan secara khusus karena<br/>            fungsi string mengubah perilakunya dan memulai proses teks dari kanan ke kiri (kecuali angka <br/>            dan karakter non-teks lainnya). |
| resolution | Mengatur atau mendapatkan resolusi untuk gambar yang diekstrak.<br/>            Nilai default adalah 150.<br/>            Gambar yang memiliki nilai resolusi lebih tinggi menjadi lebih jelas.<br/>            Namun meningkatkan nilai resolusi akan meningkatkan waktu dan memori yang dibutuhkan untuk mengekstrak gambar.<br/>            Biasanya untuk mendapatkan gambar yang jelas cukup mengatur resolusi ke 150 atau 300. |
| password | Mendapatkan atau mengatur kata sandi file input. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(input_file) | Mengikat file PDF input. |
| bind_pdf(input_stream) | Mengikat dokumen PDF dari aliran. |
| bind_pdf(src_doc) | Menginisialisasi facade. |
| extract_text() | Mengekstrak teks dari dokumen PDF menggunakan enkoding Unicode. |
| extract_text(encoding) | Mengekstrak teks dari dokumen PDF menggunakan enkoding yang ditentukan. |
| get_text(output_file) | Menyimpan teks ke file. lihat juga:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | Menyimpan teks ke aliran. lihat juga:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | Menyimpan teks ke aliran. lihat juga:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | Mengambil gambar berikutnya dari dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| get_next_image(output_file, format) | Mengambil gambar berikutnya dari dokumen PDF dengan format gambar yang diberikan. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| get_next_image(output_stream, format) | Mengambil gambar berikutnya dari file PDF dan menyimpannya ke aliran dengan format gambar yang diberikan. |
| get_next_image(output_stream) | Mengambil gambar berikutnya dari file PDF dan menyimpannya ke aliran dengan format gambar yang diberikan. |
| extract_attachment() | Mengekstrak lampiran dari dokumen PDF. |
| extract_attachment(attachment_file_name) | Mengekstrak lampiran ke file PDF berdasarkan nama lampiran. |
| get_next_page_text(output_file) | Menyimpan teks satu halaman ke file. |
| get_next_page_text(output_stream) | Menyimpan teks satu halaman ke stream. |
| close() | Membuang Aspose.Pdf.Document yang terikat dengan sebuah facade. |
| extract_image() | Ekstrak gambar dari file PDF. |
| has_next_image() | Memeriksa apakah lebih banyak gambar dapat diakses dalam dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| get_attach_names() | Mengembalikan daftar lampiran dalam file PDF. Catatan: ExtractAttachments harus dipanggil sebelum menggunakan metode ini. |
| get_attachment(output_path) | Menyimpan lampiran ke file. |
| has_next_page_text() | Menunjukkan apakah dapat mengambil lebih banyak teks atau tidak. |
| get_attachment_info() | Mendapatkan daftar lampiran. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

