---
title: "PdfFileSecurity"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili proses enkripsi atau dekripsi file PDF dengan kata sandi pemilik atau pengguna, mengubah pengaturan keamanan dan kata sandi."
type: docs
weight: 300
url: /id/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

Mewakili proses enkripsi atau dekripsi file PDF dengan kata sandi pemilik atau pengguna, mengubah pengaturan keamanan dan kata sandi.

Tipe PdfFileSecurity menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | Menginisialisasi instance baru dari kelas PdfFileSecurity |
| PdfFileSecurity(input_file, output_file) | Menginisialisasi instance baru dari kelas PdfFileSecurity |
| PdfFileSecurity() | Inisialisasi objek PdfFileSecurity. |
| PdfFileSecurity(document) | Menginisialisasi instance baru dari kelas PdfFileSecurity |
| PdfFileSecurity(document, output_file) | Menginisialisasi instance baru dari kelas PdfFileSecurity |
| PdfFileSecurity(document, output_stream) | Menginisialisasi instance baru dari kelas PdfFileSecurity |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| allow_exceptions | Jika nilai ini diatur ke true, pengecualian akan dilemparkan saat operasi gagal. Jika tidak, metode mengembalikan false pada kegagalan dan pengecualian terakhir dapat diperiksa dengan properti LastException. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(src_file) | Menginisialisasi facade. |
| bind_pdf(src_stream) | Menginisialisasi facade. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save(dest_file) | Menyimpan dokumen PDF ke file yang ditentukan. |
| save(dest_stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| encrypt_file(user_password, owner_password, privilege, key_size) | Mengenkripsi file Pdf dengan userpassword dan ownerpassword serta mengatur hak akses dokumen.<br/>            Password pengguna dan password pemilik dapat bernilai null atau kosong. Password pemilik akan diganti <br/>            dengan string acak jika password pemilik yang diberikan null atau kosong.<br/>            Melempar pengecualian jika proses gagal. |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | Mengenkripsi file Pdf dengan userpassword dan ownerpassword serta mengatur hak akses dokumen.<br/>            Password pengguna dan password pemilik dapat bernilai null atau kosong. Password pemilik akan diganti <br/>            dengan string acak jika password pemilik yang diberikan null atau kosong.<br/>            Terdapat 6 kombinasi kemungkinan antara nilai KeySize dan Algorithm. <br/>            Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai <br/>            akan dihasilkan jika kit menemukan kombinasi ini.<br/>            Melempar pengecualian jika proses gagal. |
| set_privilege(privilege) | Mengatur keamanan file Pdf dengan password pengguna/pemilik kosong.<br/>            Password pemilik akan ditambahkan dengan string acak.<br/>            Melempar pengecualian jika proses gagal. |
| set_privilege(user_password, owner_password, privilege) | Mengatur keamanan file Pdf dengan password asli.<br/>            Melempar pengecualian jika proses gagal. |
| change_password(owner_password, new_user_password, new_owner_password) | Mengubah password pengguna dan password pemilik menggunakan password pemilik, mempertahankan pengaturan keamanan asli.<br/>             Password pengguna baru dan password pemilik baru dapat bernilai null atau kosong. Password pemilik akan diganti <br/>             dengan string acak jika password pemilik baru null atau kosong.<br/>             Melempar pengecualian jika proses gagal. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Mengubah password pengguna dan password menggunakan password pemilik, memungkinkan untuk mereset keamanan dokumen Pdf.<br/>            Password pengguna baru dan password pemilik baru dapat bernilai null atau kosong. Password pemilik akan diganti <br/>            dengan string acak jika password pemilik baru null atau kosong.<br/>            Melempar pengecualian jika proses gagal. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Mengubah kata sandi pengguna dan kata sandi oleh kata sandi pemilik, memungkinkan untuk mengatur ulang keamanan Pdf documnent.<br/> Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti <br/> dengan string acak jika kata sandi pemilik baru bernilai null atau kosong.<br/> Ada 6 kombinasi kemungkinan nilai KeySize dan Algorithm. <br/> Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai <br/> akan dilemparkan jika kit menemukan kombinasi ini.<br/> Melemparkan pengecualian jika proses gagal. |
| try_change_password(owner_password, new_user_password, new_owner_password) | Mengubah kata sandi pengguna dan kata sandi pemilik dengan kata sandi pemilik, mempertahankan pengaturan keamanan asli.<br/> Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti <br/> Tidak melemparkan pengecualian jika proses gagal.<br/> dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Mengubah kata sandi pengguna dan kata sandi oleh kata sandi pemilik, memungkinkan untuk mengatur ulang keamanan Pdf documnent.<br/> Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti <br/> dengan string acak jika kata sandi pemilik baru bernilai null atau kosong.<br/> Tidak melemparkan pengecualian jika proses gagal. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Mengubah kata sandi pengguna dan kata sandi oleh kata sandi pemilik, memungkinkan untuk mengatur ulang keamanan Pdf documnent.<br/> Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti <br/> dengan string acak jika kata sandi pemilik baru bernilai null atau kosong.<br/> Ada 6 kombinasi kemungkinan nilai KeySize dan Algorithm. <br/> Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai <br/> akan dilemparkan jika kit menemukan kombinasi ini.<br/> Tidak melemparkan pengecualian jika proses gagal. |
| close() | Menutup antarmuka. |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | Mengenkripsi file Pdf dengan userpassword dan ownerpassword dan mengatur hak akses dokumen.<br/> Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti <br/> dengan string acak jika kata sandi pemilik input bernilai null atau kosong.<br/> Tidak melemparkan pengecualian jika proses gagal. |
| decrypt_file(owner_password) | Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. <br/> Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna.<br/> Melemparkan pengecualian jika proses gagal. |
| try_decrypt_file(owner_password) | Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. <br/> Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna.<br/> Tidak melemparkan pengecualian jika proses gagal. |
| try_set_privilege(user_password, owner_password, privilege) | Mengatur keamanan file Pdf dengan kata sandi asli.<br/> Tidak melemparkan pengecualian jika proses gagal. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

