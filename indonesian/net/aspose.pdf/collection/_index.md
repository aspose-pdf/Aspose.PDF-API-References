---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Collection. Mewakili kelas untuk Koleksi12.3.5
type: docs
weight: 3020
url: /id/net/aspose.pdf/collection/
---
## Kelas Koleksi

Mewakili kelas untuk Koleksi(12.3.5 Koleksi).

```csharp
public class Collection : EmbeddedFileCollection
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Collection](collection/)() | Menginisialisasi objek Koleksi baru. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Mendapatkan jumlah file tersemat dalam koleksi. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Nama file tersemat default. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi ini disinkronkan (aman untuk thread). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Mendapatkan file tersemat berdasarkan indeksnya. (2 pengindeks) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Mengembalikan daftar kunci lampiran file. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Mendapatkan "Skema" dari koleksi dokumen. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Menambahkan spesifikasi file tersemat ke dalam koleksi. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Menambahkan file ke file tersemat dengan kunci yang ditentukan. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Menyalin array objek FileSpecification ke dalam koleksi. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Menghapus semua file tersemat dari dokumen. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Menghapus file tersemat berdasarkan nama. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Menghapus file dari koleksi berdasarkan kuncinya dalam koleksi. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Mengembalikan file tersemat berdasarkan namanya. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Mengembalikan enumerator koleksi. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Mendapatkan koleksi file yang diurutkan sesuai dengan spesifikasi. |

### Lihat Juga

* kelas [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)