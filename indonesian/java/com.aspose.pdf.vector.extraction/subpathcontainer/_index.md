---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas kontainer untuk elemen grafis."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Mewakili kelas kontainer untuk elemen grafis.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Membuat instance kelas kontainer untuk elemen grafis. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Membuat instance kelas kontainer untuk elemen grafis. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Membuat instance kelas kontainer untuk elemen grafis. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Membuat instance kelas kontainer untuk elemen grafis. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Membuat instance kelas kontainer untuk elemen grafis. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | Menghitung jarak antara dua kontainer. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Membandingkan objek SubPathContainer saat ini dengan objek SubPathContainer lainnya dan mengembalikan integer yang menunjukkan apakah objek saat ini lebih kecil, sama, atau lebih besar dari objek lainnya. Objek dibandingkan berdasarkan ID numeriknya. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Menghitung jarak antara kontainer ini dan kontainer lain. |
| [getGraphElement](#getGraphElement--) | Mendapatkan elemen grafis yang terkandung. |
| [getId](#getId--) | Mendapatkan Id dari SubPathContainer. Id diperlukan untuk memudahkan debugging dan penyortiran elemen selama rendering. |
| [getRect](#getRect--) | Mewakili persegi panjang elemen yang terkandung. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Membuat instance kelas kontainer untuk elemen grafis.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Membuat instance kelas kontainer untuk elemen grafis.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Membuat instance kelas kontainer untuk elemen grafis.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Membuat instance kelas kontainer untuk elemen grafis.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Membuat instance kelas kontainer untuk elemen grafis.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
Menghitung jarak antara dua kontainer.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Membandingkan objek SubPathContainer saat ini dengan objek SubPathContainer lainnya dan mengembalikan integer yang menunjukkan apakah objek saat ini lebih kecil, sama, atau lebih besar dari objek lainnya. Objek dibandingkan berdasarkan ID numeriknya.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Menghitung jarak antara kontainer ini dan kontainer lain.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

Mendapatkan elemen grafis yang terkandung.

**Returns:**
Instansi GraphicElement

### getId {#getId--}
```
public final int getId()
```

Mendapatkan Id dari SubPathContainer. Id diperlukan untuk memudahkan debugging dan penyortiran elemen selama rendering.

**Returns:**
nilai int

### getRect {#getRect--}
```
public final Rectangle getRect()
```

Mewakili persegi panjang elemen yang terkandung.

**Returns:**
Instansi Rectangle

### toString {#toString--}
```
public String toString()
```

{@code }
