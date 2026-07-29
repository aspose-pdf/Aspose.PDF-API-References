---
title: "SimpleFontSubstitution"
linktitle: "SimpleFontSubstitution"
second_title: "Aspose.PDF for Java API Referansı"
description: "Basit bir yazı tipi ikame stratejisi için bir sınıfı temsil eder."
type: docs
weight: 90
url: /tr/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

Basit bir yazı tipi ikame stratejisi için bir sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | Yeni bir {@code SimpleFontSubstitution} sınıfı örneği başlatır. |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | Yeni bir {@code SimpleFontSubstitution} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Orijinal yazı tipi adını, {@code SubstitutionFontName} ile değiştirilecek şekilde alır. |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | unicode ikamesini döndürür |
| [getSubstitutionFontName](#getSubstitutionFontName--) | {@code OriginalFontName} öğesini değiştirecek yazı tipi adını alır. |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
Yeni bir {@code SimpleFontSubstitution} sınıfı örneği başlatır.

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
Yeni bir {@code SimpleFontSubstitution} sınıfı örneği başlatır.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Orijinal yazı tipi adını, {@code SubstitutionFontName} ile değiştirilecek şekilde alır.

**Returns:**
String değeri

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

unicode ikamesini döndürür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| unicode |  | char değeri |

**Returns:**
char değeri

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

{@code OriginalFontName} öğesini değiştirecek yazı tipi adını alır.

**Returns:**
String değeri
