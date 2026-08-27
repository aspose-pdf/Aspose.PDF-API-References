---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin paragraflarının bir absorber nesnesini temsil eder. Metin araması gerçekleştirir ve {@code TextParagraphAbsorber.TextParagraphs} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar."
type: docs
weight: 5220
url: /tr/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

Metin paragraflarının bir absorber nesnesini temsil eder. Metin araması gerçekleştirir ve {@code TextParagraphAbsorber.TextParagraphs} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> Dikdörtgen koleksiyonu ile {@code TextParagraphAbsorber} sınıfının yeni bir örneğini başlatır. </p> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRectangles](#getRectangles--) | PDF belgesi veya sayfasında metin paragraflarını aramak için {@code TextParagraphAbsorber} tarafından kullanılan dikdörtgenleri alır. |
| [getTextParagraphs](#getTextParagraphs--) | {@code TextParagraph} nesneleriyle sunulan arama oluşumlarının koleksiyonunu alır. |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | PDF belgesi veya sayfasında metin paragraflarını aramak için {@code TextParagraphAbsorber} tarafından kullanılan dikdörtgenleri ayarlar. |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | {@code TextParagraph} nesneleriyle sunulan arama oluşumlarının koleksiyonunu ayarlar. |
| [visit](#visit-com.aspose.pdf.Page-) | Belirtilen sayfada arama gerçekleştirir. |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> Dikdörtgen koleksiyonu ile {@code TextParagraphAbsorber} sınıfının yeni bir örneğini başlatır. </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

PDF belgesi veya sayfasında metin paragraflarını aramak için {@code TextParagraphAbsorber} tarafından kullanılan dikdörtgenleri alır.

**Returns:**
dikdörtgen dizisi

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

{@code TextParagraph} nesneleriyle sunulan arama oluşumlarının koleksiyonunu alır.

**Returns:**
TextParagraphCollection değeri

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
PDF belgesi veya sayfasında metin paragraflarını aramak için {@code TextParagraphAbsorber} tarafından kullanılan dikdörtgenleri ayarlar.

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
{@code TextParagraph} nesneleriyle sunulan arama oluşumlarının koleksiyonunu ayarlar.

### visit {#visit-com.aspose.pdf.Page-}
Belirtilen sayfada arama gerçekleştirir.
