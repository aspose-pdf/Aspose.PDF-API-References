---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili objek penyerap elemen grafik. Melakukan pencarian grafik dan menyediakan akses ke hasil pencarian melalui {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /id/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Mewakili objek absorber elemen grafik. Melakukan pencarian grafik dan menyediakan akses ke hasil pencarian melalui koleksi {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [dispose](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh kelas {@link GraphicsAbsorber}. |
| [getElements](#getElements--) | Mendapatkan koleksi kemunculan pencarian yang disajikan dengan objek {@link GraphicElement}. |
| [resumeUpdate](#resumeUpdate--) | Lanjutkan pembaruan untuk Page#getContents dan semua @link XForm#getContents. Dilakukan untuk meningkatkan kinerja, lihat juga. |
| [suppressUpdate](#suppressUpdate--) | Menekan pembaruan untuk Page#getContents dan semua @link XForm#getContents. Dilakukan untuk meningkatkan kinerja, lihat juga. |
| [visit](#visit-com.aspose.pdf.Page-) | Melakukan pencarian pada halaman yang ditentukan. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

Melepaskan semua sumber daya yang digunakan oleh kelas {@link GraphicsAbsorber}.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Mendapatkan koleksi kemunculan pencarian yang disajikan dengan objek {@link GraphicElement}.

**Returns:**
Instansi GraphicElementCollection

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Lanjutkan pembaruan untuk Page#getContents dan semua @link XForm#getContents. Dilakukan untuk meningkatkan kinerja, lihat juga.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Menekan pembaruan untuk Page#getContents dan semua @link XForm#getContents. Dilakukan untuk meningkatkan kinerja, lihat juga.

### visit {#visit-com.aspose.pdf.Page-}
Melakukan pencarian pada halaman yang ditentukan.
