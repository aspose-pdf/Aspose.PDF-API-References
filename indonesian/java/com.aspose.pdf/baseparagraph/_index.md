---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili objek dasar abstrak yang dapat ditambahkan ke halaman (doc.Paragraphs.Add())."
type: docs
weight: 280
url: /id/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

Mewakili objek dasar abstrak yang dapat ditambahkan ke halaman (doc.Paragraphs.Add()).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone](#deepClone--) | Mengkloning instansi ini. Metode virtual. Selalu mengembalikan null. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Mendapatkan perataan horizontal paragraf |
| [getHyperlink](#getHyperlink--) | / * / * Mendapatkan atau mengatur apakah paragraf adalah catatan kaki. Default adalah false.(untuk pembuatan pdf) / * / * |
| [getMargin](#getMargin--) | Mendapatkan margin luar untuk paragraf (untuk pembuatan pdf) |
| [getVerticalAlignment](#getVerticalAlignment--) | Mendapatkan perataan vertikal paragraf |
| [getZIndex](#getZIndex--) | Mendapatkan nilai int yang menunjukkan urutan Z (Z-order) grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false.(untuk pembuatan pdf) |
| [isInLineParagraph](#isInLineParagraph--) | Mendapatkan apakah paragraf adalah inline. Default adalah false.(untuk pembuatan pdf) |
| [isInNewPage](#isInNewPage--) | Mendapatkan nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Default adalah false. (untuk pembuatan pdf) |
| [isKeptWithNext](#isKeptWithNext--) | Mendapatkan nilai boolean yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Default adalah false. (untuk pembuatan pdf) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false.(untuk pembuatan pdf) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Mengatur perataan horizontal paragraf |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Mengatur hyperlink (untuk pembuat pdf). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | Mengatur paragraf menjadi inline. Default adalah false. (untuk pembuatan pdf) |
| [setInNewPage](#setInNewPage-boolean-) | Mengatur nilai boolean yang memaksa paragraf ini dihasilkan pada halaman baru. Default adalah false. (untuk pembuatan pdf) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | Mengatur nilai boolean yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Default adalah false. (untuk pembuatan pdf) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Mengatur margin luar untuk paragraf (untuk pembuatan pdf) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mengatur perataan vertikal paragraf |
| [setZIndex](#setZIndex-int-) | Mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Mengkloning instansi ini. Metode virtual. Selalu mengembalikan null.

**Returns:**
Null

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Mendapatkan perataan horizontal paragraf

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * Mendapatkan atau mengatur apakah paragraf adalah catatan kaki. Default adalah false.(untuk pembuatan pdf) / * / *

**Returns:**
nilai boolean /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Mendapatkan margin luar untuk paragraf (untuk pembuatan pdf)

**Returns:**
nilai MarginInfo

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Mendapatkan perataan vertikal paragraf

**Returns:**
Elemen VerticalAlignment @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

Mendapatkan nilai int yang menunjukkan urutan Z (Z-order) grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman.

**Returns:**
nilai int

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false.(untuk pembuatan pdf)

**Returns:**
nilai boolean

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

Mendapatkan apakah paragraf adalah inline. Default adalah false.(untuk pembuatan pdf)

**Returns:**
nilai boolean

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Mendapatkan nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Default adalah false. (untuk pembuatan pdf)

**Returns:**
nilai boolean

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

Mendapatkan nilai boolean yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Default adalah false. (untuk pembuatan pdf)

**Returns:**
nilai boolean

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Default adalah false.(untuk pembuatan pdf)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Mengatur perataan horizontal paragraf

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Mengatur hyperlink (untuk pembuat pdf).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

Mengatur paragraf menjadi inline. Default adalah false. (untuk pembuatan pdf)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Mengatur nilai boolean yang memaksa paragraf ini dihasilkan pada halaman baru. Default adalah false. (untuk pembuatan pdf)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

Mengatur nilai boolean yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Default adalah false. (untuk pembuatan pdf)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Mengatur margin luar untuk paragraf (untuk pembuatan pdf)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mengatur perataan vertikal paragraf

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

Mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif akan ditempatkan di belakang teks pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
