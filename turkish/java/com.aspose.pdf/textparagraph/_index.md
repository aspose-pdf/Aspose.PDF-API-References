---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Metin paragraflarını çok satırlı metin nesnesi olarak temsil eder. </p> <hr> <pre> Örnek, metin paragraf nesnesinin nasıl oluşturulacağını ve Pdf sayfasına nasıl ekleneceğini gösterir. Document doc.</pre>"
type: docs
weight: 5200
url: /tr/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> Metin paragraflarını çok satırlı metin nesnesi olarak temsil eder. </p> <hr> <pre> Bu örnek, bir metin paragrafı nesnesi oluşturmayı ve bunu Pdf sayfasına eklemeyi gösterir. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // metin paragrafı oluştur TextParagraph paragraph = new TextParagraph(); // paragraf dikdörtgenini ayarla paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // kelime kaydırma seçeneklerini ayarla paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // dize satırlarını ekle paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // paragrafı TextBuilder ile Pdf sayfasına ekle TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // Pdf belgesini kaydet doc.save(outFile); </pre>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextParagraph](#TextParagraph--) | Oluşturur {@code TextParagraph} nesnesi. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | Metin satırı ekler |
| [appendLine](#appendLine-java.lang.String-float-) | Metin satırı ekler. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Metin durumu parametreleriyle metin satırı ekler. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Metin durumu parametreleriyle metin satırı ekler |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | Metin durumu parametreleriyle metin satırı ekler. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Metin durumu parametreleriyle metin satırı ekler. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Metin durumu parametreleriyle metin satırı ekler |
| [beginEdit](#beginEdit--) | TextParagraph düzenlemesini başlatır. <p> TextParagraph doldurulmasının performansını artırır. Herhangi bir yerleşim hesabı, EndEdit yöntemi çağrılana kadar askıya alınır. <p> Yöntem çağrısının iç içe olamayacağını unutmayın. </p> |
| [endEdit](#endEdit--) | TextParagraph düzenlemesini sonlandırır. <p> TextParagraph doldurulmasının performansını artırır. Herhangi bir yerleşim hesabı, EndEdit yöntemi çağrılana kadar askıya alınır. <p> Yöntem çağrısının iç içe olamayacağını unutmayın. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | Sonraki satırların girinti değerini alır veya ayarlar. Sıfır olmayan bir değere ayarlanırsa, FormattingOptions.SubsequentLinesIndent değerine göre bir avantaj sağlar. |
| [getFormattingOptions](#getFormattingOptions--) | Biçimlendirme seçeneklerini alır. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Paragrafın Rectangle'ı içindeki metnin yatay hizalamasını alır. HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. |
| [getHyphenSymbol](#getHyphenSymbol--) | Heceleme işleminde kullanılan tire sembolünü alır. Heceleme sembolü varsayılan olarak "-" dir. Tire çizimini (sarma prosedürü hâlâ etkinken) ortadan kaldırmak için HyphenSymbol için boş bir dize string.Empty ayarlayın. |
| [getMargin](#getMargin--) | Dolgu değerini al. |
| [getPosition](#getPosition--) | Paragrafın konumunu alır. |
| [getRectangle](#getRectangle--) | Paragrafın dikdörtgenini alır. |
| [getRotation](#getRotation--) | Dönüş açısını derece cinsinden alır veya ayarlar. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Sonraki satırların girinti değerini alır. |
| [getTextRectangle](#getTextRectangle--) | Paragrafa yerleştirilen metnin dikdörtgenini alır. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> Paragrafın {@code Rectangle} içindeki metnin dikey hizalamasını alır. </p> |
| [isJustify](#isJustify--) | Metnin iki yana hizalanıp hizalanmadığını gösteren değeri alır. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Metin paragrafı için arka plan rengini ayarlar. |
| [setBackgroundMode](#setBackgroundMode-int-) | Metin paragrafı için arka plan modunu ayarlar |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Sonraki satırların girinti değerini alır veya ayarlar. Sıfır olmayan bir değere ayarlanırsa, FormattingOptions.SubsequentLinesIndent değerine göre bir avantaj sağlar. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Biçimlendirme seçeneklerini ayarlar. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Paragrafın Rectangle'ı içindeki metnin yatay hizalamasını ayarlar. HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | Heceleme işleminde kullanılan tire sembolünü ayarlar. Heceleme sembolü varsayılan olarak "-" dir. Tire çizimini (sarma prosedürü hâlâ etkinken) ortadan kaldırmak için HyphenSymbol için boş bir dize string.Empty ayarlayın. |
| [setJustify](#setJustify-boolean-) | Metnin iki yana hizalanıp hizalanmadığını gösteren değeri ayarlar. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Dolgu değerini ayarlar. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Paragrafın dönüşünü ayarlar. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | Eski kod uyumluluk modunu ayarlar |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Paragrafın konumunu ayarlar. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Paragrafın dikdörtgenini ayarlar. |
| [setRotation](#setRotation-double-) | Dönüş açısını derece cinsinden alır veya ayarlar. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Sonraki satırların girinti değerini ayarlar. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Paragrafın {@code Rectangle} içindeki metnin dikey hizalamasını ayarlar. VerticalAlignment.None, VerticalAlignment.Bottom'a eşittir. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

Oluşturur {@code TextParagraph} nesnesi.

### appendLine {#appendLine-java.lang.String-}
Metin satırı ekler

### appendLine {#appendLine-java.lang.String-float-}
Metin satırı ekler.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
Metin durumu parametreleriyle metin satırı ekler.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
Metin durumu parametreleriyle metin satırı ekler

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
Metin durumu parametreleriyle metin satırı ekler.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
Metin durumu parametreleriyle metin satırı ekler.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
Metin durumu parametreleriyle metin satırı ekler

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

TextParagraph düzenlemesini başlatır. <p> TextParagraph doldurulmasının performansını artırır. Herhangi bir yerleşim hesabı, EndEdit yöntemi çağrılana kadar askıya alınır. <p> Yöntem çağrısının iç içe olamayacağını unutmayın. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

TextParagraph düzenlemesini sonlandırır. <p> TextParagraph doldurulmasının performansını artırır. Herhangi bir yerleşim hesabı, EndEdit yöntemi çağrılana kadar askıya alınır. <p> Yöntem çağrısının iç içe olamayacağını unutmayın. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Sonraki satırların girinti değerini alır veya ayarlar. Sıfır olmayan bir değere ayarlanırsa, FormattingOptions.SubsequentLinesIndent değerine göre bir avantaj sağlar.

**Returns:**
float değer

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Biçimlendirme seçeneklerini alır.

**Returns:**
TextFormattingOptions nesnesi

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Paragrafın Rectangle'ı içindeki metnin yatay hizalamasını alır. HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir.

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

Heceleme işleminde kullanılan tire sembolünü alır. Heceleme sembolü varsayılan olarak "-" dir. Tire çizimini (sarma prosedürü hâlâ etkinken) ortadan kaldırmak için HyphenSymbol için boş bir dize string.Empty ayarlayın.

**Returns:**
String değeri

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Dolgu değerini al.

**Returns:**
MarginInfo değeri

### getPosition {#getPosition--}
```
public Position getPosition()
```

Paragrafın konumunu alır.

**Returns:**
Konum değeri

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Paragrafın dikdörtgenini alır.

**Returns:**
Rectangle nesnesi

### getRotation {#getRotation--}
```
public double getRotation()
```

Dönüş açısını derece cinsinden alır veya ayarlar.

**Returns:**
double değer

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Sonraki satırların girinti değerini alır.

**Returns:**
float değer

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

Paragrafa yerleştirilen metnin dikdörtgenini alır.

**Returns:**
Rectangle nesnesi

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> Paragrafın {@code Rectangle} içindeki metnin dikey hizalamasını alır. </p>

**Returns:**
VerticalAlignment değeri @see VerticalAlignment <hr> <p> VerticalAlignment.None, VerticalAlignment.Bottom'a eşittir. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Metnin iki yana hizalanıp hizalanmadığını gösteren değeri alır.

**Returns:**
boolean değer

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Metin paragrafı için arka plan rengini ayarlar.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

Metin paragrafı için arka plan modunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değeri @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Sonraki satırların girinti değerini alır veya ayarlar. Sıfır olmayan bir değere ayarlanırsa, FormattingOptions.SubsequentLinesIndent değerine göre bir avantaj sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Biçimlendirme seçeneklerini ayarlar.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Paragrafın Rectangle'ı içindeki metnin yatay hizalamasını ayarlar. HorizontalAlignment.None, HorizontalAlignment.Left'e eşittir.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
Heceleme işleminde kullanılan tire sembolünü ayarlar. Heceleme sembolü varsayılan olarak "-" dir. Tire çizimini (sarma prosedürü hâlâ etkinken) ortadan kaldırmak için HyphenSymbol için boş bir dize string.Empty ayarlayın.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Metnin iki yana hizalanıp hizalanmadığını gösteren değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Dolgu değerini ayarlar.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Paragrafın dönüşünü ayarlar.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

Eski kod uyumluluk modunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setPosition {#setPosition-com.aspose.pdf.Position-}
Paragrafın konumunu ayarlar.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Paragrafın dikdörtgenini ayarlar.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Dönüş açısını derece cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Sonraki satırların girinti değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Paragrafın {@code Rectangle} içindeki metnin dikey hizalamasını ayarlar. VerticalAlignment.None, VerticalAlignment.Bottom'a eşittir.
