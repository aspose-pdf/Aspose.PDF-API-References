---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metinsel damgayı temsil eder."
type: docs
weight: 5320
url: /tr/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

Metinsel damgayı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Yeni bir {@code TextStamp} sınıfı örneğini formattedText nesnesiyle başlatır |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | Yeni bir {@code TextStamp} sınıfı örneğini formattedText nesnesiyle başlatır |
| [TextStamp](#TextStamp-java.lang.String-) | Yeni bir {@code TextStamp} sınıfı örneğini başlatır. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Yeni bir TextStamp sınıfı örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | Yazı tipi boyutu hassasiyeti otomatik olarak ayarlanır. Varsayılan değer: 0.1; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | Etkinleştirildiğinde, yazı tipi boyutu {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) ve {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}) boyutundaki damga dikdörtgenine sığacak şekilde otomatik olarak ayarlanır. Varsayılan genişlik ve yükseklik sayfa dikdörtgeninden türetilir. |
| [getDefaultFont](#getDefaultFont--) | Varsayılan yazı tipini döndürür |
| [getDefaultFontSize](#getDefaultFontSize--) | Varsayılan Yazı Tipi Boyutu |
| [getDraw](#getDraw--) | Bu özellik, damganın sayfada nasıl çizileceğini belirler. Draw = true ise damga grafik operatörleri olarak çizilir ve draw = false ise damga metin olarak çizilir. |
| [getFontSize](#getFontSize--) | Damga yerleştirildikten sonraki gerçek yazı tipi boyutu. ('AutoAdjustFontSizeToFitStampRectangle' seçeneği etkinse, yapıcı üzerinden sağlanan başlangıç yazı tipi boyutundan farklı olabilir.) |
| [getHeight](#getHeight--) | Sayfadaki damganın istenen yüksekliği. |
| [getMaxRowWidth](#getMaxRowWidth--) | WordWrap seçeneği için azami satır yüksekliği. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Yazı tiplerinin istenen karakterleri içermemesi durumunda davranışı tanımlayan modu alır veya ayarlar. |
| [getReplacementFont](#getReplacementFont--) | Kullanıcı yazı tipi gerekli karakteri içermiyorsa, yerine kullanılacak yazı tipini alır veya ayarlar. |
| [getTextAlignment](#getTextAlignment--) | Damga içindeki metnin hizalaması. |
| [getTextState](#getTextState--) | Damganın metin özelliklerini alır. Ayrıntılar için {@code TextState}'e bakın. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | Metin yerleştirme için koordinat başlangıcını tanımlar. TreatYIndentAsBaseLine = true ise (Draw = true olduğunda varsayılan) YIndent değeri metin taban çizgisi olarak kabul edilir. TreatYIndentAsBaseLine = false ise (Draw = false olduğunda varsayılan) YIndent değeri metnin alt (alçak) çizgisi olarak kabul edilir. |
| [getValue](#getValue--) | Sayfada damga olarak kullanılan dize değerini alır. |
| [getWidth](#getWidth--) | Sayfadaki damganın istenen genişliği. |
| [getWordWrapMode](#getWordWrapMode--) | Metin işleme için kelime kaydırma modunu alır veya ayarlar. |
| [isJustify](#isJustify--) | Metin hizalamasını tanımlar. Bu özellik true olarak ayarlanırsa, metnin hem sol hem de sağ kenarları hizalanır. Varsayılan değer: false. |
| [isScale](#isScale--) | Metnin ölçeklendirilmesini tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde ölçeklendirilir. |
| [isWordWrap](#isWordWrap--) | Kelime kaydırmayı tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde birden fazla satıra bölünür. Varsayılan değer: false. |
| [put](#put-com.aspose.pdf.Page-) | Sayfaya metinsel damga ekler. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | Yazı tipi boyutu hassasiyeti otomatik olarak ayarlanır. Varsayılan değer: 0.1; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | Etkinleştirildiğinde, yazı tipi boyutu {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) ve {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}) boyutundaki damga dikdörtgenine sığacak şekilde otomatik olarak ayarlanır. Varsayılan genişlik ve yükseklik sayfa dikdörtgeninden türetilir. |
| [setDraw](#setDraw-boolean-) | Bu özellik, damganın sayfada nasıl çizileceğini belirler. Draw = true ise damga grafik operatörleri olarak çizilir ve draw = false ise damga metin olarak çizilir. |
| [setHeight](#setHeight-double-) | Sayfadaki damganın istenen yüksekliği. |
| [setJustify](#setJustify-boolean-) | Metin hizalamasını tanımlar. Bu özellik true olarak ayarlanırsa, metnin hem sol hem de sağ kenarları hizalanır. Varsayılan değer: false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | WordWrap seçeneği için azami satır yüksekliği. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | Yazı tiplerinin istenen karakterleri içermemesi durumunda davranışı tanımlayan modu alır veya ayarlar. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Kullanıcı yazı tipi gerekli karakteri içermiyorsa, yerine kullanılacak yazı tipini alır veya ayarlar. |
| [setScale](#setScale-boolean-) | Metnin ölçeklendirilmesini tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde ölçeklendirilir. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Damga içindeki metnin hizalaması. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | Metin yerleştirme için koordinat başlangıcını tanımlar. TreatYIndentAsBaseLine = true ise (Draw = true olduğunda varsayılan) YIndent değeri metin taban çizgisi olarak kabul edilir. TreatYIndentAsBaseLine = false ise (Draw = false olduğunda varsayılan) YIndent değeri metnin alt (alçak) çizgisi olarak kabul edilir. |
| [setValue](#setValue-java.lang.String-) | Sayfada damga olarak kullanılan dize değerini ayarlar. |
| [setWidth](#setWidth-double-) | Sayfadaki damganın istenen genişliği. |
| [setWordWrap](#setWordWrap-boolean-) | Kelime kaydırmayı tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde birden fazla satıra bölünür. Varsayılan değer: false. |
| [setWordWrapMode](#setWordWrapMode-int-) | Metin işleme için kelime kaydırma modunu alır veya ayarlar. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
Yeni bir {@code TextStamp} sınıfı örneğini formattedText nesnesiyle başlatır

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
Yeni bir {@code TextStamp} sınıfı örneğini formattedText nesnesiyle başlatır

### TextStamp {#TextStamp-java.lang.String-}
Yeni bir {@code TextStamp} sınıfı örneğini başlatır.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
Yeni bir TextStamp sınıfı örneğini başlatır.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

Yazı tipi boyutu hassasiyeti otomatik olarak ayarlanır. Varsayılan değer: 0.1;

**Returns:**
float değer

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

Etkinleştirildiğinde, yazı tipi boyutu {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) ve {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}) boyutundaki damga dikdörtgenine sığacak şekilde otomatik olarak ayarlanır. Varsayılan genişlik ve yükseklik sayfa dikdörtgeninden türetilir.

**Returns:**
boolean değer

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

Varsayılan yazı tipini döndürür

**Returns:**
com.aspose.pdf.Font nesnesi

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

Varsayılan Yazı Tipi Boyutu

**Returns:**
float değer

### getDraw {#getDraw--}
```
public boolean getDraw()
```

Bu özellik, damganın sayfada nasıl çizileceğini belirler. Draw = true ise damga grafik operatörleri olarak çizilir ve draw = false ise damga metin olarak çizilir.

**Returns:**
boolean değer

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Damga yerleştirildikten sonraki gerçek yazı tipi boyutu. ('AutoAdjustFontSizeToFitStampRectangle' seçeneği etkinse, yapıcı üzerinden sağlanan başlangıç yazı tipi boyutundan farklı olabilir.)

**Returns:**
float değer

### getHeight {#getHeight--}
```
public double getHeight()
```

Sayfadaki damganın istenen yüksekliği.

**Returns:**
double değer

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

WordWrap seçeneği için azami satır yüksekliği.

**Returns:**
double değer

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

Yazı tiplerinin istenen karakterleri içermemesi durumunda davranışı tanımlayan modu alır veya ayarlar.

**Returns:**
NoCharacterAction öğesi

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Kullanıcı yazı tipi gerekli karakteri içermiyorsa, yerine kullanılacak yazı tipini alır veya ayarlar.

**Returns:**
Font örneği

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Damga içindeki metnin hizalaması.

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Damganın metin özelliklerini alır. Ayrıntılar için {@code TextState}'e bakın.

**Returns:**
TextState öğesi

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

Metin yerleştirme için koordinat başlangıcını tanımlar. TreatYIndentAsBaseLine = true ise (Draw = true olduğunda varsayılan) YIndent değeri metin taban çizgisi olarak kabul edilir. TreatYIndentAsBaseLine = false ise (Draw = false olduğunda varsayılan) YIndent değeri metnin alt (alçak) çizgisi olarak kabul edilir.

**Returns:**
boolean değer

### getValue {#getValue--}
```
public String getValue()
```

Sayfada damga olarak kullanılan dize değerini alır.

**Returns:**
String değeri

### getWidth {#getWidth--}
```
public double getWidth()
```

Sayfadaki damganın istenen genişliği.

**Returns:**
double değer

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

Metin işleme için kelime kaydırma modunu alır veya ayarlar.

**Returns:**
WordWrapMode öğesi

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Metin hizalamasını tanımlar. Bu özellik true olarak ayarlanırsa, metnin hem sol hem de sağ kenarları hizalanır. Varsayılan değer: false.

**Returns:**
boolean değer

### isScale {#isScale--}
```
public boolean isScale()
```

Metnin ölçeklendirilmesini tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde ölçeklendirilir.

**Returns:**
boolean değer

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

Kelime kaydırmayı tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde birden fazla satıra bölünür. Varsayılan değer: false.

**Returns:**
bool değeri @deprecated "WordWrapMode yerine kullanın."

### put {#put-com.aspose.pdf.Page-}
Sayfaya metinsel damga ekler.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

Yazı tipi boyutu hassasiyeti otomatik olarak ayarlanır. Varsayılan değer: 0.1;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

Etkinleştirildiğinde, yazı tipi boyutu {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) ve {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}) boyutundaki damga dikdörtgenine sığacak şekilde otomatik olarak ayarlanır. Varsayılan genişlik ve yükseklik sayfa dikdörtgeninden türetilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

Bu özellik, damganın sayfada nasıl çizileceğini belirler. Draw = true ise damga grafik operatörleri olarak çizilir ve draw = false ise damga metin olarak çizilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Sayfadaki damganın istenen yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Metin hizalamasını tanımlar. Bu özellik true olarak ayarlanırsa, metnin hem sol hem de sağ kenarları hizalanır. Varsayılan değer: false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

WordWrap seçeneği için azami satır yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

Yazı tiplerinin istenen karakterleri içermemesi durumunda davranışı tanımlayan modu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | NoCharacterAction öğesi |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Kullanıcı yazı tipi gerekli karakteri içermiyorsa, yerine kullanılacak yazı tipini alır veya ayarlar.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

Metnin ölçeklendirilmesini tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde ölçeklendirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Damga içindeki metnin hizalaması.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

Metin yerleştirme için koordinat başlangıcını tanımlar. TreatYIndentAsBaseLine = true ise (Draw = true olduğunda varsayılan) YIndent değeri metin taban çizgisi olarak kabul edilir. TreatYIndentAsBaseLine = false ise (Draw = false olduğunda varsayılan) YIndent değeri metnin alt (alçak) çizgisi olarak kabul edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setValue {#setValue-java.lang.String-}
Sayfada damga olarak kullanılan dize değerini ayarlar.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sayfadaki damganın istenen genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

Kelime kaydırmayı tanımlar. Bu özellik true olarak ayarlanır ve Width değeri belirtilirse, metin belirtilen genişliğe sığacak şekilde birden fazla satıra bölünür. Varsayılan değer: false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | bool değeri @deprecated "WordWrapMode yerine kullanın." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

Metin işleme için kelime kaydırma modunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | WordWrapMode öğesi @see WordWrapMode |
