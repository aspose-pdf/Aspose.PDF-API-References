---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas dasar untuk objek grafik pada halaman."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Mewakili kelas dasar untuk objek grafik pada halaman.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Menambahkan elemen saat ini pada halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik gunakan Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh kelas {@link GraphicElement}. |
| [getMatrix](#getMatrix--) | Mendapatkan matriks elemen grafis. Matriks diatur saat elemen dibuat. Matriks berubah ketika SetPosition() dipanggil. |
| [getOperators](#getOperators--) | Mendapatkan koleksi operator yang mewakili elemen. |
| [getParent](#getParent--) | Mendapatkan {@link XFormPlacement} saat ini di mana elemen berada. |
| [getPosition](#getPosition--) | Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini. Jika Parent #getParent/#setParent(XFormPlacement) tidak null maka elemen memiliki ruang koordinat xForm. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang pembatas dari {@link GraphicElement}. |
| [getSourcePage](#getSourcePage--) | Mendapatkan halaman tempat elemen grafis diekstrak. |
| [remove](#remove--) | Menghapus elemen saat ini dari halaman. Jika ada banyak elemen yang akan dihapus, lebih baik gunakan Page#deleteGraphics(GraphicElementCollection). |
| [saveToSvg](#saveToSvg--) | Mengonversi elemen menjadi satu gambar SVG. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Mengonversi elemen menjadi satu gambar SVG. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini. Jika Parent #getParent/#setParent(XFormPlacement) tidak null maka elemen memiliki ruang koordinat xForm. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Menambahkan elemen saat ini pada halaman. Jika ada banyak elemen yang akan ditambahkan, lebih baik gunakan Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

Melepaskan semua sumber daya yang digunakan oleh kelas {@link GraphicElement}.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Mendapatkan matriks elemen grafis. Matriks diatur saat elemen dibuat. Matriks berubah ketika SetPosition() dipanggil.

**Returns:**
Instansi matriks

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Mendapatkan koleksi operator yang mewakili elemen.

**Returns:**
Daftar instance Operator

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Mendapatkan {@link XFormPlacement} saat ini di mana elemen berada.

**Returns:**
Instansi XFormPlacement

### getPosition {#getPosition--}
```
public Point getPosition()
```

Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini. Jika Parent #getParent/#setParent(XFormPlacement) tidak null maka elemen memiliki ruang koordinat xForm.

**Returns:**
Instansi Point

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

Mendapatkan persegi panjang pembatas dari {@link GraphicElement}.

**Returns:**
Instansi Rectangle

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Mendapatkan halaman tempat elemen grafis diekstrak.

**Returns:**
Instance Page

### remove {#remove--}
```
public final void remove()
```

Menghapus elemen saat ini dari halaman. Jika ada banyak elemen yang akan dihapus, lebih baik gunakan Page#deleteGraphics(GraphicElementCollection).

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Mengonversi elemen menjadi satu gambar SVG.

**Returns:**
String SVG.

### saveToSvg {#saveToSvg-java.lang.String-}
Mengonversi elemen menjadi satu gambar SVG.

**Returns:**
String SVG.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Mendapatkan atau mengatur posisi dalam ruang koordinat saat ini. Jika Parent #getParent/#setParent(XFormPlacement) tidak null maka elemen memiliki ruang koordinat xForm.
