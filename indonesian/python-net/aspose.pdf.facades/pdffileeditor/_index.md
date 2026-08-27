---
title: "PdfFileEditor"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Menerapkan operasi dengan penggabungan file PDF, pemisahan, mengekstrak halaman, membuat buku kecil, dll."
type: docs
weight: 220
url: /id/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

Menerapkan operasi dengan file PDF: penggabungan, pemisahan, ekstraksi halaman, pembuatan buku kecil, dll.

Tipe PdfFileEditor menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfFileEditor() | Menginisialisasi instance baru dari kelas PdfFileEditor |
## Properti
| Nama | Deskripsi |
| :- | :- |
| conversion_log | Mendapatkan log proses konversi. |
| merge_duplicate_layers | Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true. <br/>            Jika tidak, lapisan dengan nama yang sama akan disimpan sebagai lapisan terpisah dalam dokumen hasil. |
| copy_outlines | Jika true, maka outline akan disalin. |
| copy_logical_structure | Jika true, maka struktur logis file disalin saat penggabungan dilakukan. |
| merge_duplicate_outlines | Jika true, outline duplikat digabung. |
| preserve_user_rights | Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan. Hak pengguna dari semua dokumen lain diabaikan. |
| incremental_updates | Jika true, pembaruan inkremental dilakukan selama penggabungan. |
| optimize_size | Mendapatkan atau mengatur flag optimisasi. Aliran sumber daya yang sama dalam file hasil digabungkan menjadi satu objek PDF jika flag ini diatur. <br/>            Ini memungkinkan mengurangi ukuran file hasil tetapi dapat menyebabkan eksekusi lebih lambat dan kebutuhan memori yang lebih besar.<br/>            Nilai default: false. |
| corrupted_items | Array dari masalah yang ditemui ketika penggabungan dilakukan. Untuk setiap dokumen yang rusak yang diteruskan ke Concatenate() <br/>            fungsi entri CorruptedItem baru dibuat.<br/>            Properti ini hanya dapat digunakan ketika CorruptedFileAction bernilai ConcatenateIgnoringCorrupted. |
| corrupted_file_action | Properti ini mendefinisikan perilaku ketika proses penggabungan menemukan file yang rusak.<br/>            Nilai yang mungkin adalah: StopWithError dan ConcatenateIgnoringCorrupted. |
| owner_password | Mengatur kata sandi pemilik jika file Pdf masukan sumber dienkripsi.<br/>            Properti ini belum diimplementasikan. |
| allow_concatenate_exceptions | Jika diatur ke true, pengecualian akan dilemparkan jika terjadi kesalahan. Jika tidak, pengecualian tidak dilemparkan dan metode mengembalikan false jika gagal. |
| close_concatenated_streams | Jika diatur ke true, aliran akan ditutup setelah operasi. |
| unique_suffix | Format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan.<br/>            String ini harus berisi substring %NUM% yang akan diganti dengan angka.<br/>            Misalnya jika UniqueSuffix = "ABC%NUM%" maka untuk bidang "fieldName" nama-namanya akan menjadi:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3, dll. |
| keep_actions | Jika true, aksi akan disalin dari dokumen sumber. Nilai default: true. |
| keep_fields_unique | Jika true, nama bidang akan dibuat unik ketika formulir digabungkan.<br/>            Akhiran akan ditambahkan ke nama bidang, templat akhiran dapat ditentukan dalam properti UniqueSuffix. |
| remove_signatures | Jika true, semua tanda tangan akan dihapus dari bidang (bidang tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid. |
| use_disk_buffer | Jika opsi ini digunakan, maka dokumen tujuan akan disimpan ke disk secara berkala dan penggabungan selanjutnya akan diterapkan padanya sebagai pembaruan inkremental. |
| concatenation_packet_size | Jumlah dokumen yang digabungkan sebelum pembaruan inkremental baru dibuat selama proses penggabungan ketika UseDiskBuffer diatur ke true. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | Menggabungkan dua file. |
| try_concatenate(src, dest) | Menggabungkan dokumen. |
| try_concatenate(input_files, output_file) | Menggabungkan file menjadi satu file. |
| try_concatenate(input_stream, output_stream) | Menggabungkan file |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Menggabungkan dua file. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Menggabungkan file |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | Menambahkan halaman, yang dipilih dari array dokumen di portStreams.<br/>            Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portStreams dalam rentang startPage hingga endPage. |
| try_append(input_file, port_files, start_page, end_page, output_file) | Menambahkan halaman, yang dipilih dari dokumen portFiles. <br/>            Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portFiles dalam rentang startPage hingga endPage. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | Menyisipkan halaman dari file lain ke dalam file Pdf input. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | Menyisipkan halaman dari file lain ke dalam file Pdf input. |
| try_delete(input_file, page_number, output_file) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpannya sebagai file Pdf baru. |
| try_delete(input_stream, page_number, output_stream) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpannya sebagai file Pdf baru. |
| try_extract(input_file, start_page, end_page, output_file) | Mengekstrak halaman dari file input, menyimpannya sebagai file Pdf baru. |
| try_extract(input_file, page_number, output_file) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file PDF baru. |
| try_extract(input_stream, page_number, output_stream) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file Pdf baru. |
| try_split_from_first(input_file, location, output_file) | Membagi file Pdf dari halaman pertama hingga lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru. |
| try_split_from_first(input_stream, location, output_stream) | Membagi dari awal hingga lokasi yang ditentukan, dan menyimpan bagian depan di output Stream. |
| try_split_to_end(input_file, location, output_file) | Membagi dari lokasi, dan menyimpan bagian belakang sebagai file baru. |
| try_split_to_end(input_stream, location, output_stream) | Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru. |
| try_make_booklet(input_file, output_file) | Membuat buku kecil dari file input ke file output. |
| try_make_booklet(input_stream, output_stream) | Membuat buku kecil dari InputStream ke outputStream. |
| try_make_booklet(input_file, output_file, page_size) | Membuat buku kecil dari inputFile ke outputFile. |
| try_make_booklet(input_stream, output_stream, page_size) | Membuat buku kecil dari aliran input dan menyimpan hasil ke aliran output. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | Membuat buku kecil khusus dari firstInputFile ke outputFile. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | Membuat buku kecil khusus dari firstInputStream ke outputStream. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Membuat buku kecil khusus dari firstInputFile ke outputFile. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Membuat buku kecil dari firstInputStream ke outputStream. |
| try_make_n_up(input_file, output_file, x, y) | Membuat dokumen N-Up dari firstInputFile ke outputFile. |
| try_make_n_up(input_stream, output_stream, x, y) | Membuat dokumen N-Up dari aliran input dan menyimpan hasil ke aliran output. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | Membuat dokumen N-Up dari aliran input pertama ke aliran output. |
| try_make_n_up(first_input_file, second_input_file, output_file) | Membuat dokumen N-Up dari firstInputFile ke outputFile. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | Membuat dokumen N-Up dari aliran input dan menyimpan hasil ke aliran output. |
| try_make_n_up(input_files, output_file, is_sidewise) | Membuat dokumen N-Up dari beberapa file PDF masukan ke outputFile. <br/>            Setiap halaman outputFile akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman <br/>            dalam file masukan dengan nomor halaman yang sama. Beberapa halaman ditumpuk secara horizontal <br/>            jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | Membuat dokumen N-Up dari beberapa aliran PDF masukan ke outputStream.<br/>            Setiap halaman outputStream akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman <br/>            dalam aliran masukan dengan nomor halaman yang sama. Beberapa halaman ditumpuk secara horizontal <br/>            jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false. |
| try_make_n_up(input_file, output_file, x, y, page_size) | Membuat dokumen N-Up dari file masukan ke outputFile. |
| try_resize_contents(source, destination, pages, parameters) | Mengubah ukuran konten halaman dokumen. |
| try_resize_contents(source, destination, pages, new_width, new_height) | Mengubah ukuran konten halaman dokumen. <br/>            Mengecilkan konten halaman dan menambahkan margin.<br/>            Ukuran baru konten ditentukan dalam satuan ruang default. |
| try_resize_contents(source, destination, pages, parameters) | Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekitar halaman. |
| concatenate(first_input_file, sec_input_file, output_file) | Menggabungkan file dan menyimpan hasil ke objek HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | Menggabungkan file dan menyimpan hasil ke objek HttpResponse. |
| concatenate(src, dest) | Menggabungkan dokumen. |
| concatenate(input_files, output_file) | Menggabungkan file dan menyimpan hasil ke objek HttpResposnse. |
| concatenate(input_stream, output_stream) | Menggabungkan file dan menyimpan hasil ke objek HttpResponse. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Menggabungkan file dan menyimpan hasil ke objek HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Menggabungkan file dan menyimpan hasil ke objek HttpResponse. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | Menambahkan dokumen ke dokumen sumber dan menyimpan hasil ke objek response. |
| append(input_file, port_files, start_page, end_page, output_file) | Menambahkan dokumen ke dokumen sumber dan menyimpan hasil ke objek HttpResponse. |
| append(input_file, port_file, start_page, end_page, output_file) | Menambahkan dokumen ke dokumen sumber dan menyimpan hasil ke objek HttpResponse. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | Menambahkan dokumen ke dokumen sumber dan menyimpan hasil ke objek response. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | Menyisipkan konten file ke dalam file sumber dan menyimpan hasil ke objek HttpResponse. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | Menyisipkan dokumen ke dokumen lain dan menyimpan hasil ke objek respons. |
| insert(input_file, insert_location, port_file, page_number, output_file) | Menyisipkan konten file ke dalam file sumber dan menyimpan hasil ke objek HttpResponse. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | Menyisipkan dokumen ke dokumen lain dan menyimpan hasil ke objek respons. |
| delete(input_file, page_number, output_file) | Menghapus halaman yang ditentukan dari dokumen dan menyimpan hasil ke objek HttpResponse. |
| delete(input_stream, page_number, output_stream) | Menghapus halaman yang ditentukan dari dokumen dan menyimpan hasil ke objek HttpResponse. |
| extract(input_file, start_page, end_page, output_file) | Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasil ke objek HttpResponse. |
| extract(input_file, page_number, output_file) | Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasil ke objek HttpResponse. |
| extract(input_stream, start_page, end_page, output_stream) | Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasil ke objek HttpResponse. |
| extract(input_stream, page_number, output_stream) | Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasil ke objek HttpResponse. |
| split_from_first(input_file, location, output_file) | Membagi dokumen dari halaman pertama hingga lokasi dan menyimpan hasil ke objek HttpResponse. |
| split_from_first(input_stream, location, output_stream) | Membagi dokumen dari awal hingga lokasi yang ditentukan dan menyimpan hasil ke objek HttpResponse. |
| split_to_end(input_file, location, output_file) | Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang ke objek HttpResponse. |
| split_to_end(input_stream, location, output_stream) | Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang ke objek HttpResponse. |
| make_booklet(input_file, output_file) | Membuat buku kecil dari file sumber dan menyimpan hasil ke objek HttpResponse. |
| make_booklet(input_stream, output_stream) | Buat buklet dari file PDF dan simpan ke HttpResponse. |
| make_booklet(input_file, output_file, page_size) | Membuat buku kecil dari file sumber dan menyimpan hasil ke objek HttpResponse. |
| make_booklet(input_stream, output_stream, page_size) | Buat buklet dari file PDF dan simpan ke HttpResponse. |
| make_booklet(input_file, output_file, left_pages, right_pages) | Membuat buku kecil dari file sumber dan menyimpan hasil ke objek HttpResponse. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | Buat buklet dari file PDF dan simpan ke HttpResponse. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Membuat buku kecil dari file sumber dan menyimpan hasil ke objek HttpResponse. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Buat buklet dari file PDF dan simpan ke HttpResponse. |
| make_n_up(input_file, output_file, x, y) | Membuat dokumen N-up dan menyimpan hasil ke objek HttpResponse. |
| make_n_up(input_stream, output_stream, x, y) | Membuat dokumen N-up dan menyimpan hasil ke objek HttpResponse. |
| make_n_up(input_stream, output_stream, x, y, page_size) | Membuat dokumen N-up dan menyimpan hasil ke objek HttpResponse. |
| make_n_up(first_input_file, second_input_file, output_file) | Membuat dokumen N-up dan menyimpan hasil ke objek HttpResponse. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | Membuat dokumen N-up dan menyimpan hasil ke objek HttpResponse. |
| make_n_up(input_files, output_file, is_sidewise) | Membuat dokumen N-Up dari beberapa file PDF masukan ke outputFile. <br/>            Setiap halaman outputFile akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman <br/>            dalam file masukan dengan nomor halaman yang sama. Beberapa halaman ditumpuk secara horizontal <br/>            jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false. |
| make_n_up(input_streams, output_stream, is_sidewise) | Membuat dokumen N-Up dari beberapa aliran PDF masukan ke outputStream.<br/>            Setiap halaman outputStream akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman <br/>            dalam aliran masukan dengan nomor halaman yang sama. Beberapa halaman ditumpuk secara horizontal <br/>            jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false. |
| make_n_up(input_file, output_file, x, y, page_size) | Membuat dokumen N-up dan menyimpan hasil ke objek HttpResponse. |
| split_to_pages(input_file, file_name_template) | Membagi file PDF menjadi dokumen satu halaman. |
| split_to_pages(input_stream, file_name_template) | Membagi file PDF menjadi dokumen satu halaman dan menyimpannya ke jalur yang ditentukan. Jalur ditentukan oleh templat nama bidang. |
| resize_contents(source, destination, pages, parameters) | Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekitar halaman. Hasil disimpan ke objek HttpResponse. |
| resize_contents(source, destination, pages, new_width, new_height) | Mengubah ukuran konten halaman dokumen. <br/>            Mengecilkan konten halaman dan menambahkan margin.<br/>            Ukuran baru konten ditentukan dalam satuan ruang default. |
| resize_contents(source, destination, pages, new_width, new_height) | Mengubah ukuran konten halaman dokumen. <br/>            Mengecilkan konten halaman dan menambahkan margin.<br/>            Ukuran baru konten ditentukan dalam satuan ruang default. |
| resize_contents(source, destination, pages, parameters) | Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekitar halaman. Hasil disimpan ke objek HttpResponse. |
| resize_contents(source, pages, parameters) | Mengubah ukuran halaman dokumen. Margin kosong ditambahkan di sekitar halaman yang diperkecil. |
| resize_contents(source, parameters) | Mengubah ukuran halaman dokumen. Margin kosong ditambahkan di sekitar halaman yang diperkecil. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Mengubah ukuran konten halaman dokumen.<br/>            Memperkecil konten halaman dan menambahkan margin.<br/>            Ukuran konten baru ditentukan dalam persen. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Mengubah ukuran konten halaman dokumen.<br/>            Memperkecil konten halaman dan menambahkan margin.<br/>            Ukuran konten baru ditentukan dalam persen. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. <br/>            Margin ditentukan dalam satuan ruang default. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. <br/>            Margin ditentukan dalam satuan ruang default. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.<br/>            Margin ditentukan dalam persen dari ukuran halaman awal. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.<br/>            Margin ditentukan dalam persen dari ukuran halaman awal. |
| add_page_break(src, dest, page_breaks) | Menambahkan jeda halaman ke dalam halaman dokumen. |
| add_page_break(src, dest, page_breaks) | Menambahkan jeda halaman ke dalam halaman dokumen. |
| add_page_break(src, dest, page_breaks) | Menambahkan jeda halaman ke dalam halaman dokumen. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

