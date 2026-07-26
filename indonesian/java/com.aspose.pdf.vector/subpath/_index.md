---
title: "SubPath"
linktitle: "SubPath"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili objek grafik vektor pada halaman. Pada dasarnya, objek grafik vektor direpresentasikan oleh dua grup SubPath. Salah satunya direpresentasikan oleh sekumpulan garis dan."
type: docs
weight: 60
url: /id/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Mewakili objek grafik vektor pada halaman. Pada dasarnya, objek grafik vektor direpresentasikan oleh dua kelompok SubPath. Salah satunya direpresentasikan oleh sekumpulan garis dan kurva. Yang lainnya ditampilkan sebagai persegi panjang dan kadang dapat membingungkan. Biasanya itu adalah area persegi panjang yang memiliki warna, tetapi sangat sering persegi panjang ini ditempatkan di awal halaman dan mendefinisikan seluruh ruang halaman dengan warna putih. Jadi Anda mendapatkan SubPath, tetapi secara visual Anda hanya melihat teks pada halaman.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang pembatas dari GraphicElement. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang pembatas dari GraphicElement.

**Returns:**
Instansi Rectangle
