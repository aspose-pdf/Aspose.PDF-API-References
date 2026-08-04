---
title: "FormEditor"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas untuk mengedit formulir (menambah/menghapus bidang, dll)."
type: docs
weight: 110
url: /id/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Kelas untuk mengedit formulir (menambah/menghapus bidang, dll).

Tipe FormEditor menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| FormEditor(src_stream, dest_stream) | Menginisialisasi sebuah instance baru dari kelas FormEditor |
| FormEditor(src_file_name, dest_file_name) | Menginisialisasi sebuah instance baru dari kelas FormEditor |
| FormEditor() | Konstruktor untuk FormEditor. |
| FormEditor(document) | Menginisialisasi sebuah instance baru dari kelas FormEditor |
| FormEditor(document, dest_file_name) | Menginisialisasi sebuah instance baru dari kelas FormEditor |
| FormEditor(document, dest_stream) | Menginisialisasi sebuah instance baru dari kelas FormEditor |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| src_file_name | Mendapatkan atau mengatur nama file sumber. |
| dest_file_name | Mendapatkan atau mengatur nama file tujuan. |
| src_stream | Mendapatkan atau mengatur aliran sumber. |
| dest_stream | Mendapatkan atau mengatur aliran tujuan. |
| items | Mengatur item yang akan ditambahkan ke list box atau combo box yang baru dibuat. |
| export_items | Mengatur opsi untuk combo box dengan nilai ekspor. |
| facade | Mengatur atribut visual dari bidang. |
| radio_gap | Anggota untuk mencatat jarak antara dua tombol radio yang berdekatan dalam piksel, defaultnya 50. |
| radio_horiz | Bendera untuk menunjukkan apakah tombol radio diatur secara horizontal atau vertikal, nilai default adalah true. |
| radio_button_item_size | Mendapatkan atau mengatur ukuran item tombol radio (ketika bidang tombol radio baru ditambahkan). |
| submit_flag | Atur flag pengiriman tombol submit. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(src_file) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_stream) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save() | Menyimpan perubahan ke file tujuan. |
| save(dest_file) | Menyimpan perubahan ke file tujuan. |
| save(dest_stream) | Menyimpan perubahan ke file tujuan. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | Menambahkan bidang dengan tipe yang ditentukan ke formulir. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | Menambahkan bidang dengan tipe yang ditentukan ke formulir. |
| copy_inner_field(field_name, new_field_name, page_num) | Menyalin bidang yang ada ke posisi yang sama pada nomor halaman yang ditentukan.<br/>            Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali bidang yang baru disalin. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | Menyalin bidang yang ada ke posisi baru yang ditentukan oleh nomor halaman dan koordinat.<br/>            Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali bidang yang baru disalin. |
| copy_outer_field(src_file_name, field_name) | Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan koordinat asli.<br/>            Catatan: Hanya untuk bidang AcroForm (tidak termasuk kotak radio). |
| copy_outer_field(src_file_name, field_name, page_num) | Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan koordinat asli.<br/>             Catatan: Hanya untuk bidang AcroForm (tidak termasuk kotak radio). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | Menyalin bidang yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan koordinat yang ditentukan.<br/>            Catatan: Hanya untuk bidang AcroForm (tidak termasuk kotak radio). |
| decorate_field(field_name) | Mengubah atribut visual dari bidang yang ditentukan. |
| decorate_field(field_type) | Mengubah atribut visual semua bidang dengan tipe bidang yang ditentukan. |
| decorate_field() | Mengubah atribut visual dari bidang yang ditentukan. |
| add_list_item(field_name, item_name) | Menambahkan item baru ke kotak daftar. |
| add_list_item(field_name, export_name) | Menambahkan item baru dengan nilai Export ke bidang kotak daftar yang ada, hanya untuk bidang kotak kombo AcroForm. |
| close() | Menutup antarmuka. |
| set_field_attribute(field_name, flag) | Mengatur atribut bidang. |
| set_field_appearance(field_name, flags) | Mengatur flag bidang |
| get_field_appearance(field_name) | Mendapatkan flag bidang. |
| set_submit_flag(field_name, submit_form_flag) | Mengatur flag submit tombol. |
| set_submit_url(field_name, url) | Mengatur URL tombol. |
| set_field_limit(field_name, field_limit) | Mengatur jumlah karakter maksimum bidang teks. |
| set_field_comb_number(field_name, comb_number) | Mengatur jumlah comb untuk bidang teks satu baris reguler (bidang tersebut <br/>            secara otomatis dibagi menjadi sebanyak posisi yang berjarak sama, atau comb, <br/>            sesuai nilai parameter combNumber). |
| move_field(field_name, llx, lly, urx, ury) | Mengatur posisi baru bidang. |
| remove_field(field_name) | Menghapus bidang dari formulir. |
| reset_facade() | Setel semua atribut visual ke nilai kosong. |
| reset_inner_facade() | Setel semua atribut visual dari facade dalam ke nilai kosong. |
| rename_field(field_name, new_field_name) | Ubah nama bidang. |
| remove_field_action(field_name) | Hapus aksi submit dari bidang. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | Tambahkan tombol submit pada formulir. |
| del_list_item(field_name, item_name) | Hapus item dari bidang daftar. |
| set_field_script(field_name, script) | Atur JavaScript untuk bidang PushButton. Jika JavaScript lama ada, akan diganti dengan yang baru. |
| add_field_script(field_name, script) | Tambahkan JavaScript untuk bidang PushButton. Jika acara lama ada, acara baru akan ditambahkan setelahnya. |
| single_2_multiple(field_name) | Ubah bidang teks satu baris menjadi beberapa baris. |
| set_field_alignment(field_name, alignment) | Atur gaya perataan bidang teks. |
| set_field_alignment_v(field_name, alignment) | Atur gaya perataan vertikal bidang teks. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

