---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.OutlineItemCollection. Mewakili entri outline dalam hierarki outline dokumen PDF
type: docs
weight: 8010
url: /id/net/aspose.pdf/outlineitemcollection/
---
## Kelas OutlineItemCollection

Mewakili entri outline dalam hierarki outline dokumen PDF.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Menginisialisasi instance item outline menggunakan objek hierarki root. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Mendapatkan atau mengatur aksi untuk item outline ini. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Mendapatkan atau mengatur flag tebal untuk teks judul item outline ini |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Mendapatkan atau mengatur warna untuk teks judul item outline ini. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Jumlah item dalam koleksi. Harap jangan bingung dengan VisibleCount: VisibleCount mendapatkan jumlah item outline yang terlihat di semua level. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Mendapatkan atau mengatur tujuan untuk item outline ini. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Mendapatkan item outline yang mewakili item tingkat atas pertama dalam hierarki outline. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Memeriksa apakah item outline mewakili item berikutnya relatif terhadap item ini dalam hierarki outline. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi ini disinkronkan (aman untuk thread). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Mendapatkan atau mengatur flag miring untuk teks judul item outline ini |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Mendapatkan item outline dari koleksi menggunakan indeks. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Mendapatkan item outline yang mewakili item tingkat atas terakhir dalam hierarki outline. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Mendapatkan level hierarki item outline. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Mendapatkan item outline yang mewakili item berikutnya relatif terhadap item ini dalam hierarki outline. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Mendapatkan atau mengatur status terbuka (true/false) untuk item outline. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Mendapatkan objek induk dari item outline ini dalam hierarki outline. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Mendapatkan item outline yang mewakili item sebelumnya relatif terhadap item ini dalam hierarki outline. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi ini. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Mendapatkan atau mengatur judul untuk item outline ini. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Mendapatkan total jumlah item outline di semua level dalam hierarki outline dokumen. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Menambahkan item outline ke koleksi. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Menghapus semua item dari koleksi. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Memeriksa apakah koleksi mengandung item yang diberikan. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Menyalin entri outline ke dalam System.Array, dimulai dari indeks System.Array tertentu. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Menghapus item outline ini dari hierarki outline dokumen. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Menghapus entri outline dengan nama yang ditentukan dari hierarki outline dokumen. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Mengembalikan enumerator yang mengiterasi melalui koleksi. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Menyisipkan item outline ke dalam koleksi di tempat yang ditentukan. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Menghapus item berdasarkan indeks. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Menghapus item koleksi outline. |

### Lihat Juga

* kelas [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)