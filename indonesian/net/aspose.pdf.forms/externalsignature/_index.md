---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Forms.ExternalSignature. Membuat tanda tangan PKCS7 terpisah menggunakan X509Certificate2. Mendukung token kartu pintar usb tanpa kunci privat yang dapat diekspor
type: docs
weight: 5040
url: /id/net/aspose.pdf.forms/externalsignature/
---
## Kelas ExternalSignature

Membuat tanda tangan PKCS#7 terpisah menggunakan X509Certificate2. Mendukung kartu pintar usb, token tanpa kunci privat yang dapat diekspor.

```csharp
public class ExternalSignature : Signature
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | Membuat tanda tangan PKCS#7 `(terpisah)` menggunakan X509Certificate2. Mendukung kartu pintar usb, token tanpa kunci privat yang dapat diekspor. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | Membuat tanda tangan PKCS#7 menggunakan X509Certificate2 sebagai string base64. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | Membuat tanda tangan PKCS#7 `(terpisah)` menggunakan X509Certificate2 sebagai string base64. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | Membuat tanda tangan PKCS#7 terpisah menggunakan X509Certificate2. Mendukung kartu pintar usb, token tanpa kunci privat yang dapat diekspor. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | Membuat tanda tangan PKCS#7 `(terpisah)` menggunakan X509Certificate2. Mendukung kartu pintar usb, token tanpa kunci privat yang dapat diekspor. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Nama orang atau otoritas yang menandatangani dokumen. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Mendapatkan dan mengatur opsi yang berarti apakah harus menghindari memperkirakan panjang tanda tangan. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Array pasangan bilangan bulat (offset byte awal, panjang dalam byte) yang akan menggambarkan rentang byte yang tepat untuk perhitungan digest. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan untuk memverifikasi tanda tangan, misalnya nomor telepon. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Mendapatkan/mengatur penampilan kustom. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Delegasi untuk menandatangani hash dokumen secara kustom. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Waktu penandatanganan. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Mendapatkan atau mengatur panjang default untuk data tanda tangan dalam byte. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Nama host CPU atau lokasi fisik penandatanganan. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Mendapatkan/mengatur pengaturan ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Alasan untuk penandatanganan, seperti (Saya setuju, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Memaksa untuk menampilkan/menghentikan menampilkan properti tanda tangan. Jika ShowProperties adalah true, bidang tanda tangan memiliki format penampilan yang telah ditentukan sebelumnya (string untuk mewakili): ------------------------------------------- Ditandatangani secara digital oleh {subjek sertifikat} Tanggal: {signature.Date} Alasan: {signature.Reason} Lokasi: {signature.Location} ------------------------------------------- di mana {X} adalah placeholder untuk nilai X. Juga tanda tangan dapat memiliki gambar, dalam hal ini string yang terdaftar ditempatkan di atas gambar. ShowProperties adalah true secara default. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Mendapatkan/mengatur pengaturan timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Mendapatkan/mengatur bendera validasi ltv. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Mengambil informasi tentang algoritma tanda tangan yang digunakan dalam tanda tangan. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Memverifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau sebaliknya false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Memverifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau sebaliknya false. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | Sertifikat dengan kunci privat. |

### Lihat Juga

* kelas [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)