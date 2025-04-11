---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.FileSpecification. Kelas yang mewakili file yang disematkan
type: docs
weight: 4850
url: /id/net/aspose.pdf/filespecification/
---
## Kelas FileSpecification

Kelas yang mewakili file yang disematkan.

```csharp
public sealed class FileSpecification : IDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Membuat spesifikasi file kosong yang baru. |
| [FileSpecification](filespecification/#constructor_3)(string) | Konstruktor untuk FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Konstruktor untuk spesifikasi file. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Konstruktor untuk FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Konstruktor untuk FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Konstruktor untuk FileSpecification. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Hubungan file yang terkait. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Mendapatkan item koleksi dari spesifikasi file. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Mendapatkan atau mengatur file konten. Properti ini mengembalikan data yang dimuat dalam memori yang dapat menyebabkan pengecualian Out of memory untuk data besar. Untuk mengurangi penggunaan memori, silakan gunakan StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Mendapatkan atau mengatur teks yang terkait dengan spesifikasi file. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Mendapatkan atau mengatur format pengkodean. Nilai yang mungkin: Zip - file dikompresi dengan ZIP, None - file tidak dikompresi. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Mendapatkan payload terenkripsi. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Mendapatkan atau mengatur nama sistem file. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Jika true, konten file akan disertakan dalam spesifikasi file. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Mendapatkan subtipe dari file yang disematkan |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Mendapatkan atau mengatur nama spesifikasi file. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Mendapatkan parameter file. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Mendapatkan konten file sebagai stream. Konten tidak dimuat ke dalam memori yang memungkinkan untuk mengurangi penggunaan memori. Namun, stream ini tidak mendukung pemposisian dan properti Length. Jika Anda memerlukan fitur ini, silakan gunakan properti Contents sebagai gantinya. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Mendapatkan atau mengatur nama unicode spesifikasi file. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Menghapus konten. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Mendapatkan parameter spesifik aplikasi. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Mengatur parameter spesifik aplikasi. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)