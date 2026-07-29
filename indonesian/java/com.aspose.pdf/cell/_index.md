---
title: "Cell"
linktitle: "Cell"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili sel dari baris tabel."
type: docs
weight: 510
url: /id/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

Mewakili sel dari baris tabel.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Cell](#Cell--) | Menginisialisasi instance baru dari kelas Cell. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Menginisialisasi instance baru dari kelas Cell. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone](#deepClone--) | Gandakan sel. |
| [getAlignment](#getAlignment--) | Mendapatkan perataan. |
| [getBackgroundColor](#getBackgroundColor--) | Mendapatkan warna latar belakang. |
| [getBackgroundImage](#getBackgroundImage--) | Mendapatkan atau mengatur gambar latar belakang |
| [getBackgroundImageFile](#getBackgroundImageFile--) | Mendapatkan berkas gambar latar belakang. |
| [getBorder](#getBorder--) | Mendapatkan border. |
| [getColSpan](#getColSpan--) | Mendapatkan atau mengatur rentang kolom. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Mendapatkan keadaan teks sel default. |
| [getMargin](#getMargin--) | Mendapatkan padding. |
| [getParagraphs](#getParagraphs--) | Mendapatkan teks terformat sel. |
| [getRowSpan](#getRowSpan--) | Mendapatkan rentang baris. |
| [getVerticalAlignment](#getVerticalAlignment--) | Mendapatkan perataan vertikal. |
| [getWidth](#getWidth--) | Mendapatkan lebar kolom. |
| [isNoBorder](#isNoBorder--) | Mendapatkan sel memiliki batas. |
| [isOverrideByFragment](#isOverrideByFragment--) | Mengatur properti TextState sel ditimpa oleh properti TextState TextFragment. |
| [isWordWrapped](#isWordWrapped--) | Mendapatkan pembungkus kata teks sel. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Mengatur perataan. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mendapatkan atau mengatur warna latar belakang. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Mendapatkan atau mengatur gambar latar belakang |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | Mengatur berkas gambar latar belakang. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Mengatur border. |
| [setColSpan](#setColSpan-int-) | Mengatur rentang kolom. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Mengatur status teks sel default. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Mengatur padding. |
| [setNoBorder](#setNoBorder-boolean-) | Mengatur sel memiliki batas. |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | Mengatur properti TextState sel ditimpa oleh properti TextState TextFragment. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Mengatur teks terformat sel. |
| [setRowSpan](#setRowSpan-int-) | Mengatur rentang baris. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mengatur perataan vertikal. |
| [setWidth](#setWidth-double-) | Mengatur lebar kolom. |
| [setWordWrapped](#setWordWrapped-boolean-) | Mengatur pembungkus kata teks sel. |

### Cell {#Cell--}
```
public Cell()
```

Menginisialisasi instance baru dari kelas Cell.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Menginisialisasi instance baru dari kelas Cell.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Gandakan sel.

**Returns:**
Objek yang diklon.

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

Mendapatkan perataan.

**Returns:**
Elemen HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Mendapatkan warna latar belakang.

**Returns:**
objek Color

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Mendapatkan atau mengatur gambar latar belakang

**Returns:**
Instansi gambar

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

Mendapatkan berkas gambar latar belakang.

**Returns:**
Nilai string @deprecated Properti telah diperluas silakan gunakan BackgroundImage

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Mendapatkan border.

**Returns:**
Objek BorderInfo

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

Mendapatkan atau mengatur rentang kolom.

**Returns:**
nilai int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Mendapatkan keadaan teks sel default.

**Returns:**
Objek TextState

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Mendapatkan padding.

**Returns:**
Objek MarginInfo

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Mendapatkan teks terformat sel.

**Returns:**
Objek Paragraphs

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

Mendapatkan rentang baris.

**Returns:**
nilai int

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Mendapatkan perataan vertikal.

**Returns:**
Elemen VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Mendapatkan lebar kolom.

**Returns:**
nilai double

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

Mendapatkan sel memiliki batas.

**Returns:**
nilai boolean

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

Mengatur properti TextState sel ditimpa oleh properti TextState TextFragment.

**Returns:**
nilai boolean

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

Mendapatkan pembungkus kata teks sel.

**Returns:**
nilai boolean

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Mengatur perataan.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mendapatkan atau mengatur warna latar belakang.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Mendapatkan atau mengatur gambar latar belakang

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
Mengatur berkas gambar latar belakang.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Mengatur border.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

Mengatur rentang kolom.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Mengatur status teks sel default.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Mengatur padding.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

Mengatur sel memiliki batas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

Mengatur properti TextState sel ditimpa oleh properti TextState TextFragment.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Mengatur teks terformat sel.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

Mengatur rentang baris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mengatur perataan vertikal.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Mengatur lebar kolom.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

Mengatur pembungkus kata teks sel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
