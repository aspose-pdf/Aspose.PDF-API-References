---
title: "Row"
linktitle: "Row"
second_title: "Aspose.PDF for Java API Referansı"
description: "Tablonun bir satırını temsil eder."
type: docs
weight: 4330
url: /tr/java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Row

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Row extends Object implements com.aspose.ms.System.ICloneable
```

Tablonun bir satırını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Row](#Row--) | Row sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | Satırı kopyala. |
| [getBackgroundColor](#getBackgroundColor--) | Arka plan rengini alır. |
| [getBorder](#getBorder--) | Kenarı alır. |
| [getCells](#getCells--) | Satırın getCells() metodunu alır. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Varsayılan hücre kenarlığını al; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Satır getCells() için varsayılan kenar boşluğunu alır. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Satır getCells() için varsayılan metin durumunu alır veya ayarlar. Satır getCells() için varsayılan metin durumunu alır. |
| [getFixedRowHeight](#getFixedRowHeight--) | Sabit satır yüksekliğini alır - satır sabit yüksekliğe sahip olabilir; |
| [getMinRowHeight](#getMinRowHeight--) | Satır yüksekliğini alır; |
| [getVerticalAlignment](#getVerticalAlignment--) | Dikey hizalamayı alır veya ayarlar. |
| [isInNewPage](#isInNewPage--) | Sabit satırın yeni sayfada olup olmadığını alır - bu özelliğe sahip sayfa bir sonraki sayfaya basılmalıdır. Varsayılan false; |
| [isRowBroken](#isRowBroken--) | Satırın iki sayfa arasında bölünebilir olup olmadığını alır |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Arka plan rengini ayarlar. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Kenarı ayarlar. |
| [setCells](#setCells-com.aspose.pdf.Cells-) | Satırın getCells() metodunu ayarlar. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Varsayılan hücre kenarlığını ayarlar; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Satır getCells() için varsayılan kenar boşluğunu ayarlar |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Satır getCells() için varsayılan metin durumunu ayarlar |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Sabit satır yüksekliğini ayarlar - satır sabit yüksekliğe sahip olabilir; |
| [setInNewPage](#setInNewPage-boolean-) | Satırın iki sayfa arasında bölünebilir olup olmadığını ayarlar |
| [setMinRowHeight](#setMinRowHeight-double-) | Satır yüksekliğini ayarlar; |
| [setRowBroken](#setRowBroken-boolean-) | Satırın iki sayfa arasında bölünebilir olup olmadığını ayarlar |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Dikey hizalamayı alır veya ayarlar. |

### Row {#Row--}
```
public Row()
```

Row sınıfının yeni bir örneğini başlatır.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Satırı kopyala.

**Returns:**
Klonlanmış nesne

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Arka plan rengini alır.

**Returns:**
Renk değeri

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Kenarı alır.

**Returns:**
BorderInfo değeri

### getCells {#getCells--}
```
public Cells getCells()
```

Satırın getCells() metodunu alır.

**Returns:**
getCells() değeri

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```

Varsayılan hücre kenarlığını al;

**Returns:**
BorderInfo değeri

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```

Satır getCells() için varsayılan kenar boşluğunu alır.

**Returns:**
MarginInfo değeri

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Satır getCells() için varsayılan metin durumunu alır veya ayarlar. Satır getCells() için varsayılan metin durumunu alır.

**Returns:**
TextState değeri

### getFixedRowHeight {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```

Sabit satır yüksekliğini alır - satır sabit yüksekliğe sahip olabilir;

**Returns:**
double değer

### getMinRowHeight {#getMinRowHeight--}
```
public double getMinRowHeight()
```

Satır yüksekliğini alır;

**Returns:**
double değer

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Dikey hizalamayı alır veya ayarlar.

**Returns:**
VerticalAlignment öğesi @see VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Sabit satırın yeni sayfada olup olmadığını alır - bu özelliğe sahip sayfa bir sonraki sayfaya basılmalıdır. Varsayılan false;

**Returns:**
boolean değer

### isRowBroken {#isRowBroken--}
```
public boolean isRowBroken()
```

Satırın iki sayfa arasında bölünebilir olup olmadığını alır

**Returns:**
boolean değer

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Arka plan rengini ayarlar.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Kenarı ayarlar.

### setCells {#setCells-com.aspose.pdf.Cells-}
Satırın getCells() metodunu ayarlar.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Varsayılan hücre kenarlığını ayarlar;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Satır getCells() için varsayılan kenar boşluğunu ayarlar

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Satır getCells() için varsayılan metin durumunu ayarlar

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```

Sabit satır yüksekliğini ayarlar - satır sabit yüksekliğe sahip olabilir;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Satırın iki sayfa arasında bölünebilir olup olmadığını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMinRowHeight {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```

Satır yüksekliğini ayarlar;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setRowBroken {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```

Satırın iki sayfa arasında bölünebilir olup olmadığını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Dikey hizalamayı alır veya ayarlar.
