---
title: "Kelas PdfFileSignature"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.PdfFileSignature. Mewakili kelas untuk menandatangani file pdf dengan sertifikat"
type: docs
weight: 4680
url: /id/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Mewakili kelas untuk menandatangani file pdf dengan sertifikat.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Konstruktor kelas PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Menginisialisasi objek `PdfFileSignature` baru berdasarkan *document*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang diproses. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Mendapatkan flag yang menentukan apakah dokumen bersertifikat atau tidak. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Mendapatkan flag LTV yang diaktifkan. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Mengatur atau mendapatkan tampilan grafis untuk tanda tangan. Nilai properti mewakili nama file gambar. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Mengatur atau mendapatkan tampilan grafis untuk tanda tangan. Nilai properti mewakili aliran gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Mengikat aliran Pdf untuk penyuntingan. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Mengikat file Pdf untuk penyuntingan. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Sertakan dokumen dengan tanda tangan MDP yang ditempatkan pada bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh berisi kamus tanda tangan. Karena dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan; halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Sertakan dokumen dengan tanda tangan MDP. Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan melalui properti yang sesuai dari objek Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Menutup facade. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Memeriksa apakah pdf memiliki tanda tangan digital atau tidak. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Memeriksa apakah pdf memiliki hak penggunaan atau tidak. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Memeriksa apakah tanda tangan mencakup seluruh dokumen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Membuang facade. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Mengekstrak gambar tanda tangan. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Mengembalikan nilai izin akses dokumen bersertifikat berdasarkan tipe tanda tangan MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Mendapatkan nama semua bidang tanda tangan yang kosong. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Mendapatkan informasi kontak dari sebuah tanda tangan. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Mendapatkan tanggal dan waktu tanda tangan. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Mendapatkan lokasi tanda tangan. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Mendapatkan alasan tanda tangan. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Mendapatkan revisi tanda tangan. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Mendapatkan nama semua tanda tangan yang tidak kosong. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Mengambil informasi tentang semua algoritma tanda tangan yang ada dalam dokumen PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Mendapatkan nama orang atau organisasi yang menandatangani dokumen pdf. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Mendapatkan total revisi. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Menghapus tanda tangan berdasarkan nama tanda tangan. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Menghapus tanda tangan berdasarkan nama tanda tangan. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Menghapus semua tanda tangan. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Menghapus entri hak penggunaan. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Menyimpan PDF hasil ke aliran. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Menyimpan PDF hasil ke file. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Mengatur file sertifikat dan kata sandi untuk prosedur penandatanganan. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Tandatangani dokumen dengan tipe tanda tangan yang diberikan yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu tidak boleh berisi kamus tanda tangan. Karena dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menentukan tempat untuk menempelkan tanda tangan, halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan melalui properti yang sesuai dari objek Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Tandatangani dokumen dengan tipe tanda tangan yang diberikan. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Tandatangani dokumen dengan tipe tanda tangan yang diberikan yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu tidak boleh berisi kamus tanda tangan. Karena dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menentukan tempat untuk menempelkan tanda tangan, halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Buat tanda tangan pada dokumen pdf. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Tandatangani dokumen dengan tipe tanda tangan yang diberikan. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Tandatangani dokumen dengan tipe tanda tangan yang diberikan yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, dokumen pdf seharusnya sudah memiliki bidang tanda tangan, halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran. |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | Mengekstrak sertifikat X.509 tunggal dari tanda tangan. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Memeriksa keabsahan sebuah tanda tangan. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | Memeriksa keabsahan sebuah tanda tangan. Verifikasi dilakukan menggunakan sertifikat kunci publik eksternal. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Memeriksa keabsahan sebuah tanda tangan. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | Memeriksa keabsahan sebuah tanda tangan. Verifikasi dilakukan menggunakan sertifikat kunci publik eksternal. |

### Lihat Juga

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


