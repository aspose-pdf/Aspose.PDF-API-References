---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili penempatan XForm. Jika XForm ditampilkan pada halaman lebih dari 1 kali, semua XFormPlacement yang terkait dengan XForm ini akan memiliki elemen grafis yang sama, tetapi."
type: docs
weight: 70
url: /id/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

Mewakili penempatan XForm. Jika XForm ditampilkan pada halaman lebih dari 1 kali, semua XformPlacement yang terkait dengan XForm ini akan memiliki elemen grafis yang sama, tetapi keadaan grafis yang berbeda.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Menambahkan elemen saat ini pada halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik gunakan Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | Mendapatkan elemen grafis di dalam XForm ini. |
| [getName](#getName--) | Mendapatkan nama XForm. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang pembatas dari GraphicElement. |
| [getXForm](#getXForm--) | Mendapatkan XForm yang terkait dengan XFormPlacement ini. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Menambahkan elemen saat ini pada halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik gunakan Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Mendapatkan elemen grafis di dalam XForm ini.

**Returns:**
Instansi GraphicElementCollection

### getName {#getName--}
```
public final String getName()
```

Mendapatkan nama XForm.

**Returns:**
nilai String

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang pembatas dari GraphicElement.

**Returns:**
Instansi Rectangle

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Mendapatkan XForm yang terkait dengan XFormPlacement ini.

**Returns:**
Instansi XForm

### setPosition {#setPosition-com.aspose.pdf.Point-}
Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini.
