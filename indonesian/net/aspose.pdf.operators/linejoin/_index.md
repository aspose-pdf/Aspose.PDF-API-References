---
title: "Enum LineJoin"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.Operators.LineJoin. Gaya sambungan garis harus menentukan bentuk yang digunakan pada sudut-sudut jalur yang di-stroke"
type: docs
weight: 7590
url: /id/net/aspose.pdf.operators/linejoin/
---
## LineJoin enumeration

Gaya sambungan garis harus menentukan bentuk yang akan digunakan pada sudut-sudut jalur yang digambar.

```csharp
public enum LineJoin
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| MiterJoin | `0` | Sambungan miter. Tepi luar dari stroke untuk dua segmen akan diperpanjang sampai mereka bertemu pada suatu sudut, seperti pada bingkai gambar. Jika segmen bertemu pada sudut yang terlalu tajam sebagaimana didefinisikan oleh parameter batas miter (lihat 8.4.3.5, "Miter Limit"), sambungan bevel akan digunakan sebagai gantinya. |
| RoundJoin | `1` | Sambungan bulat. Sebuah busur lingkaran dengan diameter yang sama dengan lebar garis akan digambar di sekitar titik di mana dua segmen bertemu, menghubungkan tepi luar goresan untuk kedua segmen. Bentuk seperti irisan pai ini akan diisi, menghasilkan sudut melengkung. |
| BevelJoin | `2` | Sambungan bevel. Kedua segmen akan diselesaikan dengan penutup butt (lihat 8.4.3.3, "Line Cap Style") dan takik yang dihasilkan di luar ujung segmen akan diisi dengan segitiga. |

### Lihat Juga

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


