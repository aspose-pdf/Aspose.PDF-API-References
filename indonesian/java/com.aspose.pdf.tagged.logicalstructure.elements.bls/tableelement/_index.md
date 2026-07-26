---
title: "TableElement"
linktitle: "TableElement"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili elemen struktur Table dalam struktur logis."
type: docs
weight: 170
url: /id/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

Mewakili elemen struktur Table dalam struktur logis.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | konstruktor hanya untuk penggunaan internal |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Sesuaikan posisi. |
| [createTBody](#createTBody--) | Membuat {@link TableTHeadElement} dan menambahkannya ke tabel saat ini. |
| [createTFoot](#createTFoot--) | Membuat {@link TableTFootElement} dan menambahkannya ke tabel saat ini. |
| [createTHead](#createTHead--) | Membuat {@link TableTHeadElement} dan menambahkannya ke tabel saat ini. |
| [getAlignment](#getAlignment--) | Mendapatkan atau mengatur perataan tabel. |
| [getBackgroundColor](#getBackgroundColor--) | Mendapatkan atau mengatur warna latar belakang tabel. |
| [getBorder](#getBorder--) | Mendapatkan atau mengatur batas tabel. |
| [getBroken](#getBroken--) | Mendapatkan atau mengatur pemutusan vertikal tabel; |
| [getColumnAdjustment](#getColumnAdjustment--) | Mendapatkan atau mengatur penyesuaian kolom tabel. |
| [getColumnWidths](#getColumnWidths--) | Mendapatkan lebar kolom tabel. |
| [getCornerStyle](#getCornerStyle--) | Mendapatkan atau mengatur gaya sudut batas |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Mendapatkan batas sel default. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Mendapatkan atau mengatur padding sel default. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Mendapatkan atau mengatur keadaan teks sel default. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Mendapatkan atau mengatur lebar kolom default. |
| [getLeft](#getLeft--) | Mendapatkan atau mengatur koordinat kiri tabel. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Mendapatkan atau mengatur jumlah maksimum kolom untuk tabel. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Mendapatkan gaya untuk baris yang diulang. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | Mendapatkan atau mengatur koordinat atas tabel. |
| [isBordersIncluded](#isBordersIncluded--) | Mendapatkan atau mengatur batas yang termasuk dalam lebar kolom. |
| [isBroken](#isBroken--) | Mendapatkan atau mengatur apakah tabel terputus - akan dipotong untuk halaman berikutnya. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Mendapatkan atau mengatur perataan tabel. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mendapatkan atau mengatur warna latar belakang tabel. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Mendapatkan atau mengatur batas tabel. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Mendapatkan atau mengatur batas yang termasuk dalam lebar kolom. |
| [setBroken](#setBroken-boolean-) | Mendapatkan atau mengatur apakah tabel terputus - akan dipotong untuk halaman berikutnya. |
| [setBroken](#setBroken-int-) | Mendapatkan atau mengatur pemutusan vertikal tabel; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Mendapatkan atau mengatur penyesuaian kolom tabel. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Mendapatkan lebar kolom tabel. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Mendapatkan atau mengatur gaya sudut batas |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Mendapatkan batas sel default. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Mendapatkan atau mengatur padding sel default. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Mendapatkan atau mengatur keadaan teks sel default. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Mendapatkan atau mengatur lebar kolom default. |
| [setLeft](#setLeft-float-) | Mendapatkan atau mengatur koordinat kiri tabel. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Mendapatkan atau mengatur jumlah maksimum kolom untuk tabel. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Mendapatkan gaya untuk baris yang diulang. |
| [setTop](#setTop-float-) | Mendapatkan atau mengatur koordinat atas tabel. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
konstruktor hanya untuk penggunaan internal

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Sesuaikan posisi.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

Membuat {@link TableTHeadElement} dan menambahkannya ke tabel saat ini.

**Returns:**
Elemen struktur dibuat.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

Membuat {@link TableTFootElement} dan menambahkannya ke tabel saat ini.

**Returns:**
Elemen struktur dibuat.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

Membuat {@link TableTHeadElement} dan menambahkannya ke tabel saat ini.

**Returns:**
Elemen struktur dibuat.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Mendapatkan atau mengatur perataan tabel.

**Returns:**
Elemen HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Mendapatkan atau mengatur warna latar belakang tabel.

**Returns:**
Instansi Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Mendapatkan atau mengatur batas tabel.

**Returns:**
Instansi BorderInfo

### getBroken {#getBroken--}
```
public final int getBroken()
```

Mendapatkan atau mengatur pemutusan vertikal tabel;

**Returns:**
Elemen TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Mendapatkan atau mengatur penyesuaian kolom tabel.

**Returns:**
ColumnAdjustment elemen

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

Mendapatkan lebar kolom tabel.

**Returns:**
nilai String

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

Mendapatkan atau mengatur gaya sudut batas

**Returns:**
BorderCornerStyle elemen

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

Mendapatkan atau mengatur padding sel default.

**Returns:**
Instansi MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Mendapatkan atau mengatur keadaan teks sel default.

**Returns:**
instansi TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Mendapatkan atau mengatur lebar kolom default.

**Returns:**
nilai String

### getLeft {#getLeft--}
```
public final float getLeft()
```

Mendapatkan atau mengatur koordinat kiri tabel.

**Returns:**
nilai float

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Mendapatkan atau mengatur jumlah maksimum kolom untuk tabel.

**Returns:**
nilai int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman.

**Returns:**
nilai int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Mendapatkan gaya untuk baris yang diulang.

**Returns:**
instansi TextState

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

Mendapatkan atau mengatur koordinat atas tabel.

**Returns:**
nilai float

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Mendapatkan atau mengatur batas yang termasuk dalam lebar kolom.

**Returns:**
nilai boolean

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Mendapatkan atau mengatur apakah tabel terputus - akan dipotong untuk halaman berikutnya.

**Returns:**
nilai boolean

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Mendapatkan atau mengatur perataan tabel.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mendapatkan atau mengatur warna latar belakang tabel.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Mendapatkan atau mengatur batas tabel.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Mendapatkan atau mengatur batas yang termasuk dalam lebar kolom.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Mendapatkan atau mengatur apakah tabel terputus - akan dipotong untuk halaman berikutnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Mendapatkan atau mengatur pemutusan vertikal tabel;

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Mendapatkan atau mengatur penyesuaian kolom tabel.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Mendapatkan lebar kolom tabel.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Mendapatkan atau mengatur gaya sudut batas

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Mendapatkan batas sel default.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Mendapatkan atau mengatur padding sel default.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Mendapatkan atau mengatur keadaan teks sel default.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Mendapatkan atau mengatur lebar kolom default.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Mendapatkan atau mengatur koordinat kiri tabel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Mendapatkan atau mengatur jumlah maksimum kolom untuk tabel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Mendapatkan gaya untuk baris yang diulang.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Mendapatkan atau mengatur koordinat atas tabel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |
