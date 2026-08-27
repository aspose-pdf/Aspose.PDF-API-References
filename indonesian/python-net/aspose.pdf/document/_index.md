---
title: "Dokumen"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas yang mewakili dokumen PDF"
type: docs
weight: 230
url: /id/python-net/aspose.pdf/document/
---

## Document class

Kelas yang mewakili dokumen PDF

Tipe Document mengekspos anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Document(input) | Menginisialisasi instance baru dari kelas Document |
| Document(input, password, is_managed_stream) | Menginisialisasi instance baru dari kelas Document |
| Document(input, is_managed_stream) | Menginisialisasi instance baru dari kelas Document |
| Document(filename) | Menginisialisasi instance baru dari kelas Document |
| Document(input, password) | Menginisialisasi instance baru dari kelas Document |
| Document() | Menginisialisasi dokumen kosong. |
| Document(filename, options) | Menginisialisasi instance baru dari kelas Document |
| Document(input, options) | Menginisialisasi instance baru dari kelas Document |
| Document(filename, password) | Menginisialisasi instance baru dari kelas Document |
| Document(filename, password, is_managed_stream) | Menginisialisasi instance baru dari kelas Document |
## Properti
| Nama | Deskripsi |
| :- | :- |
| java_script | Koleksi JavaScript tingkat dokumen. |
| is_licensed | Mendapatkan status lisensi sistem. Mengembalikan true jika sistem berjalan dalam mode berlisensi dan false jika tidak. |
| page_info | Mendapatkan atau mengatur informasi halaman. (hanya untuk generator, tidak diisi saat membaca dokumen) |
| enable_signature_sanitization | Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan. Diaktifkan secara default. |
| is_pdfa_compliant | Mendapatkan apakah dokumen pdfa mematuhi. |
| is_pdf_ua_compliant | Mendapatkan apakah dokumen pdfua mematuhi. |
| is_xref_gaps_allowed | Mendapatkan atau mengatur apakah dokumen pdfa mematuhi. |
| named_destinations | Koleksi Named Destination dalam dokumen. |
| destinations | Mendapatkan koleksi destinasi.<br/>            Usang. Silakan gunakan NamedDestinations. |
| pdf_format | Mendapatkan format PDF |
| embed_standard_fonts | Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar <br/>            yang memiliki flag IsEmbedded disetel ke true. Semua font PDF dapat disematkan <br/>            ke dalam dokumen cukup dengan mengatur flag IsEmbedded menjadi true, tetapi font Type1 standar PDF merupakan pengecualian dari aturan ini.<br/>            Penyematan font Type1 standar membutuhkan banyak waktu, sehingga untuk menyematkan font ini diperlukan<br/>            tidak hanya mengatur flag IsEmbedded menjadi true untuk font tertentu tetapi juga mengatur <br/>            flag tambahan pada tingkat dokumen - EmbedStandardFonts = true;<br/>            Properti ini hanya dapat disetel satu kali untuk semua font.<br/>            Secara default false. |
| disable_font_license_verifications | Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font tersebut. <br/>            Misalnya beberapa font tidak dapat disematkan ke dalam dokumen PDF jika aturan lisensi melarang penyematan untuk font tersebut. <br/>            Flag ini digunakan untuk menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen PDF saat ini.<br/>            Hati-hati saat menggunakan flag ini. Ketika flag ini diaktifkan berarti orang yang mengaktifkannya, <br/>            mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi/hukum atas dirinya sendiri. <br/>            Jadi dia menanggung risikonya sendiri. <br/>            Sangat disarankan untuk menggunakan flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar <br/>            hukum hak cipta. <br/>            Secara default false. |
| font_utilities | IDocumentFontUtilities instance |
| collection | Mendapatkan koleksi dokumen. |
| version | Mendapatkan versi PDF dari header file PDF. |
| open_action | Mendapatkan atau mengatur aksi yang dilakukan saat dokumen dibuka. |
| hide_tool_bar | Mendapatkan atau mengatur flag yang menentukan apakah toolbar harus disembunyikan ketika dokumen aktif. |
| hide_menubar | Mendapatkan atau mengatur flag yang menentukan apakah menu bar harus disembunyikan ketika dokumen aktif. |
| hide_window_ui | Mendapatkan atau mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan ketika dokumen aktif. |
| fit_window | Mendapatkan atau mengatur flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. |
| center_window | Mendapatkan atau mengatur flag yang menentukan apakah posisi jendela dokumen akan dipusatkan pada layar. |
| display_doc_title | Mendapatkan atau mengatur flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. |
| halaman | Mendapatkan atau mengatur koleksi halaman dokumen.<br/>            Catatan bahwa halaman diberi nomor mulai dari 1 dalam koleksi. |
| outlines | Mendapatkan outline dokumen. |
| aksi | Mendapatkan aksi dokumen. Properti ini merupakan instance dari kelas **DocumentActions** yang memungkinkan untuk mendapatkan/mengatur aksi **BeforClosing**, **BeforSaving**, dll. |
| formulir | Mendapatkan Acro Form dokumen. |
| embedded_files | Mendapatkan koleksi file yang disematkan ke dokumen. |
| direction | Mendapatkan atau mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). |
| page_mode | Mendapatkan atau mengatur mode halaman, yang menentukan bagaimana dokumen harus ditampilkan saat dibuka. |
| non_full_screen_page_mode | Mendapatkan atau mengatur mode halaman, menentukan cara menampilkan dokumen saat keluar dari mode layar penuh. |
| page_layout | Mendapatkan atau mengatur tata letak halaman yang akan digunakan saat dokumen dibuka. |
| duplex | Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang akan digunakan saat mencetak file dari dialog cetak. |
| file_name | Nama file PDF yang menyebabkan dokumen ini |
| info | Mendapatkan info dokumen. |
| metadata | Metadata dokumen.<br/>            (Sebuah dokumen PDF dapat menyertakan informasi umum,<br/>             seperti judul dokumen, penulis, serta tanggal pembuatan dan modifikasi.<br/>             Informasi global semacam itu tentang dokumen (berlawanan dengan isi atau strukturnya) disebut metadata<br/>             dan dimaksudkan untuk membantu dalam pengkatalogan dan pencarian dokumen di basis data eksternal.) |
| logical_structure | Mendapatkan struktur logis dokumen. |
| handle_signature_change | Lempar Exception jika dokumen akan disimpan dengan perubahan dan memiliki tanda tangan |
| crypto_algorithm | Mendapatkan pengaturan keamanan jika dokumen terenkripsi. <br/>            Jika dokumen tidak terenkripsi maka pengecualian yang sesuai akan dilempar di .net 1.1<br/>            atau CryptoAlgorithm akan bernilai null untuk versi .net lainnya. |
| is_linearized | Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen terlinier. |
| permissions | Mendapatkan izin dokumen. |
| is_encrypted | Mendapatkan status enkripsi dokumen. True jika dokumen terenkripsi. |
| id | Mendapatkan ID. |
| background | Mendapatkan atau mengatur warna latar belakang dokumen. |
| optimize_size | Mendapatkan atau mengatur flag optimisasi. Ketika halaman ditambahkan ke dokumen, aliran sumber daya yang sama dalam file hasil<br/>            digabungkan menjadi satu objek PDF jika flag ini diatur. <br/>            Ini memungkinkan mengurangi ukuran file hasil tetapi dapat menyebabkan eksekusi lebih lambat dan kebutuhan memori yang lebih besar.<br/>            Nilai default: false. |
| allow_reuse_page_content | Memungkinkan penggabungan konten halaman untuk mengoptimalkan ukuran dokumen. Jika digunakan, maka halaman yang berbeda namun duplikat dapat merujuk ke <br/>            objek konten yang sama. Harap dicatat bahwa mode ini dapat menyebabkan efek samping seperti mengubah konten halaman ketika halaman lain diubah. |
| ignore_corrupted_objects | Mendapatkan atau mengatur flag untuk mengabaikan kesalahan dalam file sumber. <br/>            Ketika halaman dari dokumen sumber disalin ke dokumen tujuan, proses penyalinan dihentikan dengan pengecualian <br/>            jika beberapa objek dalam file sumber rusak ketika flag ini bernilai false. <br/>            contoh: dest.Pages.Add(src.Pages);<br/>            Jika flag ini diatur ke true, maka objek yang rusak akan diganti dengan nilai kosong.<br/>            Secara default: true. |
| page_labels | Mendapatkan label halaman dalam dokumen. |
| enable_object_unload | Mendapatkan atau mengatur flag yang memungkinkan dokumen sebagian dibongkar dari memori. <br/>            Ini memungkinkan pengurangan penggunaan memori tetapi dapat memiliki efek negatif pada kinerja. |
| tagged_content | Mendapatkan akses ke konten TaggedPdf. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| save(output) | Menyimpan dokumen ke dalam aliran. |
| save(output_file_name) | Menyimpan dokumen ke file yang ditentukan. |
| save() | Menyimpan dokumen ke dalam aliran. |
| save(options) | Menyimpan dokumen dengan opsi penyimpanan. |
| save(output_file_name, format) | Menyimpan dokumen dengan nama baru beserta format file. |
| save(output_stream, format) | Menyimpan dokumen dengan nama baru beserta format file. |
| save(output_file_name, options) | Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya. |
| save(output_stream, options) | Menyimpan dokumen ke aliran dengan opsi penyimpanan. |
| export_annotations_to_xfdf(file_name) | Mengekspor semua anotasi dokumen ke file XFDF |
| export_annotations_to_xfdf(stream) | Ekspor semua anotasi dokumen ke dalam aliran. |
| send_to(device, output) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| send_to(device, from_page, to_page, output) | Mengirim halaman tertentu dari dokumen ke perangkat dokumen untuk diproses. |
| send_to(device, output_file_name) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| send_to(device, from_page, to_page, output_file_name) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| import_annotations_from_xfdf(file_name) | Mengimpor anotasi dari file XFDF ke dokumen. |
| import_annotations_from_xfdf(stream) | Mengimpor anotasi dari aliran ke dokumen. |
| validate(output_log_file_name, format) | Validasi dokumen ke dalam file yang ditentukan. |
| validate(output_log_stream, format) | Validasi dokumen ke dalam file yang ditentukan. |
| validate(options) | Validasi dokumen ke dalam file yang ditentukan. |
| convert(output_log_file_name, format, action, transparency_action) | Konversi dokumen dan simpan kesalahan ke dalam file yang ditentukan. |
| convert(output_log_stream, format, action, transparency_action) | Konversi dokumen dan simpan kesalahan ke dalam file yang ditentukan. |
| convert(output_log_file_name, format, action) | Konversi dokumen dan simpan kesalahan ke dalam file yang ditentukan. |
| convert(options) | Konversi dokumen menggunakan opsi konversi yang ditentukan |
| convert(output_log_stream, format, action) | Konversi dokumen dan simpan kesalahan ke dalam file yang ditentukan. |
| convert(fixup, output_log, only_validation, parameters) | Konversi dokumen dengan menerapkan Fixup. |
| convert(fixup, output_log, only_validation, parameters) | Konversi dokumen dengan menerapkan Fixup. |
| convert(src_file_name, load_options, dst_file_name, save_options) | Mengonversi file sumber dalam format sumber menjadi file tujuan dalam format tujuan. |
| convert(src_stream, load_options, dst_file_name, save_options) | Mengonversi aliran dalam format sumber menjadi file tujuan dalam format tujuan. |
| convert(src_file_name, load_options, dst_stream, save_options) | Mengonversi aliran dalam format sumber menjadi file tujuan dalam format tujuan. |
| convert(src_stream, load_options, dst_stream, save_options) | Mengonversi aliran dalam format sumber menjadi file tujuan dalam format tujuan. |
| flatten() | Menghapus semua bidang dari dokumen dan menempatkan nilai mereka sebagai gantinya. |
| flatten(flatten_settings) | Menghapus semua bidang dari dokumen dan menempatkan nilai mereka sebagai gantinya. |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | Mengenkripsi dokumen. Panggil kemudian Save untuk mendapatkan versi dokumen yang terenkripsi. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | Mengenkripsi dokumen. Panggil kemudian Save untuk mendapatkan versi dokumen yang terenkripsi. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | Mengenkripsi dokumen. Panggil kemudian Save untuk mendapatkan versi dokumen yang terenkripsi. |
| optimize_resources() | Optimalkan sumber daya dalam dokumen:<br/>            1. Sumber daya yang tidak digunakan pada halaman dokumen dihapus;<br/>            2. Sumber daya yang sama digabung menjadi satu objek; <br/>            3. Objek yang tidak terpakai dihapus. |
| optimize_resources(strategy) | Optimalkan sumber daya dalam dokumen sesuai dengan strategi optimasi yang ditentukan. |
| bind_xml(file) | Mengikat xml ke dokumen |
| bind_xml(xml_file, xsl_file) | Mengikat xml ke dokumen |
| bind_xml(xml_stream, xsl_stream) | Mengikat xml/xsl ke dokumen |
| bind_xml(stream) | Mengikat xml/xsl ke dokumen |
| remove_pdfa_compliance() | Menghapus kepatuhan pdfa dari dokumen |
| remove_pdf_ua_compliance() | Menghapus kepatuhan pdfUa dari dokumen |
| set_title(title) | Atur Judul untuk Dokumen Pdf |
| process_paragraphs() | Proses paragraf untuk generator. |
| remove_metadata() | Menghapus metadata dari dokumen. |
| change_passwords(owner_password, new_user_password, new_owner_password) | Mengubah kata sandi dokumen. Tindakan ini hanya dapat dilakukan menggunakan kata sandi pemilik. |
| decrypt() | Mendekripsi dokumen. Panggil kemudian Save untuk mendapatkan versi dokumen yang didekripsi. |
| optimize() | Linearize dokumen untuk<br/>            - membuka halaman pertama secepat mungkin;<br/>            - menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin;<br/>            - menampilkan halaman secara bertahap saat data halaman tiba ketika data dikirim melalui saluran lambat (menampilkan data yang paling berguna terlebih dahulu);<br/>            - memungkinkan interaksi pengguna, seperti mengikuti tautan, dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan.<br/>            Memanggil metode ini sebenarnya tidak menyimpan dokumen. Sebaliknya dokumen hanya dipersiapkan dengan struktur yang dioptimalkan,<br/>            panggil kemudian Save untuk mendapatkan dokumen yang dioptimalkan. |
| get_catalog_value(key) | Mengembalikan nilai item dari kamus katalog. |
| free_memory() | Membersihkan memori |
| save_xml(file) | Simpan dokumen ke XML. |
| get_object_by_id(id) | Mendapatkan objek dengan ID tertentu dalam dokumen. |
| repair() | Memperbaiki dokumen yang rusak. |
| get_xmp_metadata(stream) | Dapatkan metadata XMP dari dokumen. |
| set_xmp_metadata(stream) | Atur metadata XMP dokumen. |
| check(do_repair) | Memvalidasi dokumen. |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang.<br/>            Hanya jika dokumen memiliki lebih dari nodesNumInSubtrees objek halaman, jika tidak tidak melakukan apa‑apa. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

