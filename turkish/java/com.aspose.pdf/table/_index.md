---
title: "Tablo"
linktitle: "Tablo"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfaya eklenebilen bir tabloyu temsil eder."
type: docs
weight: 4790
url: /tr/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

Sayfaya eklenebilen bir tabloyu temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Table](#Table--) | Varsayılan ctor |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | / * / * Tabloya tek boyutlu veri dizisi aktarır. Aktarım, dizinin her öğesi için bir hücreye gider ve / * parametrelere tanımlanan satır ve sütundan başlar. Aktarım sırasında, gerekli satırların / * hâlâ eksik olduğu tespit edilirse (ör. hedef tablo tüm veriyi alacak kadar küçük), gerekli satırlar oluşturulacaktır / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | Dikdörtgen için operatörler ekle. |
| [getAlignment](#getAlignment--) | Tablonun hizalamasını alır. |
| [getBackgroundColor](#getBackgroundColor--) | Tablonun arka plan rengini alır |
| [getBorder](#getBorder--) | Kenarı alır. |
| [getBreakText](#getBreakText--) | Tablo için kesme metnini alır |
| [getBroken](#getBroken--) | Tablonun dikey kırılmasını alır veya ayarlar; |
| [getColumnAdjustment](#getColumnAdjustment--) | Tablonun sütun ayarlamasını alır. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | Sütun genişliğini al |
| [getColumnWidths](#getColumnWidths--) | Tablonun sütun genişliklerini alır. |
| [getCornerStyle](#getCornerStyle--) | Kenar köşelerinin stillerini alır |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Varsayılan hücre kenarlığını al; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Varsayılan hücre doldurmasını alır. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Varsayılan hücre metin durumunu alır. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Varsayılan hücre kenarlığını al; |
| [getHeight](#getHeight--) | Yüksekliği al. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | Yüksekliği al. |
| [getLeft](#getLeft--) | Tablonun sol koordinatını alır. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Tablo için maksimum sütun sayısını alır veya ayarlar |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Birden fazla sayfada tekrarlanan ilk satır sayısını alır |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Tekrarlanan satırlar için stili alır |
| [getRows](#getRows--) | Tablonun satırlarını alır. |
| [getTop](#getTop--) | Tablonun üst koordinatını alır. |
| [getWidth](#getWidth--) | Genişliği al. |
| [isBordersIncluded](#isBordersIncluded--) | Sütun genişliklerine dahil edilen kenarlığı alır. |
| [isBroken](#isBroken--) | Tablonun kırık olduğunu alır - bir sonraki sayfada kırpılacak. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Tablo hizalamasını ayarlar. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Tablo arka plan rengini ayarlar |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Kenarı ayarlar. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Sütun genişliklerine dahil edilen kenarlığı ayarlar. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | Tablo için kesme metnini ayarlar |
| [setBroken](#setBroken-boolean-) | Tablonun kırık olduğunu ayarlar - bir sonraki sayfada kırpılacak. |
| [setBroken](#setBroken-int-) | Tablonun dikey kırılmasını alır veya ayarlar; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Tablo sütun ayarlamasını ayarlar. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | Yüksekliği ayarla. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Tablonun sütun genişliklerini alır. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Kenarlık köşelerinin stillerini alır veya ayarlar |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Varsayılan hücre kenarlığını al; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Varsayılan hücre doldurmasını ayarlar. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Varsayılan hücre metin durumunu ayarlar. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Varsayılan hücre kenarlığını al; |
| [setLeft](#setLeft-float-) | Tablonun sol koordinatını ayarlar. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Tablo için maksimum sütun sayısını alır veya ayarlar |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Birden fazla sayfada tekrarlanan ilk satır sayısını alır |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Tekrarlanan satırlar için stili alır |
| [setTop](#setTop-float-) | Tablonun üst koordinatını ayarlar. |

### Table {#Table--}
```
public Table()
```

Varsayılan ctor

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * Tabloya tek boyutlu veri dizisi aktarır. Aktarım, dizinin her öğesi için bir hücreye gider ve / * parametrelere tanımlanan satır ve sütundan başlar. Aktarım sırasında, gerekli satırların / * hâlâ eksik olduğu tespit edilirse (ör. hedef tablo tüm veriyi alacak kadar küçük), gerekli satırlar oluşturulacaktır / * / *

**Returns:**
Klonlanmış nesne

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
Dikdörtgen için operatörler ekle.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Tablonun hizalamasını alır.

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Tablonun arka plan rengini alır

**Returns:**
Color nesnesi

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Kenarı alır.

**Returns:**
BorderInfo nesnesi

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

Tablo için kesme metnini alır

**Returns:**
TextFragment nesnesi

### getBroken {#getBroken--}
```
public final int getBroken()
```

Tablonun dikey kırılmasını alır veya ayarlar;

**Returns:**
TableBroken değeri @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Tablonun sütun ayarlamasını alır.

**Returns:**
ColumnAdjustment değeri @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
Sütun genişliğini al

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

Tablonun sütun genişliklerini alır.

**Returns:**
String değeri

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

Kenar köşelerinin stillerini alır

**Returns:**
BorderCornerStyle değeri @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Varsayılan hücre kenarlığını al;

**Returns:**
BorderInfo nesnesi

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Varsayılan hücre doldurmasını alır.

**Returns:**
MarginInfo nesnesi

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Varsayılan hücre metin durumunu alır.

**Returns:**
TextState değeri

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Varsayılan hücre kenarlığını al;

**Returns:**
Dize nesnesi

### getHeight {#getHeight--}
```
public double getHeight()
```

Yüksekliği al.

**Returns:**
Tablo yüksekliği

### getHeight {#getHeight-com.aspose.pdf.Page-}
Yüksekliği al.

**Returns:**
Tablo yüksekliği

### getLeft {#getLeft--}
```
public final float getLeft()
```

Tablonun sol koordinatını alır.

**Returns:**
float değer

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Tablo için maksimum sütun sayısını alır veya ayarlar

**Returns:**
int değer

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Birden fazla sayfada tekrarlanan ilk satır sayısını alır

**Returns:**
int değer

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Tekrarlanan satırlar için stili alır

**Returns:**
TextState nesnesi

### getRows {#getRows--}
```
public final Rows getRows()
```

Tablonun satırlarını alır.

**Returns:**
Rows nesnesi

### getTop {#getTop--}
```
public final float getTop()
```

Tablonun üst koordinatını alır.

**Returns:**
float değer

### getWidth {#getWidth--}
```
public double getWidth()
```

Genişliği al.

**Returns:**
Tablo genişliği

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Sütun genişliklerine dahil edilen kenarlığı alır.

**Returns:**
boolean değer

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Tablonun kırık olduğunu alır - bir sonraki sayfada kırpılacak.

**Returns:**
boolean değer

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Tablo hizalamasını ayarlar.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Tablo arka plan rengini ayarlar

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Kenarı ayarlar.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Sütun genişliklerine dahil edilen kenarlığı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
Tablo için kesme metnini ayarlar

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Tablonun kırık olduğunu ayarlar - bir sonraki sayfada kırpılacak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Tablonun dikey kırılmasını alır veya ayarlar;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | TableBroken değeri @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Tablo sütun ayarlamasını ayarlar.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
Yüksekliği ayarla.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Tablonun sütun genişliklerini alır.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Kenarlık köşelerinin stillerini alır veya ayarlar

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Varsayılan hücre kenarlığını al;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Varsayılan hücre doldurmasını ayarlar.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Varsayılan hücre metin durumunu ayarlar.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Varsayılan hücre kenarlığını al;

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Tablonun sol koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Tablo için maksimum sütun sayısını alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Birden fazla sayfada tekrarlanan ilk satır sayısını alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Tekrarlanan satırlar için stili alır

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Tablonun üst koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |
