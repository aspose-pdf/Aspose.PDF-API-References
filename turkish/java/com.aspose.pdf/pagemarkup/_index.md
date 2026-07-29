---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Aspose.PDF for Java API Referansı"
description: "{@code MarkupSection} ve {@code MarkupParagraph} koleksiyonlarıyla temsil edilen sayfa işaretlemesi."
type: docs
weight: 3420
url: /tr/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

{@code MarkupSection} ve {@code MarkupParagraph} koleksiyonlarıyla temsil edilen sayfa işaretlemesi.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNumber](#getNumber--) | İşlenen sayfa numarasını alır. |
| [getParagraphs](#getParagraphs--) | Sayfada bulunan {@code MarkupParagraph} koleksiyonunu alır. |
| [getRectangle](#getRectangle--) | İşlenen sayfa dikdörtgenini alır. |
| [getSections](#getSections--) | Sayfada bulunan {@code MarkupSection} koleksiyonunu alır. |
| [getTextFragments](#getTextFragments--) | <p> Sayfada bulunan {@code TextFragment} koleksiyonunu alır. </p><hr> {@code TextFragment} nesnesi, arama sonucundaki metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye olanak tanır. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Bir sonraki bölümün başlangıç metin satırlarının, önceki bölümün son paragrafının devamı olarak kabul edilip edilmediğini belirten değeri alır veya ayarlar. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Bir sonraki bölümün başlangıç metin satırlarının, önceki bölümün son paragrafının devamı olarak kabul edilip edilmediğini belirten değeri alır veya ayarlar. |

### getNumber {#getNumber--}
```
public int getNumber()
```

İşlenen sayfa numarasını alır.

**Returns:**
int değer

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Sayfada bulunan {@code MarkupParagraph} koleksiyonunu alır.

**Returns:**
MarkupParagraph örneklerinin listesi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

İşlenen sayfa dikdörtgenini alır.

**Returns:**
Rectangle nesnesi

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

Sayfada bulunan {@code MarkupSection} koleksiyonunu alır.

**Returns:**
MarkupSection örneklerinin listesi

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> Sayfada bulunan {@code TextFragment} koleksiyonunu alır. </p><hr> {@code TextFragment} nesnesi, arama sonucundaki metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye olanak tanır.

**Returns:**
TextFragment örneklerinin listesi

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Bir sonraki bölümün başlangıç metin satırlarının, önceki bölümün son paragrafının devamı olarak kabul edilip edilmediğini belirten değeri alır veya ayarlar.

**Returns:**
boolean değer

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Bir sonraki bölümün başlangıç metin satırlarının, önceki bölümün son paragrafının devamı olarak kabul edilip edilmediğini belirten değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
