---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili elemen struktur TR dalam struktur logis tabel."
type: docs
weight: 240
url: /id/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

Mewakili elemen struktur TR dalam struktur logis tabel.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | konstruktor hanya untuk penggunaan internal |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [createTD](#createTD--) | Membuat {@link TableTHElement} dan menambahkannya ke tabel saat ini. |
| [createTH](#createTH--) | Membuat {@link TableTHElement} dan menambahkannya ke tabel saat ini. |
| [getBackgroundColor](#getBackgroundColor--) | Mendapatkan atau mengatur warna latar belakang baris. |
| [getBorder](#getBorder--) | Mendapatkan atau mengatur batas baris. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Mendapatkan batas sel default. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Mendapatkan atau mengatur margin default untuk sel baris. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Mendapatkan atau mengatur keadaan teks default untuk sel baris |
| [getFixedRowHeight](#getFixedRowHeight--) | Mendapatkan tinggi baris tetap - baris dapat memiliki tinggi tetap. |
| [getMinRowHeight](#getMinRowHeight--) | Mendapatkan tinggi untuk baris. |
| [getVerticalAlignment](#getVerticalAlignment--) | Mendapatkan atau mengatur perataan vertikal. |
| [isInNewPage](#isInNewPage--) | Mendapatkan apakah baris tetap berada di halaman baru - halaman dengan properti ini harus dicetak ke halaman berikutnya Default false. |
| [isRowBroken](#isRowBroken--) | Mendapatkan apakah baris dapat dipotong antara dua halaman. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mendapatkan atau mengatur warna latar belakang baris. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Mendapatkan atau mengatur batas baris. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Mendapatkan batas sel default. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Mendapatkan atau mengatur margin default untuk sel baris. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Mendapatkan atau mengatur keadaan teks default untuk sel baris |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Mendapatkan tinggi baris tetap - baris dapat memiliki tinggi tetap. |
| [setInNewPage](#setInNewPage-boolean-) | Mendapatkan apakah baris tetap berada di halaman baru - halaman dengan properti ini harus dicetak ke halaman berikutnya Default false. |
| [setMinRowHeight](#setMinRowHeight-double-) | Mendapatkan tinggi untuk baris. |
| [setRowBroken](#setRowBroken-boolean-) | Mendapatkan apakah baris dapat dipotong antara dua halaman. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mendapatkan atau mengatur perataan vertikal. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
konstruktor hanya untuk penggunaan internal

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

Membuat {@link TableTHElement} dan menambahkannya ke tabel saat ini.

**Returns:**
Elemen struktur dibuat.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

Membuat {@link TableTHElement} dan menambahkannya ke tabel saat ini.

**Returns:**
Elemen struktur dibuat.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Mendapatkan atau mengatur warna latar belakang baris.

**Returns:**
Instansi Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Mendapatkan atau mengatur batas baris.

**Returns:**
Instansi BorderInfo

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Mendapatkan batas sel default.

**Returns:**
Instansi BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Mendapatkan atau mengatur margin default untuk sel baris.

**Returns:**
Instansi MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Mendapatkan atau mengatur keadaan teks default untuk sel baris

**Returns:**
instansi TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

Mendapatkan tinggi baris tetap - baris dapat memiliki tinggi tetap.

**Returns:**
nilai double

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

Mendapatkan tinggi untuk baris.

**Returns:**
nilai double

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Mendapatkan atau mengatur perataan vertikal.

**Returns:**
Elemen VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

Mendapatkan apakah baris tetap berada di halaman baru - halaman dengan properti ini harus dicetak ke halaman berikutnya Default false.

**Returns:**
nilai boolean

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

Mendapatkan apakah baris dapat dipotong antara dua halaman.

**Returns:**
nilai boolean

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mendapatkan atau mengatur warna latar belakang baris.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Mendapatkan atau mengatur batas baris.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Mendapatkan batas sel default.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Mendapatkan atau mengatur margin default untuk sel baris.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Mendapatkan atau mengatur keadaan teks default untuk sel baris

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

Mendapatkan tinggi baris tetap - baris dapat memiliki tinggi tetap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

Mendapatkan apakah baris tetap berada di halaman baru - halaman dengan properti ini harus dicetak ke halaman berikutnya Default false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

Mendapatkan tinggi untuk baris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

Mendapatkan apakah baris dapat dipotong antara dua halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mendapatkan atau mengatur perataan vertikal.
