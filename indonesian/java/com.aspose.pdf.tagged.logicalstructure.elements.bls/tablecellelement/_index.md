---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas dasar untuk elemen sel tabel (TH dan TD) dalam struktur logis."
type: docs
weight: 150
url: /id/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

Mewakili kelas dasar untuk elemen sel tabel (TH dan TD) dalam struktur logis.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Sesuaikan posisi. |
| [getAlignment](#getAlignment--) | Mendapatkan atau mengatur perataan sel. |
| [getBackgroundColor](#getBackgroundColor--) | Mendapatkan atau mengatur warna latar belakang sel. |
| [getBorder](#getBorder--) | Mendapatkan atau mengatur batas sel. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | Mendapatkan atau mengatur rentang kolom. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Mendapatkan atau mengatur keadaan teks sel default. |
| [getMargin](#getMargin--) | Mendapatkan atau mengatur padding. |
| [getRowSpan](#getRowSpan--) | Mendapatkan atau mengatur rentang baris. |
| [getStructureTextState](#getStructureTextState--) | Mendapatkan objek {@code /Aspose.Pdf.LogicalStructure.StructureTextState} untuk elemen saat ini. Nilai: objek {@code /Aspose.Pdf.LogicalStructure.StructureTextState} untuk elemen saat ini. |
| [getVerticalAlignment](#getVerticalAlignment--) | Mendapatkan atau mengatur perataan vertikal. |
| [isNoBorder](#isNoBorder--) | Mendapatkan atau mengatur apakah sel memiliki batas. |
| [isWordWrapped](#isWordWrapped--) | Mendapatkan atau mengatur pembungkus kata pada teks sel. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Mendapatkan atau mengatur perataan sel. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mendapatkan atau mengatur warna latar belakang sel. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Mendapatkan atau mengatur batas sel. |
| [setColSpan](#setColSpan-int-) | Mendapatkan atau mengatur rentang kolom. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Mendapatkan atau mengatur keadaan teks sel default. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Mendapatkan atau mengatur padding. |
| [setNoBorder](#setNoBorder-boolean-) | Mendapatkan atau mengatur apakah sel memiliki batas. |
| [setRowSpan](#setRowSpan-int-) | Mendapatkan atau mengatur rentang baris. |
| [setText](#setText-java.lang.String-) | Menambahkan konten teks ke elemen teks saat ini. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mendapatkan atau mengatur perataan vertikal. |
| [setWordWrapped](#setWordWrapped-boolean-) | Mendapatkan atau mengatur pembungkus kata pada teks sel. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Sesuaikan posisi.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Mendapatkan atau mengatur perataan sel.

**Returns:**
Elemen HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Mendapatkan atau mengatur warna latar belakang sel.

**Returns:**
Instansi Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Mendapatkan atau mengatur batas sel.

**Returns:**
Instansi BorderInfo

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Mendapatkan atau mengatur rentang kolom.

**Returns:**
nilai int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Mendapatkan atau mengatur keadaan teks sel default.

**Returns:**
instansi TextState

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

Mendapatkan atau mengatur padding.

**Returns:**
Instansi MarginInfo

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

Mendapatkan atau mengatur rentang baris.

**Returns:**
nilai int

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Mendapatkan objek {@code /Aspose.Pdf.LogicalStructure.StructureTextState} untuk elemen saat ini. Nilai: objek {@code /Aspose.Pdf.LogicalStructure.StructureTextState} untuk elemen saat ini.

**Returns:**
instansi StructureTextState

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Mendapatkan atau mengatur perataan vertikal.

**Returns:**
Elemen VerticalAlignment

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

Mendapatkan atau mengatur apakah sel memiliki batas.

**Returns:**
nilai boolean

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

Mendapatkan atau mengatur pembungkus kata pada teks sel.

**Returns:**
nilai boolean

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Mendapatkan atau mengatur perataan sel.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mendapatkan atau mengatur warna latar belakang sel.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Mendapatkan atau mengatur batas sel.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

Mendapatkan atau mengatur rentang kolom.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Mendapatkan atau mengatur keadaan teks sel default.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Mendapatkan atau mengatur padding.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

Mendapatkan atau mengatur apakah sel memiliki batas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

Mendapatkan atau mengatur rentang baris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setText {#setText-java.lang.String-}
Menambahkan konten teks ke elemen teks saat ini.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mendapatkan atau mengatur perataan vertikal.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

Mendapatkan atau mengatur pembungkus kata pada teks sel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
