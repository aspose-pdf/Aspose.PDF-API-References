---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yazı tiplerini sistem yazı tipleriyle ikame eden bir yazı tipi ikame stratejisi sınıfını temsil eder."
type: docs
weight: 110
url: /tr/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

Yazı tiplerini sistem yazı tipleriyle ikame eden bir yazı tipi ikame stratejisi sınıfını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | {@code SystemFontsSubstitution} sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | Varsayılan ikame fontunu alır veya ayarlar. Font, başka geçerli bir ikame bulunamadığında ve başlangıç fontu hedef ikame kategorisine ({@code FontCategories}) ait olduğunda kullanılır. |
| [getFontCategories](#getFontCategories--) | Sistem fontlarıyla ikame edilmesi gereken ikame font kategorilerini alır veya ayarlar. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | Varsayılan ikame fontunu alır veya ayarlar. Font, başka geçerli bir ikame bulunamadığında ve başlangıç fontu hedef ikame kategorisine ({@code FontCategories}) ait olduğunda kullanılır. |
| [setFontCategories](#setFontCategories-int-) | Sistem fontlarıyla ikame edilmesi gereken ikame font kategorilerini alır veya ayarlar. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

{@code SystemFontsSubstitution} sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontCategories |  | Sistem yazı tipleriyle değiştirilecek hedef yazı tipi kategorileri |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

Varsayılan ikame fontunu alır veya ayarlar. Font, başka geçerli bir ikame bulunamadığında ve başlangıç fontu hedef ikame kategorisine ({@code FontCategories}) ait olduğunda kullanılır.

**Returns:**
Yazı tipi nesnesi

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

Sistem fontlarıyla ikame edilmesi gereken ikame font kategorilerini alır veya ayarlar.

**Returns:**
SubstitutionFontCategories öğesi @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
Varsayılan ikame fontunu alır veya ayarlar. Font, başka geçerli bir ikame bulunamadığında ve başlangıç fontu hedef ikame kategorisine ({@code FontCategories}) ait olduğunda kullanılır.

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

Sistem fontlarıyla ikame edilmesi gereken ikame font kategorilerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | SubstitutionFontCategories öğesi @see SubstitutionFontCategories |
