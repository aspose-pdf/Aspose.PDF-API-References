---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir paragrafı temsil eder."
type: docs
weight: 2880
url: /tr/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

Bir paragrafı temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | Paragrafın devam ettiği sayfa numaralarının listesi. Aynı sayfada bir sonraki sütunda devam ediyorsa, paragrafın başladığı sayfa ile eşleşecektir. |
| [getFragments](#getFragments--) | <p> Paragrafın boş olmayan {@code TextFragment} nesnelerinin koleksiyonu. </p><hr> {@code TextFragment} nesnesi, arama sonucundaki metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir. |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> Paragrafın satırları. Her satır, metin parçacıklarının listesiyle temsil edilir. </p><hr> {@code TextFragment} nesnesi, arama sonucundaki metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir. |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | Paragrafı tanımlayan çokgenin noktaları. Başlangıç noktası paragrafın sol alt köşesidir. Sonraki noktalar ise saat yönünün tersine sıralanır. |
| [getSecondaryPoints](#getSecondaryPoints--) | Paragrafın devamını tanımlayan ikincil çokgenin noktaları. Paragraf bir sonraki sütunda veya sayfada devam ediyorsa null olmayacaktır. Başlangıç noktası paragrafın sol alt köşesidir. Sonraki noktalar ise saat yönünün tersine sıralanır. |
| [getText](#getText--) | Alır {@code string} metin nesnesini, {@code MarkupParagraph} nesnesinin temsil ettiği. |
| [setText](#setText-java.lang.String-) | Paragraf metnini alır veya ayarlar. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

Paragrafın devam ettiği sayfa numaralarının listesi. Aynı sayfada bir sonraki sütunda devam ediyorsa, paragrafın başladığı sayfa ile eşleşecektir.

**Returns:**
Integer listesi

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Paragrafın boş olmayan {@code TextFragment} nesnelerinin koleksiyonu. </p><hr> {@code TextFragment} nesnesi, arama sonucundaki metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir.

**Returns:**
TextFragment örneklerinin listesi

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> Paragrafın satırları. Her satır, metin parçacıklarının listesiyle temsil edilir. </p><hr> {@code TextFragment} nesnesi, arama sonucundaki metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir.

**Returns:**
TextFragment örneklerinin listesi

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Paragrafı tanımlayan çokgenin noktaları. Başlangıç noktası paragrafın sol alt köşesidir. Sonraki noktalar ise saat yönünün tersine sıralanır.

**Returns:**
Point örneklerinin dizisi

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

Paragrafın devamını tanımlayan ikincil çokgenin noktaları. Paragraf bir sonraki sütunda veya sayfada devam ediyorsa null olmayacaktır. Başlangıç noktası paragrafın sol alt köşesidir. Sonraki noktalar ise saat yönünün tersine sıralanır.

**Returns:**
Point[] listesi

### getText {#getText--}
```
public String getText()
```

Alır {@code string} metin nesnesini, {@code MarkupParagraph} nesnesinin temsil ettiği.

**Returns:**
String değeri

### setText {#setText-java.lang.String-}
Paragraf metnini alır veya ayarlar.
