---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Aspose.PDF for Java API Referansı"
description: "Mantıksal yapıda tablo hücre öğeleri (TH ve TD) için temel sınıfı temsil eder."
type: docs
weight: 150
url: /tr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

Mantıksal yapıda tablo hücre öğeleri (TH ve TD) için temel sınıfı temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Pozisyonu ayarla. |
| [getAlignment](#getAlignment--) | Hücre hizalamasını alır veya ayarlar. |
| [getBackgroundColor](#getBackgroundColor--) | Hücre arka plan rengini alır veya ayarlar. |
| [getBorder](#getBorder--) | Hücre kenarlığını alır veya ayarlar. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | Sütun genişliğini alır veya ayarlar |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Varsayılan hücre metin durumunu alır veya ayarlar. |
| [getMargin](#getMargin--) | Dolgu değerini alır veya ayarlar. |
| [getRowSpan](#getRowSpan--) | Satır kapsamını alır veya ayarlar. |
| [getStructureTextState](#getStructureTextState--) | Geçerli öğe için {@code /Aspose.Pdf.LogicalStructure.StructureTextState} nesnesini alır. Değer: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} nesnesi geçerli öğe için. |
| [getVerticalAlignment](#getVerticalAlignment--) | Dikey hizalamayı alır veya ayarlar. |
| [isNoBorder](#isNoBorder--) | Hücrenin kenarlığının olup olmadığını alır veya ayarlar. |
| [isWordWrapped](#isWordWrapped--) | Hücre metninin kelime kaydırmasını alır veya ayarlar. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Hücre hizalamasını alır veya ayarlar. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Hücre arka plan rengini alır veya ayarlar. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Hücre kenarlığını alır veya ayarlar. |
| [setColSpan](#setColSpan-int-) | Sütun genişliğini alır veya ayarlar |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Varsayılan hücre metin durumunu alır veya ayarlar. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Dolgu değerini alır veya ayarlar. |
| [setNoBorder](#setNoBorder-boolean-) | Hücrenin kenarlığının olup olmadığını alır veya ayarlar. |
| [setRowSpan](#setRowSpan-int-) | Satır kapsamını alır veya ayarlar. |
| [setText](#setText-java.lang.String-) | Metin içeriğini mevcut metin öğesine ekler. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Dikey hizalamayı alır veya ayarlar. |
| [setWordWrapped](#setWordWrapped-boolean-) | Hücre metninin kelime kaydırmasını alır veya ayarlar. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Pozisyonu ayarla.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Hücre hizalamasını alır veya ayarlar.

**Returns:**
HorizontalAlignment öğesi

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Hücre arka plan rengini alır veya ayarlar.

**Returns:**
Renk örneği

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Hücre kenarlığını alır veya ayarlar.

**Returns:**
BorderInfo örneği

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Sütun genişliğini alır veya ayarlar

**Returns:**
int değer

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Varsayılan hücre metin durumunu alır veya ayarlar.

**Returns:**
TextState örneği

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

Dolgu değerini alır veya ayarlar.

**Returns:**
MarginInfo örneği

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

Satır kapsamını alır veya ayarlar.

**Returns:**
int değer

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Geçerli öğe için {@code /Aspose.Pdf.LogicalStructure.StructureTextState} nesnesini alır. Değer: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} nesnesi geçerli öğe için.

**Returns:**
StructureTextState örneği

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Dikey hizalamayı alır veya ayarlar.

**Returns:**
VerticalAlignment öğesi

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

Hücrenin kenarlığının olup olmadığını alır veya ayarlar.

**Returns:**
boolean değer

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

Hücre metninin kelime kaydırmasını alır veya ayarlar.

**Returns:**
boolean değer

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Hücre hizalamasını alır veya ayarlar.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Hücre arka plan rengini alır veya ayarlar.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Hücre kenarlığını alır veya ayarlar.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

Sütun genişliğini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Varsayılan hücre metin durumunu alır veya ayarlar.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Dolgu değerini alır veya ayarlar.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

Hücrenin kenarlığının olup olmadığını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

Satır kapsamını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setText {#setText-java.lang.String-}
Metin içeriğini mevcut metin öğesine ekler.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Dikey hizalamayı alır veya ayarlar.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

Hücre metninin kelime kaydırmasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
