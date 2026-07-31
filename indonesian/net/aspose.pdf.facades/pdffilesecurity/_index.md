---
title: "Kelas PdfFileSecurity"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Facades.PdfFileSecurity kelas. Mewakili proses enkripsi atau dekripsi file Pdf dengan kata sandi pemilik atau pengguna yang mengubah pengaturan keamanan dan kata sandi."
type: docs
weight: 4670
url: /id/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Mewakili enkripsi atau dekripsi file Pdf dengan kata sandi pemilik atau pengguna, mengubah pengaturan keamanan dan kata sandi.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Inisialisasi objek PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Menginisialisasi objek `PdfFileSecurity` baru berdasarkan *document*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Mengembalikan pengecualian yang dilemparkan oleh operasi terakhir. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Menginisialisasi facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Menginisialisasi facade. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Mengubah kata sandi pengguna dan kata sandi pemilik dengan kata sandi pemilik, mempertahankan pengaturan keamanan asli. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Melempar pengecualian jika proses gagal. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Mengubah kata sandi pengguna dan kata sandi dengan kata sandi pemilik, memungkinkan untuk mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Melempar pengecualian jika proses gagal. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Mengubah kata sandi pengguna dan kata sandi dengan kata sandi pemilik, memungkinkan untuk mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Terdapat 6 kombinasi kemungkinan nilai KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan diangkat jika kit menemukan kombinasi ini. Melempar pengecualian jika proses gagal. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Menutup facade. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Melempar pengecualian jika proses gagal. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses dokumen. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik yang dimasukkan bernilai null atau kosong. Melempar pengecualian jika proses gagal. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses dokumen. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik yang dimasukkan bernilai null atau kosong. Terdapat 6 kombinasi kemungkinan nilai KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan diangkat jika kit menemukan kombinasi ini. Melempar pengecualian jika proses gagal. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Mengatur keamanan file Pdf dengan kata sandi pengguna/pemilik kosong. Kata sandi pemilik akan ditambahkan dengan string acak. Melempar pengecualian jika proses gagal. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Mengatur keamanan file Pdf dengan kata sandi asli. Melempar pengecualian jika proses gagal. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Mengubah kata sandi pengguna dan kata sandi pemilik dengan kata sandi pemilik, mempertahankan pengaturan keamanan asli. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Mengubah kata sandi pengguna dan kata sandi dengan kata sandi pemilik, memungkinkan untuk mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Mengubah kata sandi pengguna dan kata sandi oleh kata sandi pemilik, memungkinkan mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Ada 6 kombinasi kemungkinan nilai KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan dilempar jika kit menemukan kombinasi ini. Tidak melempar pengecualian jika proses gagal. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Tidak melempar pengecualian jika proses gagal. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Mengenkripsi file Pdf dengan userpassword dan ownerpassword serta mengatur hak istimewa dokumen untuk akses. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik masukan bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Mengatur keamanan file Pdf dengan kata sandi asli. Tidak melempar pengecualian jika proses gagal. |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


