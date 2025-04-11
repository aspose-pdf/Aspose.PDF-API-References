---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Enum LineJoin dari Aspose.Pdf. Operators. Gaya sambungan garis harus menentukan bentuk yang akan digunakan di sudut jalur yang di-stroke
type: docs
weight: 7450
url: /id/net/aspose.pdf.operators/linejoin/
---
## Enumerasi LineJoin

Gaya sambungan garis harus menentukan bentuk yang akan digunakan di sudut jalur yang di-stroke.

```csharp
public enum LineJoin
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| MiterJoin | `0` | Sambungan miter. Tepi luar dari garis untuk dua segmen harus diperpanjang sampai bertemu pada sudut, seperti dalam bingkai gambar. Jika segmen bertemu pada sudut yang terlalu tajam seperti yang ditentukan oleh parameter batas miter (lihat 8.4.3.5, "Batas Miter"), sambungan bevel harus digunakan sebagai gantinya. |
| RoundJoin | `1` | Sambungan bulat. Sebuah busur lingkaran dengan diameter sama dengan lebar garis harus digambar di sekitar titik di mana dua segmen bertemu, menghubungkan tepi luar dari garis untuk dua segmen. Figura berbentuk irisan pai ini harus diisi, menghasilkan sudut yang membulat. |
| BevelJoin | `2` | Sambungan bevel. Dua segmen harus diakhiri dengan tutup ujung (lihat 8.4.3.3, "Gaya Tutup Garis") dan lekukan yang dihasilkan di luar ujung segmen harus diisi dengan segitiga. |

### Lihat Juga

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)