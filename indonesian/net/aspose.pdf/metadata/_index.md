---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Metadata. Memberikan akses ke aliran metadata XMP
type: docs
weight: 6950
url: /id/net/aspose.pdf/metadata/
---
## Kelas Metadata

Memberikan akses ke aliran metadata XMP.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Mendapatkan jumlah elemen dalam koleksi. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Mendapatkan kamus bidang ekstensi. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Memeriksa apakah koleksi memiliki ukuran tetap. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Memeriksa apakah koleksi bersifat hanya-baca. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Memeriksa apakah koleksi disinkronkan. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Mendapatkan atau mengatur data dari metadata. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Mendapatkan koleksi kunci metadata. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Mendapatkan pengelola namespace. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Mendapatkan objek sinkronisasi koleksi. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Mendapatkan nilai dalam metadata. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Menambahkan pasangan dengan kunci dan nilai ke dalam kamus. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Menambahkan nilai ke metadata. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Menambahkan ekstensi pdf ke metadata. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Menambahkan nilai ke metadata. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Menghapus metadata. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Memeriksa apakah pasangan kunci-nilai yang ditentukan ada dalam kamus. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Memeriksa apakah kunci ada dalam metadata. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Menentukan apakah kamus ini mengandung kunci yang ditentukan. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Mengembalikan enumerator kamus. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Mengembalikan URI namespace berdasarkan prefix. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Mengembalikan prefix berdasarkan URI namespace. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Mendaftarkan URI namespace. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Mendaftarkan URI namespace. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Menghapus pasangan kunci/nilai dari koleksi. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Menghapus entri dari metadata. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan. |

### Lihat Juga

* kelas [XmpValue](../xmpvalue/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)