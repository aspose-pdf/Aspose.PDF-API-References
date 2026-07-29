---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin biçimlendirme seçeneklerini temsil eder"
type: docs
weight: 5080
url: /tr/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

Metin biçimlendirme seçeneklerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | Tanımsız kelime kaydırma modu ile {@code TextFormattingOptions} nesnesinin yeni bir örneğini başlatır. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | Belirtilen kelime kaydırma modu için {@code TextFormattingOptions} nesnesinin yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | İlk satır girinti değerini alır veya ayarlar. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> Heceleme sürecinde kullanılan tire simgesini alır veya ayarlar. </p><hr> Tire çizimini ortadan kaldırmak (sarma prosedürü hâlâ etkin) lütfen HyphenSymbol için boş dize string.Empty ayarlayın. |
| [getLineSpacing](#getLineSpacing--) | Satır aralığı modunu alır. Varsayılan değer LineSpacingMode.FontSize'tir. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Sonraki satırların girinti değerini alır veya ayarlar. |
| [getWrapMode](#getWrapMode--) | Kelime kaydırma modunu alır. Varsayılan değer WordWrapMode.NoWrap'dir. |
| [setFirstLineIndent](#setFirstLineIndent-float-) | İlk satır girinti değerini alır veya ayarlar. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> Heceleme sürecinde kullanılan tire simgesini alır veya ayarlar. </p><hr> Tire çizimini ortadan kaldırmak (sarma prosedürü hâlâ etkin) lütfen HyphenSymbol için boş dize string.Empty ayarlayın. |
| [setLineSpacing](#setLineSpacing-int-) | Satır aralığı modunu ayarlar. Varsayılan değer LineSpacingMode.FontSize'tir. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Sonraki satırların girinti değerini alır veya ayarlar. |
| [setWrapMode](#setWrapMode-int-) | Kelime kaydırma modunu ayarlar. Varsayılan değer WordWrapMode.NoWrap'dir. |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

Tanımsız kelime kaydırma modu ile {@code TextFormattingOptions} nesnesinin yeni bir örneğini başlatır.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

Belirtilen kelime kaydırma modu için {@code TextFormattingOptions} nesnesinin yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| wrapMode |  | Kelime kaydırma modu. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

İlk satır girinti değerini alır veya ayarlar.

**Returns:**
float değer

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> Heceleme sürecinde kullanılan tire simgesini alır veya ayarlar. </p><hr> Tire çizimini ortadan kaldırmak (sarma prosedürü hâlâ etkin) lütfen HyphenSymbol için boş dize string.Empty ayarlayın.

**Returns:**
String değeri

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

Satır aralığı modunu alır. Varsayılan değer LineSpacingMode.FontSize'tir.

**Returns:**
int değer @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Sonraki satırların girinti değerini alır veya ayarlar.

**Returns:**
float değer

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Kelime kaydırma modunu alır. Varsayılan değer WordWrapMode.NoWrap'dir.

**Returns:**
WordWrapMode değeri @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

İlk satır girinti değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> Heceleme sürecinde kullanılan tire simgesini alır veya ayarlar. </p><hr> Tire çizimini ortadan kaldırmak (sarma prosedürü hâlâ etkin) lütfen HyphenSymbol için boş dize string.Empty ayarlayın.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

Satır aralığı modunu ayarlar. Varsayılan değer LineSpacingMode.FontSize'tir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Sonraki satırların girinti değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Kelime kaydırma modunu ayarlar. Varsayılan değer WordWrapMode.NoWrap'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | WordWrapMode değeri @see WordWrapMode |
