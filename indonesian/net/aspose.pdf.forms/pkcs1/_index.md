---
title: Class PKCS1
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Forms.PKCS1. Mewakili objek tanda tangan terkait standar PKCS1. Algoritma enkripsi RSA dan metode digest SHA1 digunakan untuk penandatanganan
type: docs
weight: 5170
url: /id/net/aspose.pdf.forms/pkcs1/
---
## Kelas PKCS1

Mewakili objek tanda tangan terkait standar PKCS#1. Algoritma enkripsi RSA dan metode digest SHA-1 digunakan untuk penandatanganan.

```csharp
public sealed class PKCS1 : Signature
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PKCS1](pkcs1/#constructor)() | Menginisialisasi instance baru dari kelas `PKCS1`. |
| [PKCS1](pkcs1/#constructor_1)(Stream) | Menginisialisasi instance baru dari kelas `PKCS1`. |
| [PKCS1](pkcs1/#constructor_2)(Stream, string) | Menginisialisasi instance baru dari kelas `PKCS1`. |
| [PKCS1](pkcs1/#constructor_3)(string, string) | Menginisialisasi instance baru dari kelas `PKCS1`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Nama orang atau otoritas yang menandatangani dokumen. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Mendapatkan dan mengatur opsi yang berarti apakah harus menghindari memperkirakan panjang tanda tangan. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Sebuah array pasangan bilangan bulat (offset byte awal, panjang dalam byte) yang akan menggambarkan rentang byte yang tepat untuk perhitungan digest. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan untuk memverifikasi tanda tangan, misalnya nomor telepon. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Mendapatkan/mengatur penampilan kustom. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Delegasi untuk menandatangani hash dokumen secara kustom. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Waktu penandatanganan. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Mendapatkan atau mengatur panjang default untuk data tanda tangan dalam byte. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Nama host CPU atau lokasi fisik penandatanganan. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Mendapatkan/mengatur pengaturan ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Alasan untuk penandatanganan, seperti (Saya setuju, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Memaksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties adalah true, bidang tanda tangan memiliki format penampilan yang telah ditentukan sebelumnya (string untuk mewakili): ------------------------------------------- Ditandatangani secara digital oleh {subjek sertifikat} Tanggal: {signature.Date} Alasan: {signature.Reason} Lokasi: {signature.Location} ------------------------------------------- di mana {X} adalah placeholder untuk nilai X. Juga tanda tangan dapat memiliki gambar, dalam hal ini string yang terdaftar ditempatkan di atas gambar. ShowProperties adalah true secara default. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Mendapatkan/mengatur pengaturan timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Mendapatkan/mengatur flag validasi ltv. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Mengambil informasi tentang algoritma tanda tangan yang digunakan dalam tanda tangan. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Memverifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau sebaliknya false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Memverifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau sebaliknya false. |

### Lihat Juga

* kelas [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)