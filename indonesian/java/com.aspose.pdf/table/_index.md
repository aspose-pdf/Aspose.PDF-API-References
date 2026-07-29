---
title: "Tabel"
linktitle: "Tabel"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili tabel yang dapat ditambahkan ke halaman."
type: docs
weight: 4790
url: /id/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

Mewakili tabel yang dapat ditambahkan ke halaman.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Table](#Table--) | Konstruktor default |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone](#deepClone--) | / * / * Mengimpor array satu dimensi data ke dalam tabel. Impor menempatkan satu sel per setiap item array dan / * mulai dari baris dan kolom yang ditentukan dalam parameter. Selama impor, jika terdeteksi bahwa baris yang diperlukan / * masih belum ada (misalnya tabel target terlalu kecil untuk menampung semua data), baris yang diperlukan akan dibuat / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | Tambahkan operator untuk persegi panjang. |
| [getAlignment](#getAlignment--) | Mendapatkan perataan tabel. |
| [getBackgroundColor](#getBackgroundColor--) | Mendapatkan warna latar belakang tabel |
| [getBorder](#getBorder--) | Mendapatkan border. |
| [getBreakText](#getBreakText--) | Mendapatkan teks pemisah untuk tabel |
| [getBroken](#getBroken--) | Mendapatkan atau mengatur pemecahan vertikal tabel; |
| [getColumnAdjustment](#getColumnAdjustment--) | Mendapatkan penyesuaian kolom tabel. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | Dapatkan lebar kolom |
| [getColumnWidths](#getColumnWidths--) | Mendapatkan lebar kolom tabel. |
| [getCornerStyle](#getCornerStyle--) | Mendapatkan gaya sudut batas |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Mendapatkan batas sel default; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Mendapatkan padding sel default. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Mendapatkan keadaan teks sel default. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Mendapatkan batas sel default; |
| [getHeight](#getHeight--) | Dapatkan tinggi. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | Dapatkan tinggi. |
| [getLeft](#getLeft--) | Mendapatkan koordinat kiri tabel. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Mendapatkan atau mengatur jumlah kolom maksimum untuk tabel |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Mendapatkan gaya untuk baris yang diulang |
| [getRows](#getRows--) | Mendapatkan baris tabel. |
| [getTop](#getTop--) | Mendapatkan koordinat atas tabel. |
| [getWidth](#getWidth--) | Dapatkan lebar. |
| [isBordersIncluded](#isBordersIncluded--) | Mendapatkan batas yang termasuk dalam lebar kolom. |
| [isBroken](#isBroken--) | Mendapatkan apakah tabel rusak - akan dipotong untuk halaman berikutnya. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Mengatur perataan tabel. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mengatur warna latar belakang tabel |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Mengatur border. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Mengatur batas yang termasuk dalam lebar kolom. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | Mengatur teks pemisah untuk tabel |
| [setBroken](#setBroken-boolean-) | Mengatur apakah tabel rusak - akan dipotong untuk halaman berikutnya. |
| [setBroken](#setBroken-int-) | Mendapatkan atau mengatur pemecahan vertikal tabel; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Mengatur penyesuaian kolom tabel. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | Atur tinggi. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Mendapatkan lebar kolom tabel. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Mendapatkan atau mengatur gaya sudut batas |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Mendapatkan batas sel default; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Mengatur padding sel default. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Mengatur status teks sel default. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Mendapatkan batas sel default; |
| [setLeft](#setLeft-float-) | Mengatur koordinat kiri tabel. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Mendapatkan atau mengatur jumlah kolom maksimum untuk tabel |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Mendapatkan gaya untuk baris yang diulang |
| [setTop](#setTop-float-) | Mengatur koordinat atas tabel. |

### Table {#Table--}
```
public Table()
```

Konstruktor default

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * Mengimpor array satu dimensi data ke dalam tabel. Impor menempatkan satu sel per setiap item array dan / * mulai dari baris dan kolom yang ditentukan dalam parameter. Selama impor, jika terdeteksi bahwa baris yang diperlukan / * masih belum ada (misalnya tabel target terlalu kecil untuk menampung semua data), baris yang diperlukan akan dibuat / * / *

**Returns:**
Objek yang diklon.

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
Tambahkan operator untuk persegi panjang.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Mendapatkan perataan tabel.

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Mendapatkan warna latar belakang tabel

**Returns:**
objek Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Mendapatkan border.

**Returns:**
Objek BorderInfo

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

Mendapatkan teks pemisah untuk tabel

**Returns:**
objek TextFragment

### getBroken {#getBroken--}
```
public final int getBroken()
```

Mendapatkan atau mengatur pemecahan vertikal tabel;

**Returns:**
Nilai TableBroken @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Mendapatkan penyesuaian kolom tabel.

**Returns:**
Nilai ColumnAdjustment @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
Dapatkan lebar kolom

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

Mendapatkan gaya sudut batas

**Returns:**
Nilai BorderCornerStyle @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Mendapatkan batas sel default;

**Returns:**
Objek BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Mendapatkan padding sel default.

**Returns:**
Objek MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Mendapatkan keadaan teks sel default.

**Returns:**
Nilai TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Mendapatkan batas sel default;

**Returns:**
Objek String

### getHeight {#getHeight--}
```
public double getHeight()
```

Dapatkan tinggi.

**Returns:**
Tinggi tabel

### getHeight {#getHeight-com.aspose.pdf.Page-}
Dapatkan tinggi.

**Returns:**
Tinggi tabel

### getLeft {#getLeft--}
```
public final float getLeft()
```

Mendapatkan koordinat kiri tabel.

**Returns:**
nilai float

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Mendapatkan atau mengatur jumlah kolom maksimum untuk tabel

**Returns:**
nilai int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman

**Returns:**
nilai int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Mendapatkan gaya untuk baris yang diulang

**Returns:**
Objek TextState

### getRows {#getRows--}
```
public final Rows getRows()
```

Mendapatkan baris tabel.

**Returns:**
Objek Rows

### getTop {#getTop--}
```
public final float getTop()
```

Mendapatkan koordinat atas tabel.

**Returns:**
nilai float

### getWidth {#getWidth--}
```
public double getWidth()
```

Dapatkan lebar.

**Returns:**
Lebar tabel

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Mendapatkan batas yang termasuk dalam lebar kolom.

**Returns:**
nilai boolean

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Mendapatkan apakah tabel rusak - akan dipotong untuk halaman berikutnya.

**Returns:**
nilai boolean

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Mengatur perataan tabel.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mengatur warna latar belakang tabel

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Mengatur border.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Mengatur batas yang termasuk dalam lebar kolom.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
Mengatur teks pemisah untuk tabel

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Mengatur apakah tabel rusak - akan dipotong untuk halaman berikutnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Mendapatkan atau mengatur pemecahan vertikal tabel;

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai TableBroken @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Mengatur penyesuaian kolom tabel.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
Atur tinggi.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Mendapatkan lebar kolom tabel.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Mendapatkan atau mengatur gaya sudut batas

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Mendapatkan batas sel default;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Mengatur padding sel default.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Mengatur status teks sel default.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Mendapatkan batas sel default;

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Mengatur koordinat kiri tabel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Mendapatkan atau mengatur jumlah kolom maksimum untuk tabel

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Mendapatkan gaya untuk baris yang diulang

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Mengatur koordinat atas tabel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |
