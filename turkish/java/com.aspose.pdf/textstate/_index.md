---
title: "TextState"
linktitle: "TextState"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir metnin metin durumunu temsil eder"
type: docs
weight: 5340
url: /tr/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

Bir metnin metin durumunu temsil eder

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | Varsayılan yazı tipinin boşluk karakteri genişliklerindeki sekme varsayılan değeri. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextState](#TextState--) | Metin durumu nesnesi oluşturur. |
| [TextState](#TextState-java.awt.Color-) | Metin durumu nesnesi oluşturur. |
| [TextState](#TextState-java.awt.Color-double-) | Metin durumu nesnesi oluşturur. |
| [TextState](#TextState-double-) | Yazı tipi boyutu belirtimiyle metin durumu nesnesi oluşturur. |
| [TextState](#TextState-java.lang.String-) | Metin durumu nesnesi oluşturur. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | Metin durumu nesnesi oluşturur. |
| [TextState](#TextState-java.lang.String-double-) | Metin durumu nesnesi oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Başka bir textState'ten ayarları uygular </p> <hr> <p> Yalnızca açıkça değiştirilen özellikler kopyalanacaktır. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Dikdörtgen için yazı tipi boyutunu hesaplar. |
| [getBackgroundColor](#getBackgroundColor--) | <p> Metnin arka plan rengini alır. </p> <hr> <p> Değerin belge içinde bir metin özelliği olarak korunmadığını unutmayın. BackgroundColor özelliği alıcısı, o nesne için daha önce BackgroundColor ayarlayıcısı ile açıkça ayarlanmışsa çalışır. Bu özellik, çalışma zamanında mevcut oluşturma/değiştirme süreci bağlamında kullanılır. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | Metnin karakter aralığını alır. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Metnin CoordinateOrigin'ını alır veya ayarlar. CoordinateOrigin Descender ise, metnin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. CoordinateOrigin BaseLine ise, metnin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek renderlanabilir. Bu durumda, daha iyi metin renderlaması için CoordinateOrigin BaseLine seçilebilir. |
| [getFont](#getFont--) | Metnin yazı tipini alır. |
| [getfontSize](#getfontSize--) | getfontSize metodunu temsil eder |
| [getFontSize](#getFontSize--) | Metnin yazı tipi boyutunu alır. |
| [getFontStyle](#getFontStyle--) | Metnin yazı tipi stilini ayarlar. |
| [getForegroundColor](#getForegroundColor--) | Metnin ön plan rengini alır. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Metnin yatay hizalamasını alır. </p> <hr> <p> HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. TextState.HorizontalAlignment özelliğinin yalnızca yeni belge oluşturma senaryolarında çalıştığını unutmayın. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Metnin yatay ölçeklemesini alır. |
| [getLineSpacing](#getLineSpacing--) | <p> Metnin satır aralığını alır. </p> |
| [getRenderingMode](#getRenderingMode--) | Metnin renderleme modunu alır veya ayarlar. |
| [getStrokingColor](#getStrokingColor--) | Metnin ön plan rengini alır veya ayarlar. |
| [getTabTag](#getTabTag--) | <p> Bu etiketi metinde sekme tanımlamak için yerleştirebilirsiniz. </p> <hr> <p> Bu, yalnızca {@code TabStops} ile birlikte kullanıldığında etkili olur. </p> |
| [getTextHeight](#getTextHeight--) | Metin yüksekliğini alır. |
| [getWordSpacing](#getWordSpacing--) | Metnin kelime aralığını alır. |
| [isInvisible](#isInvisible--) | Metnin görünmezliğini alır. Bu, temelde {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) durumunu yansıtır, ancak bazı özel durumlar (örneğin kırpma) hariçtir. |
| [isStrikeOut](#isStrikeOut--) | Metin için üstü çiziliyi alır, {@code TextFragment} nesnesi tarafından temsil edilir. |
| [isSubscript](#isSubscript--) | Metnin alt simgesini alır veya ayarlar. |
| [isSuperscript](#isSuperscript--) | Metnin üst simgesini alır. |
| [isUnderline](#isUnderline--) | Metin için alt çizgiyi alır, {@code TextFragment} nesnesi tarafından temsil edilir. |
| [measureHeight](#measureHeight-char-) | Karakter yüksekliğini ölçer. |
| [measureString](#measureString-java.lang.String-) | Dizgeyi ölçer. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> Dizgeyi ölçer. </p> <hr> <p> insideLine, dizgenin bitmediğini gösterir. Eğer dizgenin bir kısmı ölçülüyorsa - insideLine true olmalıdır. Eğer bütün dizge ölçülüyorsa insideLine false olmalıdır. Başka bir deyişle: insideLine = true olduğunda yalnızca karakter genişlikleri dikkate alınır. insideLine = false olduğunda ek dönüşümler dikkate alınmaz. dizgenin sonu doğru şekilde işlenir - italik dönüşüm dikkate alınır. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Metnin arka plan rengini ayarlar. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Metnin karakter aralığını ayarlar. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Metnin CoordinateOrigin'ını alır veya ayarlar. CoordinateOrigin Descender ise, metnin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. CoordinateOrigin BaseLine ise, metnin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek renderlanabilir. Bu durumda, daha iyi metin renderlaması için CoordinateOrigin BaseLine seçilebilir. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Metnin yazı tipini alır. |
| [setFontSize](#setFontSize-float-) | Metnin yazı tipi boyutunu ayarlar. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | Metnin yazı tipi boyutunu bastırılmış güncelleme ile ayarlar. |
| [setFontStyle](#setFontStyle-int-) | Metnin yazı tipi stilini ayarlar. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Metnin yazı tipini bastırılmış güncelleme ile alır. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Metnin ön plan rengini ayarlar. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Metin için yatay hizalamayı ayarlar. </p> <hr> <p> HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. Yalnızca yeni belge oluşturma senaryolarında TextState.HorizontalAlignment özelliğinin çalıştığını unutmayın. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Metnin yatay ölçeklendirmesini ayarlar. |
| [setInvisible](#setInvisible-boolean-) | Metnin görünmezliğini ayarlar. Bu temelde {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) durumunu yansıtır, bazı özel durumlar (örneğin kırpma) dışında. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Metnin satır aralığını ayarlar. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Metnin renderleme modunu alır veya ayarlar. |
| [setStrikeOut](#setStrikeOut-boolean-) | Metin için üstü çiziliyi ayarlar, {@code TextFragment} nesnesiyle temsil edilir. |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Metnin ön plan rengini alır veya ayarlar. |
| [setSubscript](#setSubscript-boolean-) | Metnin alt simgesini alır veya ayarlar. |
| [setSuperscript](#setSuperscript-boolean-) | Metnin üst simgesini ayarlar. |
| [setUnderline](#setUnderline-boolean-) | Metin için alt çizgiyi ayarlar, {@code TextFragment} nesnesiyle temsil edilir. |
| [setWordSpacing](#setWordSpacing-float-) | Metnin kelime aralığını ayarlar. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

Varsayılan yazı tipinin boşluk karakteri genişliklerindeki sekme varsayılan değeri.

### TextState {#TextState--}
```
public TextState()
```

Metin durumu nesnesi oluşturur.

### TextState {#TextState-java.awt.Color-}
Metin durumu nesnesi oluşturur.

### TextState {#TextState-java.awt.Color-double-}
Metin durumu nesnesi oluşturur.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

Yazı tipi boyutu belirtimiyle metin durumu nesnesi oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontSize |  | Yazı tipi boyutu. |

### TextState {#TextState-java.lang.String-}
Metin durumu nesnesi oluşturur.

### TextState {#TextState-java.lang.String-boolean-boolean-}
Metin durumu nesnesi oluşturur.

### TextState {#TextState-java.lang.String-double-}
Metin durumu nesnesi oluşturur.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Başka bir textState'ten ayarları uygular </p> <hr> <p> Yalnızca açıkça değiştirilen özellikler kopyalanacaktır. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
Dikdörtgen için yazı tipi boyutunu hesaplar.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> Metnin arka plan rengini alır. </p> <hr> <p> Değerin belge içinde bir metin özelliği olarak korunmadığını unutmayın. BackgroundColor özelliği alıcısı, o nesne için daha önce BackgroundColor ayarlayıcısı ile açıkça ayarlanmışsa çalışır. Bu özellik, çalışma zamanında mevcut oluşturma/değiştirme süreci bağlamında kullanılır. </p>

**Returns:**
Renk değeri

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Metnin karakter aralığını alır.

**Returns:**
float değer

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Metnin CoordinateOrigin'ını alır veya ayarlar. CoordinateOrigin Descender ise, metnin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. CoordinateOrigin BaseLine ise, metnin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek renderlanabilir. Bu durumda, daha iyi metin renderlaması için CoordinateOrigin BaseLine seçilebilir.

**Returns:**
CoordinateOrigin öğesi

### getFont {#getFont--}
```
public Font getFont()
```

Metnin yazı tipini alır.

**Returns:**
Yazı tipi nesnesi

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

getfontSize metodunu temsil eder

**Returns:**
float değer

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Metnin yazı tipi boyutunu alır.

**Returns:**
float değer

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Metnin yazı tipi stilini ayarlar.

**Returns:**
FontStyles öğesi @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Metnin ön plan rengini alır.

**Returns:**
Renk değeri

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Metnin yatay hizalamasını alır. </p> <hr> <p> HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. TextState.HorizontalAlignment özelliğinin yalnızca yeni belge oluşturma senaryolarında çalıştığını unutmayın. </p>

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Metnin yatay ölçeklemesini alır.

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
TextRenderingMode öğesi @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Metnin ön plan rengini alır veya ayarlar.

**Returns:**
Renk örneği

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> Bu etiketi metinde sekme tanımlamak için yerleştirebilirsiniz. </p> <hr> <p> Bu, yalnızca {@code TabStops} ile birlikte kullanıldığında etkili olur. </p>

**Returns:**
Dize değeri "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Metin yüksekliğini alır.

**Returns:**
float değer

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Metnin kelime aralığını alır.

**Returns:**
float değer

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Metnin görünmezliğini alır. Bu, temelde {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) durumunu yansıtır, ancak bazı özel durumlar (örneğin kırpma) hariçtir.

**Returns:**
boolean değer

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Metin için üstü çiziliyi alır, {@code TextFragment} nesnesi tarafından temsil edilir.

**Returns:**
boolean değer

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Metnin alt simgesini alır veya ayarlar.

**Returns:**
boolean değer

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Metnin üst simgesini alır.

**Returns:**
boolean değer

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Metin için alt çizgiyi alır, {@code TextFragment} nesnesi tarafından temsil edilir.

**Returns:**
boolean değer

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
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

### measureString {#measureString-java.lang.String-boolean-}
<p> Dizgeyi ölçer. </p> <hr> <p> insideLine, dizgenin bitmediğini gösterir. Eğer dizgenin bir kısmı ölçülüyorsa - insideLine true olmalıdır. Eğer bütün dizge ölçülüyorsa insideLine false olmalıdır. Başka bir deyişle: insideLine = true olduğunda yalnızca karakter genişlikleri dikkate alınır. insideLine = false olduğunda ek dönüşümler dikkate alınmaz. dizgenin sonu doğru şekilde işlenir - italik dönüşüm dikkate alınır. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Metnin arka plan rengini ayarlar.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Metnin karakter aralığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Metnin CoordinateOrigin'ını alır veya ayarlar. CoordinateOrigin Descender ise, metnin Y koordinatı yazı tipinin en düşük noktasına karşılık gelir. CoordinateOrigin BaseLine ise, metnin Y koordinatı yazı tipinin temel çizgisine karşılık gelir. Varsayılan değer Descender'dır. Yazı tipinin Descent değeri çok büyükse, metin diğer yazı tiplerinden daha yüksek renderlanabilir. Bu durumda, daha iyi metin renderlaması için CoordinateOrigin BaseLine seçilebilir.

### setFont {#setFont-com.aspose.pdf.Font-}
Metnin yazı tipini alır.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Metnin yazı tipi boyutunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

Metnin yazı tipi boyutunu bastırılmış güncelleme ile ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Metnin yazı tipi stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | FontStyles değeri @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
Metnin yazı tipini bastırılmış güncelleme ile alır.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Metnin ön plan rengini ayarlar.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Metin için yatay hizalamayı ayarlar. </p> <hr> <p> HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. Yalnızca yeni belge oluşturma senaryolarında TextState.HorizontalAlignment özelliğinin çalıştığını unutmayın. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Metnin yatay ölçeklendirmesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Metnin görünmezliğini ayarlar. Bu temelde {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) durumunu yansıtır, bazı özel durumlar (örneğin kırpma) dışında.

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
Metnin ön plan rengini alır veya ayarlar.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Metnin alt simgesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Metnin üst simgesini ayarlar.

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
