---
title: "Kelas CosPdfDictionary"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.DataEditor.CosPdfDictionary. Kelas untuk mengakses kamus objek"
type: docs
weight: 3540
url: /id/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class

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
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Koleksi lengkap kunci. Berisi kunci yang dapat diedit dan yang tidak dapat diedit. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Mendapatkan jumlah elemen yang terdapat dalam `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah `CosPdfDictionary` bersifat read-only. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Mendapatkan atau mengatur elemen dengan kunci yang ditentukan. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Koleksi kunci yang dapat diedit. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Mendapatkan ICollection yang berisi nilai-nilai dalam `CosPdfDictionary`. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Membuat kamus kosong yang akan dilampirkan ke dokumen. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Membuat kamus kosong yang akan dilampirkan ke halaman. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Atur [`ICosPdfPrimitive`](../icospdfprimitive/) ke kamus. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Atur [`ICosPdfPrimitive`](../icospdfprimitive/) ke kamus. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Menghapus semua item dari `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menentukan apakah `CosPdfDictionary` berisi nilai tertentu. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Menentukan apakah `CosPdfDictionary` berisi elemen dengan kunci yang ditentukan. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Mengembalikan enumerator yang mengiterasi koleksi. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Menghapus kemunculan pertama dari objek tertentu dari `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Menghapus elemen dengan kunci yang ditentukan dari `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Mencoba meng-cast instance ini ke [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Mencoba meng-cast instance ini ke `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Mencoba meng-cast instance ini ke [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Mencoba meng-cast instance ini ke [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Mencoba meng-cast instance ini ke [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | Untuk mengakses tipe data sederhana seperti string, nama, bool, number. Mengembalikan null untuk tipe lainnya. |

### Lihat Juga

* class [CosPdfPrimitive](../cospdfprimitive/)
* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


