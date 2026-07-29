---
title: "Cell"
linktitle: "Cell"
second_title: "Aspose.PDF for Java API Referansı"
description: "Tablonun satırındaki bir hücreyi temsil eder."
type: docs
weight: 510
url: /tr/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

Tablonun satırındaki bir hücreyi temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Cell](#Cell--) | Cell sınıfının yeni bir örneğini başlatır. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Cell sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | Hücreyi klonla. |
| [getAlignment](#getAlignment--) | Hizalamayı al. |
| [getBackgroundColor](#getBackgroundColor--) | Arka plan rengini alır. |
| [getBackgroundImage](#getBackgroundImage--) | Arka plan resmini alır veya ayarlar |
| [getBackgroundImageFile](#getBackgroundImageFile--) | Arka plan resim dosyasını al. |
| [getBorder](#getBorder--) | Kenarı alır. |
| [getColSpan](#getColSpan--) | Sütun genişliğini alır veya ayarlar |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Varsayılan hücre metin durumunu alır. |
| [getMargin](#getMargin--) | Dolgu değerini al. |
| [getParagraphs](#getParagraphs--) | Hücrenin biçimlendirilmiş metnini al. |
| [getRowSpan](#getRowSpan--) | Satır genişliğini al. |
| [getVerticalAlignment](#getVerticalAlignment--) | Dikey hizalamayı al. |
| [getWidth](#getWidth--) | Sütun genişliğini al. |
| [isNoBorder](#isNoBorder--) | Hücrenin kenarlığının olup olmadığını al. |
| [isOverrideByFragment](#isOverrideByFragment--) | Hücrenin **TextState** özelliği, **TextFragment TextState** özelliği tarafından geçersiz kılınır. |
| [isWordWrapped](#isWordWrapped--) | Hücrenin metninin kelime kaydırmasını al. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Hizalamayı ayarlar. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Arka plan rengini alır veya ayarlar. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Arka plan resmini alır veya ayarlar |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | Arka plan resim dosyasını ayarlar. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Kenarı ayarlar. |
| [setColSpan](#setColSpan-int-) | Sütun genişliğini ayarlar. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Varsayılan hücre metin durumunu ayarlar. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Dolgu değerini ayarlar. |
| [setNoBorder](#setNoBorder-boolean-) | Hücrenin kenarlığını ayarlar. |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | Hücrenin **TextState** özelliği, **TextFragment TextState** özelliği tarafından geçersiz kılınır. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Hücrenin biçimlendirilmiş metnini ayarlar. |
| [setRowSpan](#setRowSpan-int-) | Satır genişliğini ayarlar. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Dikey hizalamayı ayarlar. |
| [setWidth](#setWidth-double-) | Sütun genişliğini ayarlar. |
| [setWordWrapped](#setWordWrapped-boolean-) | Hücrenin metninin kelime kaydırmasını ayarlar. |

### Cell {#Cell--}
```
public Cell()
```

Cell sınıfının yeni bir örneğini başlatır.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Cell sınıfının yeni bir örneğini başlatır.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Hücreyi klonla.

**Returns:**
Klonlanmış nesne

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

Hizalamayı al.

**Returns:**
HorizontalAlignment öğesi @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Arka plan rengini alır.

**Returns:**
Color nesnesi

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Arka plan resmini alır veya ayarlar

**Returns:**
Görüntü örneği

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

Arka plan resim dosyasını al.

**Returns:**
String değeri @deprecated Özellik genişletildi lütfen BackgroundImage kullanın

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Kenarı alır.

**Returns:**
BorderInfo nesnesi

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

Sütun genişliğini alır veya ayarlar

**Returns:**
int değer

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Varsayılan hücre metin durumunu alır.

**Returns:**
TextState nesnesi

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Dolgu değerini al.

**Returns:**
MarginInfo nesnesi

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Hücrenin biçimlendirilmiş metnini al.

**Returns:**
Paragraflar nesnesi

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

Satır genişliğini al.

**Returns:**
int değer

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Dikey hizalamayı al.

**Returns:**
VerticalAlignment öğesi @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Sütun genişliğini al.

**Returns:**
double değer

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

Hücrenin kenarlığının olup olmadığını al.

**Returns:**
boolean değer

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

Hücrenin **TextState** özelliği, **TextFragment TextState** özelliği tarafından geçersiz kılınır.

**Returns:**
boolean değer

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

Hücrenin metninin kelime kaydırmasını al.

**Returns:**
boolean değer

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Hizalamayı ayarlar.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Arka plan rengini alır veya ayarlar.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Arka plan resmini alır veya ayarlar

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
Arka plan resim dosyasını ayarlar.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Kenarı ayarlar.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

Sütun genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Varsayılan hücre metin durumunu ayarlar.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Dolgu değerini ayarlar.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

Hücrenin kenarlığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

Hücrenin **TextState** özelliği, **TextFragment TextState** özelliği tarafından geçersiz kılınır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Hücrenin biçimlendirilmiş metnini ayarlar.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

Satır genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Dikey hizalamayı ayarlar.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sütun genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

Hücrenin metninin kelime kaydırmasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
