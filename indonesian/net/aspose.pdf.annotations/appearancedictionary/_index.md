---
title: "Kelas AppearanceDictionary"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Annotations.AppearanceDictionary. Kamus tampilan anotasi yang menentukan bagaimana anotasi akan ditampilkan secara visual pada halaman."
type: docs
weight: 1580
url: /id/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

Kamus tampilan anotasi yang menentukan bagaimana anotasi akan ditampilkan secara visual pada halaman.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Mendapatkan jumlah elemen yang terdapat dalam kamus. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Mendapatkan nilai yang menunjukkan apakah kamus memiliki ukuran tetap. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah kamus bersifat hanya-baca. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Mendapatkan nilai yang menunjukkan apakah akses ke kamus disinkronkan (aman untuk thread). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Mewakili bentuk yang nyaman untuk mendapatkan aliran tampilan. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Mendapatkan kunci kamus. Jika kamus tampilan memiliki subkamus, maka [`Keys`](./keys/) berisi nilai (N&#x7C;R&#x7C;D).state, di mana N - tampilan normal, R - tampilan rollover, D - tampilan turun dan state - nama status (misalnya On, Off untuk kotak centang). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke kamus. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Mendapatkan daftar nilai kamus. Koleksi hasil berisi daftar objek XForm. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Menambahkan pasangan kunci dan nilai ke dalam kamus. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Tambahkan X form untuk kunci yang ditentukan. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Menghapus semua elemen dari kamus. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Memeriksa apakah pasangan kunci-nilai yang ditentukan terdapat dalam kamus. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Menentukan apakah kamus ini berisi kunci yang ditentukan. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Menyalin elemen kamus ke Array, mulai dari indeks Array tertentu. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Mengembalikan objek IDictionaryEnumerator untuk kamus. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Menghapus pasangan kunci/nilai dari koleksi. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Menghapus kunci dari kamus. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan. |

### Lihat Juga

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


