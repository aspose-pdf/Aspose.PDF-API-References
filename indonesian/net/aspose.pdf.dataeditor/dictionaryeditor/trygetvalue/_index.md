---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: Metode DictionaryEditor. Untuk akses ke tipe data sederhana seperti string, nama, bool, angka. Mengembalikan null untuk tipe lain
type: docs
weight: 150
url: /id/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## Metode DictionaryEditor.TryGetValue

Untuk akses ke tipe data sederhana seperti string, nama, bool, angka. Mengembalikan null untuk tipe lain.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | String | Nilai kunci |
| value | ICosPdfPrimitive& | mengembalikan [`ICosPdfPrimitive`](../../icospdfprimitive/) untuk kunci atau null. |

### Nilai Kembali

Mengembalikan true jika [`ICosPdfPrimitive`](../../icospdfprimitive/) seperti string, nama, bool, angka. Mengembalikan false untuk semua tipe lain.

### Lihat Juga

* antarmuka [ICosPdfPrimitive](../../icospdfprimitive/)
* kelas [DictionaryEditor](../)
* ruang nama [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)