---
title: Class DestinationCollection
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.DestinationCollection. Kelas ini mewakili koleksi semua tujuan lihat 12.3.2.3 "Named Destinations" dan lihat 7.7.4 "Name Dictionary" dalam dokumen pdf
type: docs
weight: 3510
url: /id/net/aspose.pdf/destinationcollection/
---
## Kelas DestinationCollection

Kelas ini mewakili koleksi semua tujuan (a name tree mapping name strings to destinations (lihat 12.3.2.3, "Named Destinations") dan (lihat 7.7.4, "Name Dictionary")) dalam dokumen pdf.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Mendapatkan jumlah elemen yang terdapat dalam koleksi. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Mendapatkan objek tujuan berdasarkan indeks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Menambahkan item yang ditentukan. Koleksi bersifat hanya-baca. Selalu melempar pengecualian NotSupportedException. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | Koleksi bersifat hanya-baca. Selalu melempar pengecualian NotSupportedException. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Menentukan apakah instansi ini mengandung objek tersebut. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Mengembalikan enumerator. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Mengembalikan tujuan eksplisit berdasarkan nama. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Mengembalikan nomor halaman tujuan berdasarkan nama. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Mengembalikan indeks tujuan dalam koleksi. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Menghapus item yang ditentukan. Koleksi bersifat hanya-baca. Selalu melempar pengecualian NotSupportedException. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)