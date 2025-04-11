---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.PageCollection. Koleksi halaman dokumen PDF
type: docs
weight: 8080
url: /id/net/aspose.pdf/pagecollection/
---
## Kelas PageCollection

Koleksi halaman dokumen PDF.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Mendapatkan jumlah halaman dalam dokumen. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca. Selalu mengembalikan false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Mengembalikan true jika objek disinkronkan. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Mendapatkan halaman berdasarkan indeks. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Mendapatkan objek sinkronisasi dari koleksi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Menerima objek pengunjung [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) yang menyediakan fungsionalitas untuk bekerja dengan anotasi. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Menerima objek pengunjung [`ImagePlacementAbsorber`](../imageplacementabsorber/) yang menyediakan fungsionalitas untuk bekerja dengan objek penempatan gambar. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Menerima objek pengunjung [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Menerima objek pengunjung [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Dalam kasus terdapat hanya dua halaman berbeda, ukuran halaman pertama akan digunakan. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Menambahkan semua halaman dari daftar ke koleksi. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Menambahkan halaman ke koleksi. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Menambahkan semua halaman dari array ke koleksi. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Menghapus koleksi halaman. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Menentukan apakah instansi ini mengandung objek tersebut. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Menyalin halaman ke dalam dokumen. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Menghapus semua halaman dari koleksi. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Menghapus halaman yang ditentukan. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Menghapus halaman yang ditentukan yang nomornya ada dalam array. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Menghapus semua bidang yang terletak di halaman dan menempatkan nilai mereka sebagai gantinya. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Menghapus data yang di-cache |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Mengembalikan enumerator halaman. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Mengembalikan indeks dari halaman yang ditentukan. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Menyisipkan halaman kosong ke dalam koleksi pada posisi yang ditentukan. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Dalam kasus terdapat hanya dua halaman berbeda, ukuran halaman pertama akan digunakan. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Menyisipkan halaman dari koleksi ke dalam dokumen. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Menyisipkan halaman ke dalam koleksi halaman di tempat yang ditentukan. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Menyisipkan halaman dari array ke dalam dokumen. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Menghapus item yang ditentukan, melempar NotSupportedException. |

### Lihat Juga

* kelas [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)