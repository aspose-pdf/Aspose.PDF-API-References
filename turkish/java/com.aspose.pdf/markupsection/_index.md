---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir işaretleme bölümünü temsil eder - metin içeren ve görsel olarak diğer metin bloklarından ayrılabilen bir sayfanın dikdörtgen bölgesi."
type: docs
weight: 2890
url: /tr/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

Bir işaretleme bölümünü temsil eder - metin içeren ve görsel olarak diğer metin bloklarından ayrılabilen bir sayfanın dikdörtgen bölgesi.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFragments](#getFragments--) | <p> Bölüm içinde bulunan boş olmayan {@code TextFragment} nesnelerinin koleksiyonu. </p><hr> {@code TextFragment} nesnesi, arama gerçekleşen metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir. |
| [getParagraphs](#getParagraphs--) | Bölüm içinde bulunan {@code MarkupParagraph} nesnelerinin koleksiyonu. |
| [getRectangle](#getRectangle--) | Bölüm dikdörtgeni |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Bölüm içinde bulunan boş olmayan {@code TextFragment} nesnelerinin koleksiyonu. </p><hr> {@code TextFragment} nesnesi, arama gerçekleşen metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir.

**Returns:**
TextFragment örneklerinin listesi

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Bölüm içinde bulunan {@code MarkupParagraph} nesnelerinin koleksiyonu.

**Returns:**
MarkupParagraph örneklerinin listesi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Bölüm dikdörtgeni

**Returns:**
Dikdörtgen örneği
