---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.DataEditor.DictionaryEditor. Kelas untuk mengakses kamus pohon dokumen.
type: docs
weight: 3470
url: /id/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## Kelas DictionaryEditor

Kelas untuk mengakses kamus pohon dokumen (kamus dokumen, kamus halaman, kamus sumber daya).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Koleksi lengkap kunci. Berisi kunci yang dapat diedit dan tidak dapat diedit. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Mendapatkan jumlah elemen yang terdapat dalam `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah `DictionaryEditor` bersifat hanya-baca. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Mendapatkan atau menetapkan elemen dengan kunci yang ditentukan. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Koleksi kunci yang dapat diedit. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Mendapatkan ICollection yang berisi nilai-nilai dalam `DictionaryEditor`. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menetapkan [`ICosPdfPrimitive`](../icospdfprimitive/) ke kamus. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Menetapkan [`ICosPdfPrimitive`](../icospdfprimitive/) ke kamus. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Menghapus semua item dari `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menentukan apakah `DictionaryEditor` mengandung nilai tertentu. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Menentukan apakah `DictionaryEditor` mengandung elemen dengan kunci yang ditentukan. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Mengembalikan enumerator yang mengiterasi melalui koleksi. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menghapus kemunculan pertama dari objek tertentu dari `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Menghapus elemen dengan kunci yang ditentukan dari `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Untuk akses ke tipe data sederhana seperti string, nama, bool, angka. Mengembalikan null untuk tipe lain. |

### Lihat Juga

* antarmuka [ICosPdfPrimitive](../icospdfprimitive/)
* ruang nama [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)