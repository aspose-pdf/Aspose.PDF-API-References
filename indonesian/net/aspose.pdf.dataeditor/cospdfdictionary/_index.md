---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.DataEditor.CosPdfDictionary. Kelas untuk mengakses kamus objek
type: docs
weight: 3420
url: /id/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## Kelas CosPdfDictionary

Kelas untuk mengakses kamus objek.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Membuat kamus dari sumber daya. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Koleksi lengkap kunci. Berisi kunci yang dapat diedit dan tidak dapat diedit. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Mendapatkan jumlah elemen yang terdapat dalam `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah `CosPdfDictionary` bersifat hanya-baca. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Mendapatkan atau menetapkan elemen dengan kunci yang ditentukan. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Koleksi kunci yang dapat diedit. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Mendapatkan ICollection yang berisi nilai-nilai dalam `CosPdfDictionary`. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Membuat kamus kosong yang akan dilampirkan ke dokumen. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Membuat kamus kosong yang akan dilampirkan ke halaman. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menetapkan [`ICosPdfPrimitive`](../icospdfprimitive/) ke kamus. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Menetapkan [`ICosPdfPrimitive`](../icospdfprimitive/) ke kamus. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Menghapus semua item dari `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menentukan apakah `CosPdfDictionary` mengandung nilai tertentu. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Menentukan apakah `CosPdfDictionary` mengandung elemen dengan kunci yang ditentukan. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Mengembalikan enumerator yang mengiterasi melalui koleksi. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menghapus kemunculan pertama dari objek tertentu dari `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Menghapus elemen dengan kunci yang ditentukan dari `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Mencoba mengonversi instance ini menjadi [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Mencoba mengonversi instance ini menjadi `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Mencoba mengonversi instance ini menjadi [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Mencoba mengonversi instance ini menjadi [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Mencoba mengonversi instance ini menjadi [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | Untuk akses ke tipe data sederhana seperti string, nama, bool, angka. Mengembalikan null untuk tipe lain. |

### Lihat Juga

* kelas [CosPdfPrimitive](../cospdfprimitive/)
* antarmuka [ICosPdfPrimitive](../icospdfprimitive/)
* ruang nama [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)