---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Bir metin parçacığının metin durumunu temsil eder. </p> <hr> <pre> Örnek, {@code TextState} nesnesi ile metnin renk ve yazı tipi boyutunu nasıl değiştireceğini gösterir. // Open."
type: docs
weight: 5150
url: /tr/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> Bir metin parçacığının metin durumunu temsil eder. </p> <hr> <pre> Örnek, {@code TextState} nesnesi ile metnin renk ve yazı tipi boyutunu nasıl değiştireceğini gösterir. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metnin aşağıdaki özelliklerini değiştirmek için bir yol sağlar: yazı tipi ({@code TextFragmentState.Font} özelliği) yazı tipi boyutu ({@code TextFragmentState.FontSize} özelliği) yazı tipi stili ({@code TextFragmentState.FontStyle} özelliği) ön plan rengi ({@code TextFragmentState.ForegroundColor} özelliği) arka plan rengi ({@code TextFragmentState.BackgroundColor} özelliği) </p> <p> {@code TextFragmentState} özelliklerini değiştirmenin {@code TextFragment.Segments} koleksiyonunu içsel olarak etkileyebileceğini unutmayın; çünkü TextFragment bir toplama nesnesidir ve iç segmentleri yeniden düzenleyebilir veya tek bir segmente birleştirebilir. {@code TextFragment.Segments} koleksiyonunun değişmemesini istiyorsanız, lütfen iç segmentleri tek tek değiştirin. </p> @see TextFragmentAbsorber @see IDocument

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | Belirtilen {@code TextFragment} nesnesi ile {@code TextFragmentState} nesnesinin yeni bir örneğini başlatır. Bu {@code TextFragmentState} başlatması desteklenmez. TextFragmentState yalnızca {@code TextFragment.TextState} özelliği ile kullanılabilir. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Başka bir textState'ten ayarları uygular </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Başka bir textState'ten ayarları uygular |
| [getBackgroundColor](#getBackgroundColor--) | Metnin arka plan rengini, {@code TextFragment} nesnesi tarafından temsil edilen, ayarlar |
| [getCharacterSpacing](#getCharacterSpacing--) | Metnin karakter aralığını alır, {@code TextFragment} nesnesiyle temsil edilir. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Metnin CoordinateOrigin'ını alır veya ayarlar. CoordinateOrigin Descender ise, metnin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. CoordinateOrigin BaseLine ise, metnin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek renderlanabilir. Bu durumda, daha iyi metin renderlaması için CoordinateOrigin BaseLine seçilebilir. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | Metin dikdörtgen kenarlığının çizilip çizilmediği bayrağını alır. |
| [getFont](#getFont--) | Metnin yazı tipini alır, {@code TextFragment} nesnesiyle temsil edilir |
| [getFontSize](#getFontSize--) | Metnin yazı tipi boyutunu alır, {@code TextFragment} nesnesiyle temsil edilir |
| [getFontStyle](#getFontStyle--) | Metnin yazı tipi stilini ayarlar, {@code TextFragment} nesnesiyle temsil edilir |
| [getForegroundColor](#getForegroundColor--) | Metnin ön plan rengini alır, {@code TextFragment} nesnesiyle temsil edilir |
| [getFormattingOptions](#getFormattingOptions--) | Biçimlendirme seçeneklerini alır veya ayarlar. Seçeneklerin ayarlanması yalnızca üretici senaryolarında etkili olur. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Metin için yatay hizalamayı alır. </p> <hr> <p> HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. TextFragmentState.VerticalAlignment özelliğinin yalnızca yeni belge oluşturma senaryolarında çalıştığını unutmayın. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Metnin yatay ölçeklendirmesini alır, {@code TextFragment} nesnesiyle temsil edilir. |
| [getLineSpacing](#getLineSpacing--) | <p> Metnin satır aralığını alır. </p> |
| [getRenderingMode](#getRenderingMode--) | Metnin renderleme modunu alır veya ayarlar. |
| [getRotation](#getRotation--) | Dönüş açısını derece cinsinden alır veya ayarlar. |
| [getStrokingColor](#getStrokingColor--) | Alır veya ayarlar {@code TextFragment} renderlemesinin renk çizim işlemlerini (metni çizme, dikdörtgen kenarlığı) |
| [getTabStops](#getTabStops--) | <p> Metin için sekme duraklarını alır. </p> <hr> <p> Tabstops özelliğinin yalnızca yeni belge oluşturma senaryolarında çalıştığını unutmayın. Tabstops, {@code TextFragment} başlatması sırasında eklenebilir. Tabstops, metinden önce oluşturulmalıdır. </p> |
| [getTextHeight](#getTextHeight--) | Metnin yüksekliğini alır, {@code TextFragment} nesnesiyle temsil edilir |
| [getWordSpacing](#getWordSpacing--) | Metnin kelime aralığını alır. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | Giriş dizesinin tanımlı dikdörtgenin içine yerleştirilebileceğini kontrol eder. |
| [isInvisible](#isInvisible--) | Metnin görünmezliğini alır. |
| [isStrikeOut](#isStrikeOut--) | Metin için üstü çizili özelliğini alır veya ayarlar, {@link TextFragment} nesnesiyle temsil edilir |
| [isSubscript](#isSubscript--) | Metnin alt simgesini alır veya ayarlar, {@code TextFragment} nesnesiyle temsil edilir. |
| [isSuperscript](#isSuperscript--) | Metnin üst simgesini alır veya ayarlar, {@code TextFragment} nesnesiyle temsil edilir. |
| [isUnderline](#isUnderline--) | Metin için alt çizgiyi alır veya ayarlar, {@link TextFragment} nesnesiyle temsil edilir |
| [measureHeight](#measureHeight-char-) | Karakter yüksekliğini ölçer. |
| [measureString](#measureString-java.lang.String-) | Dizgeyi ölçer. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Metnin arka plan rengini ayarlar, TextFragment nesnesiyle temsil edilir |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Metnin karakter aralığını ayarlar, {@code TextFragment} nesnesiyle temsil edilir. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Metnin CoordinateOrigin'ını alır veya ayarlar. CoordinateOrigin Descender ise, metnin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. CoordinateOrigin BaseLine ise, metnin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek renderlanabilir. Bu durumda, daha iyi metin renderlaması için CoordinateOrigin BaseLine seçilebilir. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | Metin dikdörtgen kenarlığının çizilip çizilmediği bayrağını ayarlar. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Metnin yazı tipini ayarlar, {@code TextFragment} nesnesiyle temsil edilir |
| [setFontSize](#setFontSize-float-) | Metnin yazı tipi boyutunu ayarlar, {@code TextFragment} nesnesiyle temsil eder |
| [setFontStyle](#setFontStyle-int-) | Metnin yazı tipi stilini ayarlar, {@link TextFragment} nesnesiyle temsil edilir |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Metnin ön plan rengini ayarlar, {@code TextFragment} nesnesi tarafından temsil edilir |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Biçimlendirme seçeneklerini alır veya ayarlar. Seçeneklerin ayarlanması yalnızca üretici senaryolarında etkili olur. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Metin için yatay hizalamayı ayarlar. </p> <hr> <p> HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. Yalnızca yeni belge oluşturma senaryolarında TextFragmentState.VerticalAlignment özelliğinin çalıştığını unutmayın. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Metnin yatay ölçeklendirmesini ayarlar, {@code TextFragment} nesnesi tarafından temsil edilir. |
| [setInvisible](#setInvisible-boolean-) | Metnin görünmezliğini ayarlar. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Metnin satır aralığını ayarlar. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Metnin renderleme modunu alır veya ayarlar. |
| [setRotation](#setRotation-double-) | Dönüş açısını derece cinsinden alır veya ayarlar. |
| [setStrikeOut](#setStrikeOut-boolean-) | Metin için üstü çiziliyi ayarlar, {@code TextFragment} nesnesiyle temsil edilir. |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Alır veya ayarlar {@code TextFragment} renderlemesinin renk çizim işlemlerini (metni çizme, dikdörtgen kenarlığı) |
| [setSubscript](#setSubscript-boolean-) | Metnin alt simgesini alır veya ayarlar, {@code TextFragment} nesnesiyle temsil edilir. |
| [setSuperscript](#setSuperscript-boolean-) | Metnin üst simgesini alır veya ayarlar, {@code TextFragment} nesnesiyle temsil edilir. |
| [setUnderline](#setUnderline-boolean-) | Metin için alt çizgiyi ayarlar, {@code TextFragment} nesnesiyle temsil edilir. |
| [setWordSpacing](#setWordSpacing-float-) | Metnin kelime aralığını ayarlar. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
Belirtilen {@code TextFragment} nesnesi ile {@code TextFragmentState} nesnesinin yeni bir örneğini başlatır. Bu {@code TextFragmentState} başlatması desteklenmez. TextFragmentState yalnızca {@code TextFragment.TextState} özelliği ile kullanılabilir.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Başka bir textState'ten ayarları uygular </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
Başka bir textState'ten ayarları uygular

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Metnin arka plan rengini, {@code TextFragment} nesnesi tarafından temsil edilen, ayarlar

**Returns:**
değer Color nesnesi

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Metnin karakter aralığını alır, {@code TextFragment} nesnesiyle temsil edilir.

**Returns:**
float değer

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Metnin CoordinateOrigin'ını alır veya ayarlar. CoordinateOrigin Descender ise, metnin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. CoordinateOrigin BaseLine ise, metnin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek renderlanabilir. Bu durumda, daha iyi metin renderlaması için CoordinateOrigin BaseLine seçilebilir.

**Returns:**
CoordinateOrigin öğesi

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

Metin dikdörtgen kenarlığının çizilip çizilmediği bayrağını alır.

**Returns:**
boolean değer

### getFont {#getFont--}
```
public Font getFont()
```

Metnin yazı tipini alır, {@code TextFragment} nesnesiyle temsil edilir

**Returns:**
Yazı tipi değeri

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Metnin yazı tipi boyutunu alır, {@code TextFragment} nesnesiyle temsil edilir

**Returns:**
float değer

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Metnin yazı tipi stilini ayarlar, {@code TextFragment} nesnesiyle temsil edilir

**Returns:**
FontStyles öğesi @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Metnin ön plan rengini alır, {@code TextFragment} nesnesiyle temsil edilir

**Returns:**
Color nesnesi

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Biçimlendirme seçeneklerini alır veya ayarlar. Seçeneklerin ayarlanması yalnızca üretici senaryolarında etkili olur.

**Returns:**
TextFormattingOptions örneği

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Metin için yatay hizalamayı alır. </p> <hr> <p> HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. TextFragmentState.VerticalAlignment özelliğinin yalnızca yeni belge oluşturma senaryolarında çalıştığını unutmayın. </p>

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Metnin yatay ölçeklendirmesini alır, {@code TextFragment} nesnesiyle temsil edilir.

**Returns:**
float değer

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> Metnin satır aralığını alır. </p>

**Returns:**
float değer <hr> <p> Değerin belge içinde bir metin özelliği olarak korunmadığını unutmayın. LineSpacing özelliği alıcısı, nesne için daha önce LineSpacing ayarlayıcısı ile açıkça ayarlanmışsa çalışır. Özellik, çalışma zamanında mevcut oluşturma/değiştirme süreci bağlamında kullanılır. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

Metnin renderleme modunu alır veya ayarlar.

**Returns:**
TextRenderingMode öğesi

### getRotation {#getRotation--}
```
public double getRotation()
```

Dönüş açısını derece cinsinden alır veya ayarlar.

**Returns:**
double değer

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Alır veya ayarlar {@code TextFragment} renderlemesinin renk çizim işlemlerini (metni çizme, dikdörtgen kenarlığı)

**Returns:**
Renk örneği

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> Metin için sekme duraklarını alır. </p> <hr> <p> Tabstops özelliğinin yalnızca yeni belge oluşturma senaryolarında çalıştığını unutmayın. Tabstops, {@code TextFragment} başlatması sırasında eklenebilir. Tabstops, metinden önce oluşturulmalıdır. </p>

**Returns:**
TabStops nesnesi

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Metnin yüksekliğini alır, {@code TextFragment} nesnesiyle temsil edilir

**Returns:**
float değer

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Metnin kelime aralığını alır.

**Returns:**
float değer

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
Giriş dizesinin tanımlı dikdörtgenin içine yerleştirilebileceğini kontrol eder.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Metnin görünmezliğini alır.

**Returns:**
boolean değer

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Metin için üstü çizili özelliğini alır veya ayarlar, {@link TextFragment} nesnesiyle temsil edilir

**Returns:**
boolean değer

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Metnin alt simgesini alır veya ayarlar, {@code TextFragment} nesnesiyle temsil edilir.

**Returns:**
boolean değer

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Metnin üst simgesini alır veya ayarlar, {@code TextFragment} nesnesiyle temsil edilir.

**Returns:**
değer boolean değer

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Metin için alt çizgiyi alır veya ayarlar, {@link TextFragment} nesnesiyle temsil edilir

**Returns:**
boolean değer

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
```

Karakter yüksekliğini ölçer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| karakter |  | Ölçülecek karakter. |

**Returns:**
Yazı tipinden alabiliyorsak karakterin yüksekliği; aksi takdirde 0.

### measureString {#measureString-java.lang.String-}
Dizgeyi ölçer.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Metnin arka plan rengini ayarlar, TextFragment nesnesiyle temsil edilir

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Metnin karakter aralığını ayarlar, {@code TextFragment} nesnesiyle temsil edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Metnin CoordinateOrigin'ını alır veya ayarlar. CoordinateOrigin Descender ise, metnin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. CoordinateOrigin BaseLine ise, metnin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek renderlanabilir. Bu durumda, daha iyi metin renderlaması için CoordinateOrigin BaseLine seçilebilir.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

Metin dikdörtgen kenarlığının çizilip çizilmediği bayrağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setFont {#setFont-com.aspose.pdf.Font-}
Metnin yazı tipini ayarlar, {@code TextFragment} nesnesiyle temsil edilir

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Metnin yazı tipi boyutunu ayarlar, {@code TextFragment} nesnesiyle temsil eder

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Metnin yazı tipi stilini ayarlar, {@link TextFragment} nesnesiyle temsil edilir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Metnin ön plan rengini ayarlar, {@code TextFragment} nesnesi tarafından temsil edilir

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Biçimlendirme seçeneklerini alır veya ayarlar. Seçeneklerin ayarlanması yalnızca üretici senaryolarında etkili olur.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Metin için yatay hizalamayı ayarlar. </p> <hr> <p> HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. Yalnızca yeni belge oluşturma senaryolarında TextFragmentState.VerticalAlignment özelliğinin çalıştığını unutmayın. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Metnin yatay ölçeklendirmesini ayarlar, {@code TextFragment} nesnesi tarafından temsil edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Metnin görünmezliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> Metnin satır aralığını ayarlar. </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer <hr> <p> Değerin belge içinde bir metin özelliği olarak korunmadığını unutmayın. LineSpacing özelliği alıcısı, nesne için daha önce LineSpacing ayarlayıcısı ile açıkça ayarlanmışsa çalışır. Özellik, çalışma zamanında mevcut oluşturma/değiştirme süreci bağlamında kullanılır. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
Metnin renderleme modunu alır veya ayarlar.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Dönüş açısını derece cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

Metin için üstü çiziliyi ayarlar, {@code TextFragment} nesnesiyle temsil edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
Alır veya ayarlar {@code TextFragment} renderlemesinin renk çizim işlemlerini (metni çizme, dikdörtgen kenarlığı)

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Metnin alt simgesini alır veya ayarlar, {@code TextFragment} nesnesiyle temsil edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Metnin üst simgesini alır veya ayarlar, {@code TextFragment} nesnesiyle temsil edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

Metin için alt çizgiyi ayarlar, {@code TextFragment} nesnesiyle temsil edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

Metnin kelime aralığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |
