---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfaya (doc.Paragraphs.Add()) eklenebilen soyut bir temel nesneyi temsil eder."
type: docs
weight: 280
url: /tr/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

Sayfaya (doc.Paragraphs.Add()) eklenebilen soyut bir temel nesneyi temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | Bu örneği klonlar. Sanal yöntem. Her zaman null döndürür. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Paragrafın yatay hizalamasını alır |
| [getHyperlink](#getHyperlink--) | / * / * Bir paragrafın dipnot olup olmadığını alır veya ayarlar. Varsayılan false'tur.(pdf oluşturma için) / * / * |
| [getMargin](#getMargin--) | Paragraf için dış kenar boşluğunu alır (pdf oluşturma için) |
| [getVerticalAlignment](#getVerticalAlignment--) | Paragrafın dikey hizalamasını alır |
| [getZIndex](#getZIndex--) | Grafiğin Z-sırasını gösteren bir int değer alır. Daha büyük ZIndex değerine sahip bir grafik, daha küçük ZIndex değerine sahip grafiğin üzerine yerleştirilir. ZIndex negatif olabilir. Negatif ZIndex değerine sahip grafik, sayfadaki metnin arkasına yerleştirilir. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Bu paragrafın bir sonraki sütunda olup olmayacağını gösteren bir bool değer alır veya ayarlar. Varsayılan false'tur.(pdf oluşturma için) |
| [isInLineParagraph](#isInLineParagraph--) | Paragrafın satır içi olup olmadığını alır. Varsayılan false'tur.(pdf oluşturma için) |
| [isInNewPage](#isInNewPage--) | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır. Varsayılan değer false'tur. (pdf oluşturma için) |
| [isKeptWithNext](#isKeptWithNext--) | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını gösteren bir boolean değeri alır. Varsayılan değer false'tur. (pdf oluşturma için) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | Bu paragrafın bir sonraki sütunda olup olmayacağını gösteren bir bool değer alır veya ayarlar. Varsayılan false'tur.(pdf oluşturma için) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Paragrafın yatay hizalamasını ayarlar |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Hipermetin bağlantısını ayarlar (pdf oluşturucu için). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | Paragrafın satır içi olmasını ayarlar. Varsayılan değer false'tur. (pdf oluşturma için) |
| [setInNewPage](#setInNewPage-boolean-) | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir boolean değeri ayarlar. Varsayılan değer false'tur. (pdf oluşturma için) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını gösteren bir boolean değeri ayarlar. Varsayılan değer false'tur. (pdf oluşturma için) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Paragraf için dış kenar boşluğunu ayarlar (pdf oluşturma için) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Paragrafın dikey hizalamasını ayarlar |
| [setZIndex](#setZIndex-int-) | Grafiğin Z-sırasını gösteren bir int değeri ayarlar. Daha büyük ZIndex değerine sahip bir grafik, daha küçük ZIndex değerine sahip grafiğin üzerine yerleştirilir. ZIndex negatif olabilir. Negatif ZIndex değerine sahip grafik, sayfadaki metnin arkasına yerleştirilir. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Bu örneği klonlar. Sanal yöntem. Her zaman null döndürür.

**Returns:**
Null

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Paragrafın yatay hizalamasını alır

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * Bir paragrafın dipnot olup olmadığını alır veya ayarlar. Varsayılan false'tur.(pdf oluşturma için) / * / *

**Returns:**
boolean değeri /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Paragraf için dış kenar boşluğunu alır (pdf oluşturma için)

**Returns:**
MarginInfo değeri

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Paragrafın dikey hizalamasını alır

**Returns:**
VerticalAlignment öğesi @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

Grafiğin Z-sırasını gösteren bir int değer alır. Daha büyük ZIndex değerine sahip bir grafik, daha küçük ZIndex değerine sahip grafiğin üzerine yerleştirilir. ZIndex negatif olabilir. Negatif ZIndex değerine sahip grafik, sayfadaki metnin arkasına yerleştirilir.

**Returns:**
int değer

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

Bu paragrafın bir sonraki sütunda olup olmayacağını gösteren bir bool değer alır veya ayarlar. Varsayılan false'tur.(pdf oluşturma için)

**Returns:**
boolean değer

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

Paragrafın satır içi olup olmadığını alır. Varsayılan false'tur.(pdf oluşturma için)

**Returns:**
boolean değer

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır. Varsayılan değer false'tur. (pdf oluşturma için)

**Returns:**
boolean değer

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını gösteren bir boolean değeri alır. Varsayılan değer false'tur. (pdf oluşturma için)

**Returns:**
boolean değer

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

Bu paragrafın bir sonraki sütunda olup olmayacağını gösteren bir bool değer alır veya ayarlar. Varsayılan false'tur.(pdf oluşturma için)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Paragrafın yatay hizalamasını ayarlar

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Hipermetin bağlantısını ayarlar (pdf oluşturucu için).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

Paragrafın satır içi olmasını ayarlar. Varsayılan değer false'tur. (pdf oluşturma için)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir boolean değeri ayarlar. Varsayılan değer false'tur. (pdf oluşturma için)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını gösteren bir boolean değeri ayarlar. Varsayılan değer false'tur. (pdf oluşturma için)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Paragraf için dış kenar boşluğunu ayarlar (pdf oluşturma için)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Paragrafın dikey hizalamasını ayarlar

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

Grafiğin Z-sırasını gösteren bir int değeri ayarlar. Daha büyük ZIndex değerine sahip bir grafik, daha küçük ZIndex değerine sahip grafiğin üzerine yerleştirilir. ZIndex negatif olabilir. Negatif ZIndex değerine sahip grafik, sayfadaki metnin arkasına yerleştirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
