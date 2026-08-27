---
title: "Kelas OutlineCollection"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.OutlineCollection. Mewakili hierarki outline dokumen"
type: docs
weight: 8140
url: /id/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

Mewakili hierarki outline dokumen.

```csharp
public sealed class OutlineCollection : Outlines
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Jumlah item dalam koleksi. Harap jangan bingungkan dengan VisibleCount: VisibleCount mendapatkan jumlah item outline yang terlihat pada semua tingkat. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Mendapatkan item outline yang mewakili item tingkat atas pertama dalam outline. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi ini disinkronkan (aman untuk thread). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Mendapatkan item outline dari koleksi berdasarkan indeks. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Mendapatkan item outline yang mewakili item tingkat atas terakhir dalam outline. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi ini. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Count adalah jumlah dari jumlah item outline turunan yang terlihat pada semua tingkat. Catatan: harap jangan bingungkan dengan Count yang merupakan jumlah item dalam koleksi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Menambahkan item outline ke koleksi. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Mengosongkan semua item dari koleksi. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Memeriksa apakah koleksi berisi item yang diberikan. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Menyalin item outline ke System.Array, mulai dari indeks System.Array tertentu. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Menghapus semua item outline dari outline dokumen. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Menghapus item outline dengan judul yang ditentukan dari outline dokumen. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Mengembalikan enumerator yang mengiterasi koleksi. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Menghapus item berdasarkan indeks. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Selalu melempar NotImplementedException |

### Lihat Juga

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


