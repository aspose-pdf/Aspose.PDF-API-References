---
title: "Kelas DictionaryEditor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.DataEditor.DictionaryEditor. Kelas untuk mengakses kamus pohon dokumen, kamus dokumen, kamus halaman, kamus sumber daya."
type: docs
weight: 3590
url: /id/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class

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
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Koleksi lengkap kunci. Berisi kunci yang dapat diedit dan yang tidak dapat diedit. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Mendapatkan jumlah elemen yang terdapat dalam `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah `DictionaryEditor` bersifat read-only. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Mendapatkan atau mengatur elemen dengan kunci yang ditentukan. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Koleksi kunci yang dapat diedit. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Mendapatkan ICollection yang berisi nilai-nilai dalam `DictionaryEditor`. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Atur [`ICosPdfPrimitive`](../icospdfprimitive/) ke kamus. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Atur [`ICosPdfPrimitive`](../icospdfprimitive/) ke kamus. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Menghapus semua item dari `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menentukan apakah `DictionaryEditor` berisi nilai tertentu. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Menentukan apakah `DictionaryEditor` berisi elemen dengan kunci yang ditentukan. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Mengembalikan enumerator yang mengiterasi koleksi. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menghapus kemunculan pertama dari objek tertentu dari `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Menghapus elemen dengan kunci yang ditentukan dari `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Untuk mengakses tipe data sederhana seperti string, nama, bool, number. Mengembalikan null untuk tipe lainnya. |

### Lihat Juga

* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


