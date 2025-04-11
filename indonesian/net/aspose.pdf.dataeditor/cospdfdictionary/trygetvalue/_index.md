---
title: CosPdfDictionary.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: Metode CosPdfDictionary. Untuk akses ke tipe data sederhana seperti string, nama, bool, angka. Mengembalikan null untuk tipe lainnya
type: docs
weight: 170
url: /id/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## Metode CosPdfDictionary.TryGetValue

Untuk akses ke tipe data sederhana seperti string, nama, bool, angka. Mengembalikan null untuk tipe lainnya.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | String | Nilai kunci |
| value | ICosPdfPrimitive& | mengembalikan [`ICosPdfPrimitive`](../../icospdfprimitive/) untuk kunci atau null. |

### Nilai Kembali

Mengembalikan true jika [`ICosPdfPrimitive`](../../icospdfprimitive/) seperti string, nama, bool, angka. Mengembalikan false untuk semua tipe lainnya.

### Lihat Juga

* antarmuka [ICosPdfPrimitive](../../icospdfprimitive/)
* kelas [CosPdfDictionary](../)
* ruang nama [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)