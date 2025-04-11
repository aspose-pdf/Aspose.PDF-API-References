---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Annotations.AppearanceDictionary. Kamus penampilan anotasi yang menentukan bagaimana anotasi akan ditampilkan secara visual di halaman
type: docs
weight: 1490
url: /id/net/aspose.pdf.annotations/appearancedictionary/
---
## Kelas AppearanceDictionary

Kamus penampilan anotasi yang menentukan bagaimana anotasi akan ditampilkan secara visual di halaman.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Mendapatkan jumlah elemen yang terdapat dalam kamus. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Mendapatkan nilai yang menunjukkan apakah kamus memiliki ukuran tetap. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah kamus hanya dapat dibaca. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Mendapatkan nilai yang menunjukkan apakah akses ke kamus disinkronkan (aman untuk thread). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Mewakili bentuk yang nyaman untuk mendapatkan aliran penampilan. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Mendapatkan kunci dari kamus. Jika kamus penampilan memiliki subkamus, maka [`Keys`](./keys/) berisi nilai (N&#x7C;R&#x7C;D).state, di mana N - penampilan normal, R - penampilan rollover, D - penampilan turun dan state - nama dari state (misalnya On, Off untuk kotak centang). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke kamus. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Mendapatkan daftar nilai kamus. Koleksi hasil berisi daftar objek XForm. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Menambahkan pasangan dengan kunci dan nilai ke dalam kamus. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Menambahkan X form untuk kunci yang ditentukan. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Menghapus semua elemen dari kamus. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Memeriksa apakah pasangan kunci-nilai yang ditentukan terdapat dalam kamus. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Menentukan apakah kamus ini mengandung kunci yang ditentukan. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Menyalin elemen-elemen dari kamus ke dalam Array, dimulai dari indeks Array tertentu. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Mengembalikan objek IDictionaryEnumerator untuk kamus. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Menghapus pasangan kunci/nilai dari koleksi. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Menghapus kunci dari kamus. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Mencoba untuk menemukan kunci dalam kamus dan mengambil nilai jika ditemukan. |

### Lihat Juga

* kelas [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)