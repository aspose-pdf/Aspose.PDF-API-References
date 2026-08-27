---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Aspose.PDF for Java API Referansı"
description: "HTML parçacığını temsil eder."
type: docs
weight: 1950
url: /tr/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

HTML parçacığını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | HtmlFragment sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | html fragment'ı klonlar. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | Bu sınıf örneğine HTML yüklemek (ve işlemek) için kullanılacak HtmlLoadOptions değerini alır. Bu, bu veya o örnek için HTML içe aktarma ayarının belirli bir şekilde kullanılmasının gerektiği durumlarda (ör. bu veya o örnek, içe aktarılan HTML için belirli bir BasePath kullanmalı veya harici kaynakların belirli bir yükleyicisini kullanmalı) kullanılmalıdır. Parametre varsayılan (null) ise, standart HTML yükleme seçenekleri kullanılacaktır. |
| [getRectangle](#getRectangle--) | HtmlFragment'in dikdörtgenini alır. |
| [getTextState](#getTextState--) | Yazı tipini alır veya ayarlar. |
| [isBreakWords](#isBreakWords--) | Kelime kırılmasını alır veya ayarlar. |
| [isParagraphHasMargin](#isParagraphHasMargin--) | Paragrafın varsayılan kenar boşluğuna sahip olup olmadığını alır veya ayarlar; aksi takdirde kenar boşluğu 0'dır. |
| [setBreakWords](#setBreakWords-boolean-) | Kelime kırılmasını alır veya ayarlar. |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Bu sınıf örneğine HTML yüklemek (ve işlemek) için kullanılacak HtmlLoadOptions değerini ayarlar. Bu, bu veya o örnek için HTML içe aktarma ayarının belirli bir şekilde kullanılmasının gerektiği durumlarda (ör. bu veya o örnek, içe aktarılan HTML için belirli bir BasePath kullanmalı veya harici kaynakların belirli bir yükleyicisini kullanmalı) kullanılmalıdır. Parametre varsayılan (null) ise, standart HTML yükleme seçenekleri kullanılacaktır. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | Paragrafın varsayılan kenar boşluğuna sahip olup olmadığını alır veya ayarlar; aksi takdirde kenar boşluğu 0'dır. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Yazı tipini alır veya ayarlar. |

### HtmlFragment {#HtmlFragment-java.lang.String-}
HtmlFragment sınıfının yeni bir örneğini başlatır.

### deepClone {#deepClone--}
```
public Object deepClone()
```

html fragment'ı klonlar.

**Returns:**
Klonlanmış html fragment nesnesi.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

Bu sınıf örneğine HTML yüklemek (ve işlemek) için kullanılacak HtmlLoadOptions değerini alır. Bu, bu veya o örnek için HTML içe aktarma ayarının belirli bir şekilde kullanılmasının gerektiği durumlarda (ör. bu veya o örnek, içe aktarılan HTML için belirli bir BasePath kullanmalı veya harici kaynakların belirli bir yükleyicisini kullanmalı) kullanılmalıdır. Parametre varsayılan (null) ise, standart HTML yükleme seçenekleri kullanılacaktır.

**Returns:**
HtmlLoadOptions değeri

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

HtmlFragment'in dikdörtgenini alır.

**Returns:**
java.awt.geom.Rectangle2D.Float instance

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Yazı tipini alır veya ayarlar.

**Returns:**
TextState nesnesi

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

Kelime kırılmasını alır veya ayarlar.

**Returns:**
boolean değer

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

Paragrafın varsayılan kenar boşluğuna sahip olup olmadığını alır veya ayarlar; aksi takdirde kenar boşluğu 0'dır.

**Returns:**
boolean değer

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

Kelime kırılmasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
Bu sınıf örneğine HTML yüklemek (ve işlemek) için kullanılacak HtmlLoadOptions değerini ayarlar. Bu, bu veya o örnek için HTML içe aktarma ayarının belirli bir şekilde kullanılmasının gerektiği durumlarda (ör. bu veya o örnek, içe aktarılan HTML için belirli bir BasePath kullanmalı veya harici kaynakların belirli bir yükleyicisini kullanmalı) kullanılmalıdır. Parametre varsayılan (null) ise, standart HTML yükleme seçenekleri kullanılacaktır.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

Paragrafın varsayılan kenar boşluğuna sahip olup olmadığını alır veya ayarlar; aksi takdirde kenar boşluğu 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Yazı tipini alır veya ayarlar.
