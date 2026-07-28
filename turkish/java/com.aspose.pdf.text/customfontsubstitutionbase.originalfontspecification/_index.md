---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Orijinal yazı tipi spesifikasyonunu temsil eder. </p> <hr> <p> Orijinal yazı tipiyle ilgili bilgileri, örneğin , bayrak gibi, sağlar. Ayrıca, değişimin gerçekleşip gerçekleşmeyeceğini kontrol etmeye yardımcı olan bir bayrak da sağlar. </p>"
type: docs
weight: 20
url: /tr/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Orijinal yazı tipi tanımını temsil eder. </p> <hr> <p> Orijinal yazı tipine ilişkin bilgi sağlar, örneğin , bayrak. Ayrıca ikamenin yazı tipiyle gerçekleşip gerçekleşmeyeceğini kontrol etmeye yardımcı olan bir bayrak sağlar ve kullanıcı varsayılan ikame mantığını geçersiz kılabilir. </p>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Yeni OriginalFontSpecification nesnesini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Orijinal yazı tipi adını alır. |
| [isEmbedded](#isEmbedded--) | Yazı tipinin gömülü olup olmadığını gösteren bir değeri alır. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Değişimin kaçınılmaz olduğunu gösteren bir değeri alır. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Yeni OriginalFontSpecification nesnesini başlatır.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Orijinal yazı tipi adını alır.

**Returns:**
String değeri

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Yazı tipinin gömülü olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Değişimin kaçınılmaz olduğunu gösteren bir değeri alır. </p>

**Returns:**
boolean değer <hr> <p> Orijinal yazı tipinin yokluğu nedeniyle veya bazı görev bağlamında orijinal yazı tipi kullanılamadığı durumlarda değişim istendiğinde true döndürür. Kullanıcı bayrağı görmezden gelir ve yazı tipini değiştirmezse - varsayılan yazı tipi değiştirme prosedürü uygulanır. Ancak, kullanıcıya standart yazı tipi değiştirme prosedürünü değiştirme ve sisteme daha iyi bir yazı tipi ayarlama fırsatı sunar. Orijinal yazı tipi mevcut, geçerli ve kullanıcıya değiştirme izni verildiğinde false döndürür. </p>
