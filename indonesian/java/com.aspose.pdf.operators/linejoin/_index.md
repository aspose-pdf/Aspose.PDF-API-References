---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Gaya sambungan garis harus menentukan bentuk yang akan digunakan pada sudut-sudut jalur yang digambar."
type: docs
weight: 370
url: /id/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

Gaya sambungan garis harus menentukan bentuk yang akan digunakan pada sudut-sudut jalur yang digambar.

## Fields

| Field | Deskripsi |
| --- | --- |
| [BevelJoin](#BevelJoin) | Sambungan bevel. Dua segmen harus diselesaikan dengan butt caps (lihat 8.4.3.3, "Line Cap Style") dan takik yang dihasilkan di luar ujung segmen harus diisi dengan segitiga. |
| [MiterJoin](#MiterJoin) | Sambungan miter. Tepi luar goresan untuk dua segmen harus diperpanjang sampai mereka bertemu pada suatu sudut, seperti pada bingkai gambar. Jika segmen bertemu pada sudut yang terlalu tajam sebagaimana didefinisikan oleh parameter batas miter (lihat 8.4.3.5, "Miter Limit"), sambungan bevel akan digunakan sebagai gantinya. |
| [RoundJoin](#RoundJoin) | Sambungan bulat. Sebuah busur lingkaran dengan diameter sama dengan lebar garis harus digambar di sekitar titik di mana dua segmen bertemu, menghubungkan tepi luar goresan untuk kedua segmen. Bentuk seperti irisan pai ini harus diisi, menghasilkan sudut melengkung. |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

Sambungan bevel. Dua segmen harus diselesaikan dengan butt caps (lihat 8.4.3.3, "Line Cap Style") dan takik yang dihasilkan di luar ujung segmen harus diisi dengan segitiga.

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

Sambungan miter. Tepi luar goresan untuk dua segmen harus diperpanjang sampai mereka bertemu pada suatu sudut, seperti pada bingkai gambar. Jika segmen bertemu pada sudut yang terlalu tajam sebagaimana didefinisikan oleh parameter batas miter (lihat 8.4.3.5, "Miter Limit"), sambungan bevel akan digunakan sebagai gantinya.

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

Sambungan bulat. Sebuah busur lingkaran dengan diameter sama dengan lebar garis harus digambar di sekitar titik di mana dua segmen bertemu, menghubungkan tepi luar goresan untuk kedua segmen. Bentuk seperti irisan pai ini harus diisi, menghasilkan sudut melengkung.
