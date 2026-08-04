---
title: "DocSaveOptions"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Opsi penyimpanan untuk ekspor ke format Doc"
type: docs
weight: 220
url: /id/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Opsi penyimpanan untuk ekspor ke format Doc

Tipe DocSaveOptions menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| DocSaveOptions() | Menginisialisasi sebuah instance baru dari kelas DocSaveOptions |
## Properti
| Nama | Deskripsi |
| :- | :- |
| warning_handler | Callback untuk menangani peringatan apa pun yang dihasilkan. <br/>            WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. <br/>            Continue adalah aksi default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus dihentikan. |
| save_format | Format penyimpanan data. |
| close_response | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam response. |
| extract_ocr_sublayer_only | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks <br/>            untuk dokumen PDF dengan sublayer OCR. |
| try_merge_adjacent_same_background_images | Kadang-kadang PDF berisi gambar latar belakang (halaman atau sel tabel)<br/>              yang dibangun dari beberapa gambar latar belakang berulang yang ditempatkan berdekatan.<br/>              Dalam kasus seperti itu, renderer format target (mis. MsWord untuk format DOCS) terkadang menghasilkan<br/>              batasan visual antara bagian-bagian gambar latar belakang,<br/>              karena teknik mereka dalam menghaluskan tepi gambar (anti-aliasing) berbeda dari Acrobat Reader.<br/>               Jika tampaknya dokumen yang diekspor mengandung batasan visual semacam itu antara <br/>              bagian-bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan <br/>              efek yang tidak diinginkan. <br/>                PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi,<br/>              jadi, harap gunakan opsi ini hanya ketika memang diperlukan. |
| mode | Mode pengenalan. |
| relative_horizontal_proximity | Pada PDF, kata-kata dapat direpresentasikan secara internal dengan operator yang mencetak kata<br/>              secara terpisah dengan mencetak huruf atau suku kata masing‑masing. Jadi, untuk mendeteksi kata terkadang kami perlu mendeteksi kelompok<br/>              karakter independen yang sebenarnya merupakan kata.<br/>                Pengaturan ini menentukan lebar ruang antara elemen teks (huruf, suku kata) <br/>              yang harus diperlakukan sebagai jarak antar kata selama pengenalan kata dalam PDF sumber.<br/>              (keberadaan ruang kosong setidaknya dengan lebar ini antara huruf berarti bahwa <br/>               elemen teks termasuk dalam kata yang berbeda).<br/>              Nilainya dinormalkan terhadap ukuran font - 1.0 berarti 100% dari ukuran font kata yang dimaksud.<br/>             PERHATIAN!Hanya digunakan dalam kasus ketika PDF sumber berisi font khusus yang jarang digunakan<br/>             yang nilai optimalnya tidak dapat dihitung dari font. <br/>               Jadi, dalam sebagian besar kasus parameter ini tidak mengubah apa‑apa dalam dokumen hasil. |
| max_distance_between_text_lines | Parameter ini digunakan untuk mengelompokkan baris teks menjadi paragraf.<br/>            Menentukan seberapa jauh dua baris teks relatif dapat dipisahkan. Ditentukan dalam ratusan persen dari tinggi baris teks. |
| recognize_bullets | Aktifkan pengenalan bullet |
| add_return_to_line_end | Gunakan jeda paragraf atau baris |
| image_resolution_x | Resolusi X gambar yang dikonversi. |
| image_resolution_y | Resolusi Y gambar yang dikonversi. |
| format | Format output |
| batch_size | Mendefinisikan ukuran batch jika konversi batch berlaku<br/>            untuk pasangan format sumber dan tujuan. |
| memory_save_mode_path | Mendefinisikan jalur (nama file atau nama direktori) untuk menyimpan<br/>            data sementara saat melakukan konversi dalam mode penyimpanan memori. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

