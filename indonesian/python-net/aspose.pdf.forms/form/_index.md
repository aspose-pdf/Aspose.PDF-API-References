---
title: "Form"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas yang mewakili objek formulir."
type: docs
weight: 110
url: /id/python-net/aspose.pdf.forms/form/
---

## Form class

Kelas yang mewakili objek formulir.

Tipe Form menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| is_synchronized | Mengembalikan true jika objek aman terhadap thread. |
| sync_root | Mengembalikan objek sinkronisasi. |
| auto_recalculate | Jika diatur, semua bidang formulir akan dihitung ulang ketika ada bidang yang berubah. Nilai default adalah true. Atur ke false untuk meningkatkan kinerja saat mengisi formulir dengan sejumlah besar bidang yang dihitung. |
| auto_restore_form | Jika diatur, bidang formulir yang tidak ada akan secara otomatis dibuat jika mereka terdapat dalam anotasi. |
| default_resources | Mendapatkan sumber daya default yang ditempatkan pada formulir ini. |
| default_appearance | Mendapatkan atau mengatur tampilan default formulir (objek yang mendeskripsikan font default, ukuran teks, dan warna untuk bidang pada formulir). |
| xfa | Mendapatkan data XFA dari formulir (jika ada). |
| ignore_needs_rendering | Jika properti ini bernilai true, nilai kunci NeedsRendering akan diabaikan selama konversi <br/>            formulir XFA ke formulir Standar. Nilainya false secara default. |
| remove_permission | Jika properti ini bernilai true, kamus \"Perms\" akan dihapus dari dokumen pdf setelah konversi <br/>            dokumen dinamis ke standar. Kamus \"Perms\" dapat berisi aturan yang mengganggu penampilan pilihan <br/>            bidang wajib di Adobe Acrobat reader.<br/>            Nilainya false secara default. |
| emulate_requierd_groups | Jika properti ini bernilai true, maka persegi panjang batas merah tambahan akan digambar untuk kontainer elemen Xfa exclGroup yang wajib<br/>            Properti ini diperkenalkan karena tidak adanya analog untuk exclGroup selama konversi representasi Xfa dari formulir <br/>            ke standar.<br/>            Nilainya false secara default. |
| type | Mendapatkan tipe formulir. Nilai yang mungkin: Standard, Static, Dynamic. |
| fields | Mendapatkan daftar semua bidang pada tingkat terendah dari formulir hierarkis. |
| signatures_exist | Jika diatur, dokumen berisi setidaknya satu bidang tanda tangan. |
| signatures_append_only | Jika diatur, dokumen berisi tanda tangan yang dapat menjadi tidak valid jika file disimpan (ditulis) dengan cara yang mengubah isi sebelumnya, <br/>            berbeda dengan pembaruan inkremental. |
| sign_dependent_elements_rendering_mode_when_converted | Formulir dapat berisi informasi penandatanganan, yaitu dapat ditandatangani atau tidak.<br/>              Dan tampilan formulir terkadang harus bergantung pada apakah formulir ditandatangani atau tidak.<br/>              Properti ini memberi tahu konverter formulir (misalnya selama konversi formulir XFA ke formulir Standar)<br/>              apakah formulir hasil harus dirender sebagai ditandatangani atau tidak ditandatangani. |
## Indexer
| Nama | Deskripsi |
| :- | :- |
| [index] | Mendapatkan bidang formulir berdasarkan indeks bidang. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| delete(field) | Hapus bidang dari formulir. |
| delete(field_name) | Menghapus bidang dari formulir berdasarkan namanya. |
| add(field, page_number) | Menambahkan bidang pada formulir. |
| add(field) | Menambahkan bidang pada formulir. |
| add(field, partial_name, page_number) | Menambahkan bidang baru ke formulir; Jika bidang ini sudah ditempatkan pada formulir lain atau formulir ini, salinan bidang akan dibuat. |
| has_field(field) | Periksa apakah formulir sudah memiliki bidang yang ditentukan. |
| has_field(field_name) | Menentukan apakah bidang dengan nama yang ditentukan sudah ditambahkan ke Formulir. |
| copy_to(array, index) | Menyalin bidang yang ditempatkan pada formulir ke dalam array. |
| flatten() | Menghapus semua bidang formulir dan menempatkan nilainya langsung pada halaman. |
| add_field_appearance(field, page_number, rect) | Menambahkan tampilan tambahan bidang ke halaman tertentu dari dokumen pada lokasi yang ditentukan. |
| get_fields_in_rect(rect) | Mengembalikan bidang di dalam persegi panjang yang ditentukan. |

### Lihat Juga

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

