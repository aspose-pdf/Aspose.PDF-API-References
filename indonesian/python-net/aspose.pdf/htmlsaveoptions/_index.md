---
title: "HtmlSaveOptions"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Opsi penyimpanan untuk mengekspor ke format Html"
type: docs
weight: 490
url: /id/python-net/aspose.pdf/htmlsaveoptions/
---

## HtmlSaveOptions class

Opsi penyimpanan untuk mengekspor ke format Html

Tipe HtmlSaveOptions menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| HtmlSaveOptions() | Menginisialisasi sebuah instance baru dari kelas [HtmlSaveOptions](/pdf/python-net/aspose.pdf/htmlsaveoptions/). |
| HtmlSaveOptions(document_type) | Menginisialisasi sebuah instance baru dari kelas HtmlSaveOptions |
| HtmlSaveOptions(fixed_layout) | Menginisialisasi sebuah instance baru dari kelas HtmlSaveOptions |
| HtmlSaveOptions(document_type, fixed_layout) | Menginisialisasi sebuah instance baru dari kelas HtmlSaveOptions |
## Properti
| Nama | Deskripsi |
| :- | :- |
| warning_handler | Callback untuk menangani peringatan apa pun yang dihasilkan. <br/>            WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. <br/>            Continue adalah aksi default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus dihentikan. |
| save_format | Format penyimpanan data. |
| close_response | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam response. |
| extract_ocr_sublayer_only | None |
| try_merge_adjacent_same_background_images | None |
| document_type | Mendapatkan atau mengatur [HtmlDocumentType](/pdf/python-net/aspose.pdf/htmldocumenttype/). |
| compress_svg_graphics_if_any | Mendapatkan atau mengatur flag yang menunjukkan apakah<br/>            grafik SVG yang ditemukan (jika ada) akan dikompresi (dizip) <br/>            ke format SVGZ selama penyimpanan |
| split_css_into_pages | Ketika mode multipage dipilih (misalnya 'SplitIntoPages' bernilai 'true'), <br/>            maka atribut ini menentukan apakah harus dibuat file CSS terpisah<br/>            untuk setiap halaman HTML hasil.<br/>            Secara default atribut ini bernilai false, sehingga akan dibuat<br/>            satu CSS besar bersama untuk semua halaman yang dibuat. Ukuran total semua<br/>            CSS yang dihasilkan dalam mode ini (satu CSS per halaman) biasanya<br/>            jauh lebih besar daripada ukuran satu file CSS besar, karena pada kasus sebelumnya <br/>            kelas CSS duplikat muncul di beberapa file CSS untuk setiap halaman.<br/>            Jadi, pengaturan ini sebaiknya hanya digunakan ketika Anda tertarik<br/>            pada pemrosesan lanjutan setiap halaman HTML secara independen, dan oleh karena itu ukuran<br/>            CSS dari setiap halaman yang dipisahkan menjadi isu paling kritis. |
| split_into_pages | Mendapatkan atau mengatur flag yang menunjukkan apakah setiap halaman dokumen sumber <br/>            akan dikonversi menjadi dokumen HTML targetnya masing-masing, <br/>            yaitu apakah HTML hasil akan dibagi menjadi beberapa halaman HTML. |
| explicit_list_of_saved_pages | Dengan properti ini Anda dapat secara eksplisit menentukan <br/>            halaman mana dari dokumen yang harus dikonversi.<br/>            Halaman dalam daftar ini harus memiliki nomor berbasis 1. Misalnya <br/>            nomor halaman yang valid harus diambil dari rentang (1...[NumberOfPagesInConvertedDocument])<br/>            Urutan munculnya halaman dalam daftar ini tidak memengaruhi <br/>            urutan mereka dalam halaman HTML hasil - dalam halaman hasil selalu akan mengikuti urutan di mana mereka <br/>            muncul dalam PDF sumber.<br/>            Jika daftar ini null (seperti default), semua halaman akan dikonversi.<br/>            Jika ada nomor halaman dalam daftar ini yang berada di luar rentang halaman yang ada (1-[amountOfPagesInDocument])<br/>            akan dilemparkan pengecualian. |
| fixed_layout | Mendapatkan atau mengatur nilai yang menunjukkan apakah HTML tersebut dibuat sebagai tata letak tetap. |
| image_resolution | Mendapatkan atau mengatur resolusi untuk rendering gambar. |
| default_font_name | Menentukan nama font yang terpasang yang digunakan untuk menggantikan<br/>            font dokumen apa pun yang tidak ter-embed dan tidak terpasang di sistem. <br/>            Jika null maka font substitusi default akan digunakan. |
| batch_size | Mendefinisikan ukuran batch jika konversi batch berlaku<br/>            untuk pasangan format sumber dan tujuan. |
| font_sources | Sumber font dari font yang telah disimpan sebelumnya. |
| additional_margin_width_in_points | Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF input tidak akan<br/>            dipisahkan menjadi halaman HTML yang berbeda, melainkan akan dimasukkan ke dalam satu file HTML hasil yang besar.<br/>            Namun setiap halaman PDF sumber akan diwakili dengan area persegi panjangnya sendiri <br/>            di HTML (jika diperlukan area tersebut dapat diberi batas untuk menunjukkan tepi kertas halaman<br/>            dengan atribut khusus 'PageBorderIfAny'.<br/>            Parameter ini menentukan lebar margin yang akan dipaksa ditinggalkan di sekitar area HTML output<br/>            yang mewakili halaman dokumen PDF sumber. Pada dasarnya ini menentukan interval terjamin antara<br/>            representasi HTML dari halaman "kertas" PDF dalam mode konversi ini. |
| use_z_order | Jika atribut UseZORder diatur ke true, grafik dan teks ditambahkan ke dokumen HTML hasil<br/>            sesuai urutan Z dalam dokumen PDF asli. Jika atribut ini false, semua grafik ditempatkan<br/>            sebagai satu lapisan yang dapat menyebabkan efek tidak perlu pada objek yang tumpang tindih. |
| convert_marked_content_to_layers | Jika atribut ConvertMarkedContentToLayers diatur ke true maka semua elemen di dalam konten PDF yang ditandai<br/>            (lapisan) akan ditempatkan ke dalam div HTML dengan atribut "data-pdflayer" yang menentukan nama lapisan.<br/>            Nama lapisan ini akan diambil dari properti opsional konten PDF yang ditandai.<br/>            Jika atribut ini false (secara default) maka tidak ada lapisan yang akan dibuat dari konten PDF yang ditandai. |
| minimal_line_width | Atribut ini menetapkan lebar minimal garis jalur grafis.<br/>            Jika ketebalan garis kurang dari 1px, Adobe Acrobat membulatkannya ke nilai ini. Jadi atribut ini dapat<br/>            digunakan untuk meniru perilaku tersebut pada peramban HTML. |
| prevent_glyphs_grouping | Atribut ini mengaktifkan mode di mana glyph teks tidak akan dikelompokkan menjadi kata dan string<br/>            Mode ini memungkinkan mempertahankan presisi maksimum saat penempatan glyph pada halaman dan dapat<br/>            digunakan untuk mengonversi dokumen dengan notasi musik atau glyph yang harus ditempatkan secara terpisah satu sama lain.<br/>            Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| simple_textbox_mode_grouping | Atribut ini menentukan pengelompokan berurutan glyph dan kata menjadi string<br/>            Misalnya tag dan kata memiliki urutan yang berbeda dalam HTML yang dikonversi dan Anda ingin keduanya cocok.<br/>            Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| flow_layout_paragraph_full_width | Atribut ini menentukan teks paragraf lebar penuh untuk mode Flow, FixedLayout = false |
| render_text_as_image | Jika atribut RenderTextAsImage diatur ke true, teks dari sumber menjadi gambar dalam HTML.<br/>            Mungkin berguna untuk membuat teks tidak dapat dipilih<br/>            atau teks HTML tidak dirender dengan benar. |
| save_full_font | Menunjukkan bahwa font lengkap akan disimpan, hanya mendukung True Type Fonts.<br/>            Secara default SaveFullFont = false dan konverter menyimpan subset font awal<br/>            yang diperlukan untuk menampilkan teks dokumen. |
| antialiasing_processing | Parameter ini menentukan langkah antialiasing yang diperlukan selama konversi gambar latar belakang kompleks dari PDF ke HTML |
| save_transparent_texts | Pdf dapat berisi teks transparan yang dapat disalin ke clipboard (biasanya terjadi ketika dokumen berisi gambar dan teks hasil OCR yang diekstrak darinya).<br/>            Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan<br/>            yang dapat dipilih dalam HTML hasil. |
| save_shadowed_texts_as_transparent_texts | Pdf dapat berisi teks yang tertutup oleh elemen lain (misalnya oleh gambar) tetapi <br/> dapat dipilih ke clipboard di Acrobat Reader (biasanya terjadi ketika dokumen berisi gambar dan teks OCR yang diekstrak darinya).<br/> Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan <br/> yang dapat dipilih dalam HTML hasil untuk meniru perilaku Acrobat Reader (sebaliknya teks tersebut biasanya disimpan sebagai tersembunyi, tidak tersedia untuk disalin ke clipboard) |
| font_saving_mode | Menentukan mode penyimpanan font yang akan digunakan selama penyimpanan PDF ke format yang diinginkan |
| page_border_if_any | Atribut ini mewakili sekumpulan pengaturan yang digunakan untuk menggambar batas (jika ada)<br/> dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber.<br/> Pada dasarnya ini berkaitan dengan menampilkan tepi kertas halaman,<br/> bukan batas halaman yang direferensikan dalam halaman PDF itu sendiri. |
| page_margin_if_any | Atribut ini mewakili sekumpulan margin halaman tambahan (jika ada)<br/> dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. |
| letters_positioning_method | Menetapkan mode penempatan huruf dalam kata pada HTML hasil |
| exclude_font_name_list | Daftar nama font PDF yang tertanam yang tidak akan ditanamkan dalam HTML. |
| special_folder_for_svg_images | Mengambil atau mengatur jalur ke direktori tempat hanya gambar SVG yang harus disimpan jika mereka <br/> ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null<br/> maka file SVG (jika ada) akan disimpan bersama file gambar lainnya (dekat file output)<br/> atau di folder khusus untuk gambar (jika ditentukan dalam opsi SpecialImagesFolderIfAny).<br/> Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy<br/> telah berhasil digunakan untuk memproses file gambar yang relevan. |
| special_folder_for_all_images | Mengambil atau mengatur jalur ke direktori tempat semua gambar harus disimpan jika mereka <br/> ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null<br/> maka file gambar (jika ada) akan disimpan bersama file lain yang terhubung ke HTML<br/> Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy<br/> telah berhasil digunakan untuk memproses file gambar yang relevan. |
| css_class_names_prefix | Ketika konverter PDFtoHTML menghasilkan CSS hasil, nama kelas CSS<br/> (misalnya ".stl_01 {}" ... ".stl_NN {}") dihasilkan<br/> dan digunakan dalam CSS hasil. Properti ini memungkinkan untuk memaksa menetapkan awalan nama kelas<br/> Misalnya, jika Anda ingin semua nama kelas dimulai dengan 'my_prefix_'<br/> (yaitu sesuatu seperti 'my_prefix_1' ... 'my_prefix_NNN'), <br/> maka cukup tetapkan 'my_prefix_' ke properti ini sebelum konversi.<br/> Jika properti ini dibiarkan tidak berubah (misalnya null akan tetap sebagai nilai), maka<br/> konverter akan menghasilkan nama kelas sendiri <br/> (akan menjadi sesuatu seperti ".stl_01 {}" ... ".stl_NN {}") |
| parts_embedding_mode | Ini menentukan apakah file yang direferensikan (HTML, Font, Gambar, CSS)<br/> akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah |
| html_markup_generation_mode | Terkadang ada persyaratan khusus untuk pembuatan markup HTML.<br/> Parameter ini menentukan mode persiapan HTML yang dapat digunakan<br/> selama konversi PDF ke HTML untuk memenuhi persyaratan khusus tersebut. |
| raster_images_saving_mode | PDF yang dikonversi dapat berisi gambar raster<br/> Parameter ini menentukan bagaimana mereka harus diproses<br/> selama konversi PDF ke HTML |
| remove_empty_areas_on_top_and_bottom | Mendefinisikan apakah pada HTML yang dibuat area kosong di bagian atas dan bawah akan dihapus tanpa konten apa pun (jika ada). |
| font_encoding_strategy | Mendefinisikan aturan khusus pengkodean untuk menyesuaikan dekripsi PDF untuk dokumen saat ini. |
| pages_flow_type_depends_on_viewers_screen_size | Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF input akan <br/>            dimasukkan ke dalam satu file HTML hasil yang besar. <br/>            Bendera ini menentukan apakah HTML hasil akan dihasilkan dengan cara<br/>            sehingga aliran area yang mewakili halaman PDF dalam HTML hasil akan bergantung<br/>            pada resolusi layar penampil. <br/>            Anggap lebar layar pada sisi penampil cukup besar untuk menempatkan 2 atau lebih halaman berdampingan<br/>            secara horizontal. Jika bendera ini diatur ke true, maka kesempatan ini<br/>            akan digunakan (sebanyak mungkin halaman akan ditampilkan secara horizontal berdampingan<br/>            sejauh memungkinkan, kemudian grup halaman horizontal berikutnya akan ditampilkan di bawah yang pertama ).<br/>            Jika tidak, halaman akan mengalir dengan cara berikut: halaman berikutnya selalu berada di bawah halaman sebelumnya. |
| try_save_text_underlining_and_strikeouting_in_css | PDF itu sendiri tidak mengandung penanda garis bawah untuk teks. Itu disimulasikan dengan garis yang terletak di bawah teks.<br/>            Opsi ini memungkinkan konverter mencoba menebak bahwa garis ini atau itu adalah garis bawah teks<br/>            dan menempatkan informasi ini ke dalam CSS alih-alih menggambar garis bawah secara grafis |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

