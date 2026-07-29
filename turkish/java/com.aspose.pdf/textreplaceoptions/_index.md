---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin değiştirme seçeneklerini temsil eder"
type: docs
weight: 5250
url: /tr/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

Metin değiştirme seçeneklerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | Varsayılan ayarlama ve kapsam için {@code TextReplaceOptions} nesnesinin yeni bir örneğini başlatır: ReplaceAdjustment.None ve Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | Belirtilen değiştirme sonrası eylem için {@code TextReplaceOptions} nesnesinin yeni bir örneğini başlatır. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | Varsayılan ayarlama ve kapsam için {@code TextReplaceOptions} nesnesinin yeni bir örneğini başlatır: ReplaceAdjustment.None ve Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Varsayılan ayarlama ve kapsam için {@code TextReplaceOptions} nesnesinin yeni bir örneğini başlatır: ReplaceAdjustment.None ve Scope.REPLACE_FIRST |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | Değiştirme ayarlaması yeni bir metin satırı oluşturmak için zorlanırsa kullanılan satır aralığı değerini alır veya ayarlar. Beklenen değer, değiştirilen metnin yazı tipi boyutunun çarpanı olur. Varsayılan değer 1.2'dir. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}) tarafından tanımlanan sınırlar içinde sığacak şekilde yazı tipi boyutunu ayarlama politikasını alır veya ayarlar. |
| [getLeftAdjustment](#getLeftAdjustment--) | TextReplaceOptions kullanılırken değiştirilen metin için sol konum ayarlamasını alır: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | Değiştirmeden sonra metni sığdırmak için dikdörtgeni alır veya ayarlar. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | Metin parçacığının daha kısa bir şekilde değiştirilmesinden sonra yapılacak eylemi alır. |
| [getReplaceScope](#getReplaceScope--) | Değiştirme metin işleminin uygulandığı kapsamı alır |
| [getRightAdjustment](#getRightAdjustment--) | TextReplaceOptions kullanılırken değiştirilen metin için sağ konum ayarlamasını ayarlar veya alır: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | Metin değiştirmeden sonra sayfadaki metni ayarlarken ayrı paragrafları yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | Değiştirme ayarlaması yeni bir metin satırı oluşturmak için zorlanırsa kullanılan satır aralığı değerini alır veya ayarlar. Beklenen değer, değiştirilen metnin yazı tipi boyutunun çarpanı olur. Varsayılan değer 1.2'dir. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ) tarafından tanımlanan sınırlar içinde sığacak şekilde yazı tipi boyutunu ayarlama politikasını alır veya ayarlar. |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | Metin değiştirmeden sonra sayfadaki metni ayarlarken ayrı paragrafları yoksayma durumunu gösteren bir değeri alır veya ayarlar. |
| [setLeftAdjustment](#setLeftAdjustment-double-) | TextReplaceOptions kullanılırken değiştirilen metin için sol konum ayarlamasını ayarlar veya alır: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Değiştirmeden sonra metni sığdırmak için dikdörtgeni alır veya ayarlar. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | Metin parçacığının daha kısa bir şekilde değiştirilmesinden sonra yapılacak eylemi ayarlar. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Değiştirme metin işleminin uygulandığı kapsamı ayarlar |
| [setRightAdjustment](#setRightAdjustment-double-) | TextReplaceOptions kullanılırken değiştirilen metin için sağ konum ayarlamasını ayarlar: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

Varsayılan ayarlama ve kapsam için {@code TextReplaceOptions} nesnesinin yeni bir örneğini başlatır: ReplaceAdjustment.None ve Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

Belirtilen değiştirme sonrası eylem için {@code TextReplaceOptions} nesnesinin yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ayarlama |  | ReplaceAdjustment nesnesi. @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
Varsayılan ayarlama ve kapsam için {@code TextReplaceOptions} nesnesinin yeni bir örneğini başlatır: ReplaceAdjustment.None ve Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
Varsayılan ayarlama ve kapsam için {@code TextReplaceOptions} nesnesinin yeni bir örneğini başlatır: ReplaceAdjustment.None ve Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

Değiştirme ayarlaması yeni bir metin satırı oluşturmak için zorlanırsa kullanılan satır aralığı değerini alır veya ayarlar. Beklenen değer, değiştirilen metnin yazı tipi boyutunun çarpanı olur. Varsayılan değer 1.2'dir.

**Returns:**
double değer

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

{@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}) tarafından tanımlanan sınırlar içinde sığacak şekilde yazı tipi boyutunu ayarlama politikasını alır veya ayarlar.

**Returns:**
FontSizeAdjustment öğesi

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

TextReplaceOptions kullanılırken değiştirilen metin için sol konum ayarlamasını alır: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double değer

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

Değiştirmeden sonra metni sığdırmak için dikdörtgeni alır veya ayarlar.

**Returns:**
Dikdörtgen örneği

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

Metin parçacığının daha kısa bir şekilde değiştirilmesinden sonra yapılacak eylemi alır.

**Returns:**
ReplaceAdjustment öğesi @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

Değiştirme metin işleminin uygulandığı kapsamı alır

**Returns:**
int değer @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

TextReplaceOptions kullanılırken değiştirilen metin için sağ konum ayarlamasını ayarlar veya alır: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double değer

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

Metin değiştirmeden sonra sayfadaki metni ayarlarken ayrı paragrafları yoksayma durumunu gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean değer

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

Değiştirme ayarlaması yeni bir metin satırı oluşturmak için zorlanırsa kullanılan satır aralığı değerini alır veya ayarlar. Beklenen değer, değiştirilen metnin yazı tipi boyutunun çarpanı olur. Varsayılan değer 1.2'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ) tarafından tanımlanan sınırlar içinde sığacak şekilde yazı tipi boyutunu ayarlama politikasını alır veya ayarlar.

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

Metin değiştirmeden sonra sayfadaki metni ayarlarken ayrı paragrafları yoksayma durumunu gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

TextReplaceOptions kullanılırken değiştirilen metin için sol konum ayarlamasını ayarlar veya alır: - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Değiştirmeden sonra metni sığdırmak için dikdörtgeni alır veya ayarlar.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

Metin parçacığının daha kısa bir şekilde değiştirilmesinden sonra yapılacak eylemi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ReplaceAdjustment öğesi @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
Değiştirme metin işleminin uygulandığı kapsamı ayarlar

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

TextReplaceOptions kullanılırken değiştirilen metin için sağ konum ayarlamasını ayarlar: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |
