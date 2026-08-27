---
title: "Kelas Signature"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Forms.Signature. Kelas abstrak yang mewakili objek tanda tangan dalam dokumen pdf. Tanda tangan adalah bidang dengan nilai objek tanda tangan yang terakhir berisi data yang digunakan untuk memverifikasi keabsahan dokumen."
type: docs
weight: 5390
url: /id/net/aspose.pdf.forms/signature/
---
## Signature class

Kelas abstrak yang mewakili objek tanda tangan dalam dokumen pdf. Tanda tangan adalah bidang dengan nilai objek tanda tangan, yang terakhir berisi data yang digunakan untuk memverifikasi keabsahan dokumen.

```csharp
public abstract class Signature
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Signature](signature/#constructor)() | Menginisialisasi instance baru dari kelas `Signature`. |
| [Signature](signature/#constructor_1)(Stream, string) | Menginisialisasi instance baru dari kelas `Signature`. |
| [Signature](signature/#constructor_2)(string, string) | Menginisialisasi instance baru dari kelas `Signature`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Nama orang atau otoritas yang menandatangani Document. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Mendapatkan dan mengatur opsi yang berarti apakah menghindari perkiraan panjang tanda tangan. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Array pasangan integer (offset byte mulai, panjang dalam byte) yang harus menggambarkan rentang byte yang tepat untuk perhitungan digest. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informasi yang diberikan oleh penandatangan untuk memungkinkan penerima menghubungi penandatangan guna memverifikasi tanda tangan, misalnya nomor telepon. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Mendapatkan/mengatur tampilan khusus. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Delegasi untuk menandatangani hash dokumen secara khusus. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Waktu penandatanganan. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Mendapatkan atau mengatur panjang default untuk data tanda tangan dalam byte. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Nama host CPU atau lokasi fisik penandatanganan. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Mendapatkan/mengatur pengaturan ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Alasan penandatanganan, seperti (I agree, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Paksa untuk menampilkan/menyembunyikan properti tanda tangan. Jika ShowProperties bernilai true, bidang tanda tangan memiliki format tampilan yang telah ditentukan (string untuk merepresentasikan): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- dimana {X} adalah placeholder untuk nilai X. Juga tanda tangan dapat memiliki gambar, dalam kasus ini string yang terdaftar ditempatkan di atas gambar. ShowProperties bernilai true secara default. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Mendapatkan/mengatur pengaturan timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Mendapatkan/mengatur flag validasi ltv. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Mengambil informasi tentang algoritma tanda tangan yang digunakan dalam tanda tangan. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | Verifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau false sebaliknya. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | Verifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau false sebaliknya. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_2)(X509Certificate2, ValidationOptions, out ValidationResult) | Verifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau false sebaliknya. Verifikasi dilakukan menggunakan sertifikat kunci publik eksternal. |

### Lihat Juga

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


