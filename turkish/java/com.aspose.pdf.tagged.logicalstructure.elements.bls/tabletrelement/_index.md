---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Aspose.PDF for Java API Referansı"
description: "Tablonun mantıksal yapısında TR yapı öğesini temsil eder."
type: docs
weight: 240
url: /tr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

Tablonun mantıksal yapısında TR yapı öğesini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | yalnızca dahili kullanım için yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createTD](#createTD--) | Mevcut tabloya {@link TableTHElement} oluşturur ve ekler. |
| [createTH](#createTH--) | Mevcut tabloya {@link TableTHElement} oluşturur ve ekler. |
| [getBackgroundColor](#getBackgroundColor--) | Satır arka plan rengini alır veya ayarlar. |
| [getBorder](#getBorder--) | Satır kenarlığını alır veya ayarlar. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Varsayılan hücre kenarlığını alır. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Satır hücreleri için varsayılan kenar boşluğunu alır veya ayarlar. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Satır hücreleri için varsayılan metin durumunu alır veya ayarlar. |
| [getFixedRowHeight](#getFixedRowHeight--) | Sabit satır yüksekliğini alır - satır sabit yüksekliğe sahip olabilir. |
| [getMinRowHeight](#getMinRowHeight--) | Satır yüksekliğini alır. |
| [getVerticalAlignment](#getVerticalAlignment--) | Dikey hizalamayı alır veya ayarlar. |
| [isInNewPage](#isInNewPage--) | Sabit satırın yeni sayfada olup olmadığını alır - bu özelliğe sahip sayfa bir sonraki sayfaya basılmalıdır. Varsayılan false. |
| [isRowBroken](#isRowBroken--) | Satırın iki sayfa arasında bölünebilir olup olmadığını alır. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Satır arka plan rengini alır veya ayarlar. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Satır kenarlığını alır veya ayarlar. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Varsayılan hücre kenarlığını alır. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Satır hücreleri için varsayılan kenar boşluğunu alır veya ayarlar. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Satır hücreleri için varsayılan metin durumunu alır veya ayarlar. |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Sabit satır yüksekliğini alır - satır sabit yüksekliğe sahip olabilir. |
| [setInNewPage](#setInNewPage-boolean-) | Sabit satırın yeni sayfada olup olmadığını alır - bu özelliğe sahip sayfa bir sonraki sayfaya basılmalıdır. Varsayılan false. |
| [setMinRowHeight](#setMinRowHeight-double-) | Satır yüksekliğini alır. |
| [setRowBroken](#setRowBroken-boolean-) | Satırın iki sayfa arasında bölünebilir olup olmadığını alır. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Dikey hizalamayı alır veya ayarlar. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
yalnızca dahili kullanım için yapıcı

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

Mevcut tabloya {@link TableTHElement} oluşturur ve ekler.

**Returns:**
Yapı öğesi oluşturuldu.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

Mevcut tabloya {@link TableTHElement} oluşturur ve ekler.

**Returns:**
Yapı öğesi oluşturuldu.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Satır arka plan rengini alır veya ayarlar.

**Returns:**
Renk örneği

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Satır kenarlığını alır veya ayarlar.

**Returns:**
BorderInfo örneği

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

Satır hücreleri için varsayılan kenar boşluğunu alır veya ayarlar.

**Returns:**
MarginInfo örneği

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Satır hücreleri için varsayılan metin durumunu alır veya ayarlar.

**Returns:**
TextState örneği

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

Sabit satır yüksekliğini alır - satır sabit yüksekliğe sahip olabilir.

**Returns:**
double değer

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

Satır yüksekliğini alır.

**Returns:**
double değer

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Dikey hizalamayı alır veya ayarlar.

**Returns:**
VerticalAlignment öğesi

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

Sabit satırın yeni sayfada olup olmadığını alır - bu özelliğe sahip sayfa bir sonraki sayfaya basılmalıdır. Varsayılan false.

**Returns:**
boolean değer

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

Satırın iki sayfa arasında bölünebilir olup olmadığını alır.

**Returns:**
boolean değer

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Satır arka plan rengini alır veya ayarlar.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Satır kenarlığını alır veya ayarlar.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Varsayılan hücre kenarlığını alır.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Satır hücreleri için varsayılan kenar boşluğunu alır veya ayarlar.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Satır hücreleri için varsayılan metin durumunu alır veya ayarlar.

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

Sabit satır yüksekliğini alır - satır sabit yüksekliğe sahip olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

Sabit satırın yeni sayfada olup olmadığını alır - bu özelliğe sahip sayfa bir sonraki sayfaya basılmalıdır. Varsayılan false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

Satır yüksekliğini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

Satırın iki sayfa arasında bölünebilir olup olmadığını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Dikey hizalamayı alır veya ayarlar.
