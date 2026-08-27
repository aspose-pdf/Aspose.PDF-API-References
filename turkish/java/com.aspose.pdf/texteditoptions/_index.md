---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin düzenleme işlemlerinin seçeneklerini açıklar."
type: docs
weight: 4970
url: /tr/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

Metin düzenleme işlemlerinin seçeneklerini açıklar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * Belirtilen metin yeniden düzenleme modu için {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | Metin ekleme veya düzenleme sırasında dil dönüşümünün kullanılmasına izin veren değeri alır. true - gerekli olduğunda dil dönüşümü uygulanır (varsayılan değer). false - dil dönüşümü uygulanmaz. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | Düzenlenen metnin kırpma yolunun işlenmesi için modu alır. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | Yazı tipleri değiştirme senaryoları için davranışı tanımlayan modu alır. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | Dil dönüşümü senaryoları için davranışı tanımlayan modu alır. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Yazı tipleri istenen karakterleri içermediğinde davranışı tanımlayan modu alır. |
| [getReplacementFont](#getReplacementFont--) | Kullanıcı yazı tipi gerekli karakteri içermiyorsa, değiştirme için kullanılan yazı tipini alır veya ayarlar |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> Kaynak belgenin sayfasında metin alt çizgisi aramaya izin veren değeri alır veya ayarlar. </p> <p> (Eski) Lütfen bunun yerine TextSearchOptions.SearchForTextRelatedGraphics kullanın. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | Metin ekleme veya düzenleme sırasında dil dönüşümünün kullanılmasına izin veren değeri ayarlar. true - gerekli olduğunda dil dönüşümü uygulanır (varsayılan değer). false - dil dönüşümü uygulanmaz. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Düzenlenen metnin kırpma yolunun işlenmesi için modu alır. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Yazı tipleri değiştirme senaryoları için davranışı tanımlayan modu ayarlar. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Dil dönüşümü senaryoları için davranışı tanımlayan modu ayarlar. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Yazı tipleri istenen karakterleri içermediğinde davranışı tanımlayan modu ayarlar. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Kullanıcı yazı tipi gerekli karakteri içermiyorsa, değiştirme için kullanılan yazı tipini alır veya ayarlar |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> Kaynak belgenin sayfasında metin alt çizgisi aramaya izin veren değeri alır veya ayarlar. </p> <p> (Eski) Lütfen bunun yerine TextSearchOptions.SearchForTextRelatedGraphics kullanın. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * Belirtilen metin yeniden düzenleme modu için {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. / * / *

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
Varsayılan seçeneklerle {@code TextEditOptions} nesnesinin yeni bir örneğini başlatır. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

Metin ekleme veya düzenleme sırasında dil dönüşümünün kullanılmasına izin veren değeri alır. true - gerekli olduğunda dil dönüşümü uygulanır (varsayılan değer). false - dil dönüşümü uygulanmaz.

**Returns:**
boolean değer

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

Düzenlenen metnin kırpma yolunun işlenmesi için modu alır.

**Returns:**
ClippingPathsProcessingMode öğesi

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

Yazı tipleri değiştirme senaryoları için davranışı tanımlayan modu alır.

**Returns:**
FontReplace değeri @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

Dil dönüşümü senaryoları için davranışı tanımlayan modu alır.

**Returns:**
LanguageTransformation değeri @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

Yazı tipleri istenen karakterleri içermediğinde davranışı tanımlayan modu alır.

**Returns:**
NoCharacterAction değeri @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Kullanıcı yazı tipi gerekli karakteri içermiyorsa, değiştirme için kullanılan yazı tipini alır veya ayarlar

**Returns:**
Font örneği

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> Kaynak belgenin sayfasında metin alt çizgisi aramaya izin veren değeri alır veya ayarlar. </p> <p> (Eski) Lütfen bunun yerine TextSearchOptions.SearchForTextRelatedGraphics kullanın. </p>

**Returns:**
boolean değer

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

Metin ekleme veya düzenleme sırasında dil dönüşümünün kullanılmasına izin veren değeri ayarlar. true - gerekli olduğunda dil dönüşümü uygulanır (varsayılan değer). false - dil dönüşümü uygulanmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
Düzenlenen metnin kırpma yolunun işlenmesi için modu alır.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
Yazı tipleri değiştirme senaryoları için davranışı tanımlayan modu ayarlar.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Dil dönüşümü senaryoları için davranışı tanımlayan modu ayarlar.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Yazı tipleri istenen karakterleri içermediğinde davranışı tanımlayan modu ayarlar.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Kullanıcı yazı tipi gerekli karakteri içermiyorsa, değiştirme için kullanılan yazı tipini alır veya ayarlar

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> Kaynak belgenin sayfasında metin alt çizgisi aramaya izin veren değeri alır veya ayarlar. </p> <p> (Eski) Lütfen bunun yerine TextSearchOptions.SearchForTextRelatedGraphics kullanın. </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
