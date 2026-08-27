---
title: "Kelas EncryptionOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Plugins.EncryptionOptions. Mewakili Opsi Enkripsi untuk plugin Security"
type: docs
weight: 8670
url: /id/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions class

Mewakili Opsi Enkripsi untuk plugin [`Security`](../security/).

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Menginisialisasi instance baru dari objek `EncryptionOptions` dengan opsi default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Tutup aliran input setelah operasi selesai. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Tutup aliran output setelah operasi selesai. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Algoritma kriptografi, lihat [`CryptoAlgorithm`](./cryptoalgorithm/) untuk detail. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Izin dokumen, lihat [`Permissions`](../../aspose.pdf/permissions/) untuk detail. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Mengembalikan koleksi data plugin OrganizerOptions. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Mendapatkan koleksi target yang ditambahkan untuk menyimpan hasil operasi. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Password pemilik. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Kata sandi pengguna. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Menambahkan sumber data baru ke koleksi data plugin PdfOrganizer. |

### Lihat Juga

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


