---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfXmpMetadata. Kelas untuk manipulasi metadata XMP
type: docs
weight: 4640
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/
---
## Kelas PdfXmpMetadata

Kelas untuk manipulasi metadata XMP.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | Konstruktor untuk PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | Menginisialisasi objek `PdfXmpMetadata` baru berdasarkan *dokumen*. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Mendapatkan jumlah item dalam koleksi. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Mendapatkan facade dokumen yang sedang dikerjakan. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Mendapatkan kamus bidang ekstensi. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Mengembalikan true jika koleksi memiliki ukuran tetap. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Mengembalikan true jika koleksi bersifat hanya-baca. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Mengembalikan true jika koleksi disinkronkan. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Mendapatkan atau mengatur nilai berdasarkan kunci. (2 indeks) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Mendapatkan kunci dari kamus. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Mendapatkan objek sinkronisasi dari koleksi. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Mendapatkan koleksi nilai dalam kamus. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Menambahkan pasangan dengan kunci dan nilai ke dalam kamus. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | Menambahkan nilai ke metadata XMP. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Menambahkan elemen baru ke objek kamus. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Menambahkan elemen baru ke objek kamus. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Menambahkan bidang ekstensi ke dalam metadata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Menginisialisasi facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Menginisialisasi facade. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Menghapus semua elemen dari objek. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Menghapus Aspose.Pdf.Document yang terikat dengan facade. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Memeriksa apakah kamus mengandung properti yang ditentukan. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Memeriksa apakah pasangan kunci-nilai yang ditentukan ada dalam kamus. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Memeriksa apakah kamus mengandung kunci yang ditentukan. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Menentukan apakah kamus ini mengandung kunci yang ditentukan. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Menghapus facade. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Mendapatkan objek enumerator dari kamus. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Mendapatkan URI namespace berdasarkan prefix. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Mendapatkan prefix berdasarkan URI namespace. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Mendapatkan XmpMetadata dari pdf input dalam format xml. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Mendapatkan bagian dari XmpMetadata dari pdf input sesuai dengan nama meta. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Mendaftarkan URI namespace. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Menghapus elemen dengan kunci yang ditentukan. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Menghapus pasangan kunci/nilai dari koleksi. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Menghapus kunci dari kamus. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Menyimpan dokumen PDF ke stream yang ditentukan. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Menyimpan dokumen PDF ke file yang ditentukan. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan. |

### Lihat Juga

* kelas [SaveableFacade](../saveablefacade/)
* kelas [XmpValue](../../aspose.pdf/xmpvalue/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)