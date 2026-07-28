---
title: "TableElement"
linktitle: "TableElement"
second_title: "Aspose.PDF for Java API Referansı"
description: "Mantıksal yapıda Table yapı öğesini temsil eder."
type: docs
weight: 170
url: /tr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

Mantıksal yapıda Table yapı öğesini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | yalnızca dahili kullanım için yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Pozisyonu ayarla. |
| [createTBody](#createTBody--) | Mevcut tabloya {@link TableTHeadElement} oluşturur ve ekler. |
| [createTFoot](#createTFoot--) | Mevcut tabloya {@link TableTFootElement} oluşturur ve ekler. |
| [createTHead](#createTHead--) | Mevcut tabloya {@link TableTHeadElement} oluşturur ve ekler. |
| [getAlignment](#getAlignment--) | Tablonun hizalamasını alır veya ayarlar. |
| [getBackgroundColor](#getBackgroundColor--) | Tablonun arka plan rengini alır veya ayarlar. |
| [getBorder](#getBorder--) | Tablonun kenarlığını alır veya ayarlar. |
| [getBroken](#getBroken--) | Tablonun dikey kırılmasını alır veya ayarlar; |
| [getColumnAdjustment](#getColumnAdjustment--) | Tablonun sütun ayarlamasını alır veya ayarlar. |
| [getColumnWidths](#getColumnWidths--) | Tablonun sütun genişliklerini alır. |
| [getCornerStyle](#getCornerStyle--) | Kenarlık köşelerinin stillerini alır veya ayarlar |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Varsayılan hücre kenarlığını alır. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Varsayılan hücre doldurmasını alır veya ayarlar. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Varsayılan hücre metin durumunu alır veya ayarlar. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Varsayılan sütun genişliğini alır veya ayarlar. |
| [getLeft](#getLeft--) | Tablonun sol koordinatını alır veya ayarlar. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Tablo için maksimum sütun sayısını alır veya ayarlar. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Birden fazla sayfada tekrarlanan ilk satır sayısını alır. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Tekrarlanan satırlar için stili alır. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | Tablonun üst koordinatını alır veya ayarlar. |
| [isBordersIncluded](#isBordersIncluded--) | Sütun genişliklerine dahil edilen kenarlığı alır veya ayarlar. |
| [isBroken](#isBroken--) | Tablonun kırık olup olmadığını alır veya ayarlar - bir sonraki sayfada kırpılacaktır. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Tablonun hizalamasını alır veya ayarlar. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Tablonun arka plan rengini alır veya ayarlar. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Tablonun kenarlığını alır veya ayarlar. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Sütun genişliklerine dahil edilen kenarlığı alır veya ayarlar. |
| [setBroken](#setBroken-boolean-) | Tablonun kırık olup olmadığını alır veya ayarlar - bir sonraki sayfada kırpılacaktır. |
| [setBroken](#setBroken-int-) | Tablonun dikey kırılmasını alır veya ayarlar; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Tablonun sütun ayarlamasını alır veya ayarlar. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Tablonun sütun genişliklerini alır. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Kenarlık köşelerinin stillerini alır veya ayarlar |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Varsayılan hücre kenarlığını alır. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Varsayılan hücre doldurmasını alır veya ayarlar. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Varsayılan hücre metin durumunu alır veya ayarlar. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Varsayılan sütun genişliğini alır veya ayarlar. |
| [setLeft](#setLeft-float-) | Tablonun sol koordinatını alır veya ayarlar. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Tablo için maksimum sütun sayısını alır veya ayarlar. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Birden fazla sayfada tekrarlanan ilk satır sayısını alır. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Tekrarlanan satırlar için stili alır. |
| [setTop](#setTop-float-) | Tablonun üst koordinatını alır veya ayarlar. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
yalnızca dahili kullanım için yapıcı

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Pozisyonu ayarla.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

Mevcut tabloya {@link TableTHeadElement} oluşturur ve ekler.

**Returns:**
Yapı öğesi oluşturuldu.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

Mevcut tabloya {@link TableTFootElement} oluşturur ve ekler.

**Returns:**
Yapı öğesi oluşturuldu.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

Mevcut tabloya {@link TableTHeadElement} oluşturur ve ekler.

**Returns:**
Yapı öğesi oluşturuldu.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Tablonun hizalamasını alır veya ayarlar.

**Returns:**
HorizontalAlignment öğesi

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Tablonun arka plan rengini alır veya ayarlar.

**Returns:**
Renk örneği

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Tablonun kenarlığını alır veya ayarlar.

**Returns:**
BorderInfo örneği

### getBroken {#getBroken--}
```
public final int getBroken()
```

Tablonun dikey kırılmasını alır veya ayarlar;

**Returns:**
TableBroken öğesi

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Tablonun sütun ayarlamasını alır veya ayarlar.

**Returns:**
ColumnAdjustment öğesi

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

Kenarlık köşelerinin stillerini alır veya ayarlar

**Returns:**
BorderCornerStyle öğesi

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Varsayılan hücre kenarlığını alır.

**Returns:**
BorderInfo örneği

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Varsayılan hücre doldurmasını alır veya ayarlar.

**Returns:**
MarginInfo örneği

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Varsayılan hücre metin durumunu alır veya ayarlar.

**Returns:**
TextState örneği

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Varsayılan sütun genişliğini alır veya ayarlar.

**Returns:**
String değeri

### getLeft {#getLeft--}
```
public final float getLeft()
```

Tablonun sol koordinatını alır veya ayarlar.

**Returns:**
float değer

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Tablo için maksimum sütun sayısını alır veya ayarlar.

**Returns:**
int değer

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Birden fazla sayfada tekrarlanan ilk satır sayısını alır.

**Returns:**
int değer

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Tekrarlanan satırlar için stili alır.

**Returns:**
TextState örneği

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

Tablonun üst koordinatını alır veya ayarlar.

**Returns:**
float değer

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Sütun genişliklerine dahil edilen kenarlığı alır veya ayarlar.

**Returns:**
boolean değer

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Tablonun kırık olup olmadığını alır veya ayarlar - bir sonraki sayfada kırpılacaktır.

**Returns:**
boolean değer

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Tablonun hizalamasını alır veya ayarlar.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Tablonun arka plan rengini alır veya ayarlar.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Tablonun kenarlığını alır veya ayarlar.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Sütun genişliklerine dahil edilen kenarlığı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Tablonun kırık olup olmadığını alır veya ayarlar - bir sonraki sayfada kırpılacaktır.

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
| değer |  | TableBroken öğesi |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Tablonun sütun ayarlamasını alır veya ayarlar.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Tablonun sütun genişliklerini alır.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Kenarlık köşelerinin stillerini alır veya ayarlar

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Varsayılan hücre kenarlığını alır.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Varsayılan hücre doldurmasını alır veya ayarlar.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Varsayılan hücre metin durumunu alır veya ayarlar.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Varsayılan sütun genişliğini alır veya ayarlar.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Tablonun sol koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Tablo için maksimum sütun sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Birden fazla sayfada tekrarlanan ilk satır sayısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Tekrarlanan satırlar için stili alır.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Tablonun üst koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |
