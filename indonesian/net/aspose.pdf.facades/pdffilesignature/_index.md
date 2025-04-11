---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfFileSignature. Mewakili kelas untuk menandatangani file pdf dengan sertifikat
type: docs
weight: 4560
url: /id/net/aspose.pdf.facades/pdffilesignature/
---
## Kelas PdfFileSignature

Mewakili kelas untuk menandatangani file pdf dengan sertifikat.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Konstruktor kelas PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Menginisialisasi objek `PdfFileSignature` baru berdasarkan *dokumen*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Mendapatkan flag yang menentukan apakah dokumen telah disertifikasi atau tidak. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Mendapatkan flag LTV yang diaktifkan. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Mengatur atau mendapatkan tampilan grafis untuk tanda tangan. Nilai properti mewakili nama file gambar. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Mengatur atau mendapatkan tampilan grafis untuk tanda tangan. Nilai properti mewakili aliran gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Mengikat aliran Pdf untuk pengeditan. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Mengikat file Pdf untuk pengeditan. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Menyertifikasi dokumen dengan tanda tangan MDP yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh mengandung kamus tanda tangan. Dengan demikian, dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Menyertifikasi dokumen dengan tanda tangan MDP. Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan oleh properti yang sesuai dari objek Tanda Tangan sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Menutup facade. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Memeriksa apakah pdf memiliki tanda tangan digital atau tidak. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Memeriksa apakah pdf memiliki hak penggunaan atau tidak. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Memeriksa apakah tanda tangan mencakup seluruh dokumen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Menghapus facade. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Mengekstrak sertifikat X.509 tunggal dari tanda tangan sebagai aliran. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Mengekstrak gambar tanda tangan. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Mengembalikan nilai izin akses dokumen yang disertifikasi berdasarkan jenis tanda tangan MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Mendapatkan nama semua bidang tanda tangan kosong. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Mendapatkan informasi kontak dari sebuah tanda tangan. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Mendapatkan tanggal dan waktu tanda tangan. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Mendapatkan lokasi dari sebuah tanda tangan. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Mendapatkan alasan dari sebuah tanda tangan. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Mendapatkan revisi dari sebuah tanda tangan. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Mendapatkan nama semua tanda tangan yang tidak kosong. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Mengambil informasi tentang semua algoritma tanda tangan yang ada dalam dokumen PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Mendapatkan nama orang atau organisasi yang menandatangani dokumen pdf. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Mendapatkan total revisi. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Menghapus tanda tangan sesuai dengan nama tanda tangan. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Menghapus tanda tangan sesuai dengan nama tanda tangan. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Menghapus semua tanda tangan. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Menghapus entri hak penggunaan. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Menyimpan PDF hasil ke aliran. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Menyimpan PDF hasil ke file. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Mengatur file sertifikat dan kata sandi untuk rutinitas penandatanganan. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Menandatangani dokumen dengan jenis tanda tangan yang diberikan yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh mengandung kamus tanda tangan. Dengan demikian, dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan oleh properti yang sesuai dari objek Tanda Tangan sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Menandatangani dokumen dengan jenis tanda tangan yang diberikan. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Menandatangani dokumen dengan jenis tanda tangan yang diberikan yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh mengandung kamus tanda tangan. Dengan demikian, dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Membuat tanda tangan pada dokumen pdf. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Menandatangani dokumen dengan jenis tanda tangan yang diberikan. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Menandatangani dokumen dengan jenis tanda tangan yang diberikan yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, dokumen pdf harus sudah memiliki bidang tanda tangan, halaman dan persegi panjang yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Memeriksa keabsahan sebuah tanda tangan. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Memeriksa keabsahan sebuah tanda tangan. |

### Lihat Juga

* kelas [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)