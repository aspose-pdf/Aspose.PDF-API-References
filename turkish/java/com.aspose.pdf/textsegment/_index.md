---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Pdf metninin segmentini temsil eder. </p> <hr> <pre> Örnek, {@code TextState} nesnesi ile metnin metin rengini ve yazı tipi boyutunu nasıl değiştireceğini gösterir. {@code"
type: docs
weight: 5300
url: /tr/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Pdf metninin segmentini temsil eder. </p> <hr> <pre> Örnek, {@code TextState} nesnesi ile {@code TextSegment} nesnesinin metin rengini ve yazı tipi boyutunu nasıl değiştireceğini gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Tüm "hello world" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun ilk metin segmentinin ön plan rengini değiştir absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // İlk metin oluşumunun ilk metin segmentinin yazı tipi boyutunu değiştir absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> Kısaca, {@code TextSegment} nesneleri {@code TextFragment} nesnesinin alt nesneleridir. Ayrıntılı olarak: {@code Aspose.Pdf} içindeki pdf belgesinin metni iki temel nesneyle temsil edilir: {@code TextFragment} ve {@code TextSegment} Aralarındaki farklar çoğunlukla bağlama bağlıdır. Aşağıdaki senaryoyu ele alalım. Kullanıcı, "hello world" metnini bulur, onunla işlem yapar, özelliklerini değiştirir, görüntüler vb. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> Pdf metninin fiziksel temsili çok karmaşıktır. "hello world" metni birkaç fiziksel bağımsız metin segmentinden oluşabilir. Aspose.PDF metin modeli temelde, {@code TextFragment} nesnesinin, kullanıcının sorgusunu temsil eden fiziksel {@code TextSegment} nesneleri kümesi üzerinde tek bir mantıksal işlem kümesi sağladığını belirler. Metin arama senaryosunda, {@code TextFragment} mantıksal "hello world" metin temsilidir ve {@code TextSegment} nesne koleksiyonu "hello world" metin nesnesini oluşturan tüm fiziksel segmentleri temsil eder. Dolayısıyla, {@code TextFragment} mantıksal metin temsiline yakındır. Ve {@code TextSegment} fiziksel metin temsiline yakındır. Açıkça her {@code TextSegment} nesnesi kendi yazı tipi, renkleme ve konumlandırma özelliklerine sahip olabilir. {@code TextFragment}, metni özellikleriyle değiştirmek için basit bir yol sunar: yazı tipini ayarla, yazı tipi boyutunu ayarla, yazı tipi rengini ayarla vb. Bu arada {@code TextSegment} nesneleri erişilebilirdir ve kullanıcılar {@code TextSegment} nesneleriyle bağımsız olarak işlem yapabilir. </p>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> TextSegment nesnesi oluşturur. </p> <hr> <pre> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> TextSegment nesnesi oluşturur. </p> <hr> <pre> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | Metin konumunu, {@code TextSegment} nesnesiyle temsil edilen metin için alır. Position yapısının YIndent özelliği, metin segmentinin temel çizgi koordinatını temsil eder. |
| [getCharacters](#getCharacters--) | Metin segmentindeki karakterler hakkında bilgi temsil eden CharInfo nesnelerinin koleksiyonunu alır. |
| [getEndCharIndex](#getEndCharIndex--) | Göster metin operatöründeki (Tj, TJ) segmentte mevcut segmentin bitiş karakter indeksini alır. |
| [getHyperlink](#getHyperlink--) | Segmentin hiperlinkini alır veya ayarlar (pdf oluşturucu için). |
| [getPosition](#getPosition--) | Metin konumunu, {@code TextSegment} nesnesiyle temsil edilen metin için alır. |
| [getRectangle](#getRectangle--) | TextSegment'in dikdörtgenini alır. |
| [getStartCharIndex](#getStartCharIndex--) | Göster metin operatöründeki (Tj, TJ) segmentte mevcut segmentin başlangıç karakter indeksini alır. |
| [getText](#getText--) | {@code TextSegment} nesnesinin temsil ettiği {@code string} metin nesnesini alır. |
| [getTextEditOptions](#getTextEditOptions--) | Metin düzenleme seçeneklerini alır. Seçenekler, istenen sembolün yazı tipiyle yazılamadığı durumlarda özel davranışı tanımlar. |
| [getTextState](#getTextState--) | <p> {@code TextSegment} nesnesinin temsil ettiği metnin metin durumunu alır veya ayarlar. </p> <hr> <p> Metnin aşağıdaki özelliklerini değiştirmek için bir yol sağlar: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Metin konumunu, {@code TextSegment} nesnesiyle temsil edilen metin için ayarlar. Position yapısının YIndent özelliği, metin segmentinin temel çizgi koordinatını temsil eder. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Segmentin hiperlinkini alır veya ayarlar (pdf oluşturucu için). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Metin konumunu, {@code TextSegment} nesnesiyle temsil edilen metin için ayarlar. |
| [setText](#setText-java.lang.String-) | {@code TextSegment} nesnesinin temsil ettiği {@code string} metin nesnesini ayarlar. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Metin düzenleme seçeneklerini ayarlar. Seçenekler, istenen sembolün yazı tipiyle yazılamadığı durumlarda özel davranışı tanımlar. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> {@code TextSegment} nesnesinin temsil ettiği metnin metin durumunu ayarlar. </p> <hr> <p> Metnin aşağıdaki özelliklerini değiştirmek için bir yol sağlar: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | {@code TextSegment} nesnesinin temsil ettiği {@code string} metin nesnesini, güncelleme bastırma isteğiyle ayarlar. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> TextSegment nesnesi oluşturur. </p> <hr> <pre> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> TextSegment nesnesi oluşturur. </p> <hr> <pre> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Metin konumunu, {@code TextSegment} nesnesiyle temsil edilen metin için alır. Position yapısının YIndent özelliği, metin segmentinin temel çizgi koordinatını temsil eder.

**Returns:**
Konum değeri

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

Metin segmentindeki karakterler hakkında bilgi temsil eden CharInfo nesnelerinin koleksiyonunu alır.

**Returns:**
CharInfoCollection nesnesi

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

Göster metin operatöründeki (Tj, TJ) segmentte mevcut segmentin bitiş karakter indeksini alır.

**Returns:**
int değer

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

Segmentin hiperlinkini alır veya ayarlar (pdf oluşturucu için).

**Returns:**
Hyperlink nesnesi

### getPosition {#getPosition--}
```
public Position getPosition()
```

Metin konumunu, {@code TextSegment} nesnesiyle temsil edilen metin için alır.

**Returns:**
Konum değeri

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

TextSegment'in dikdörtgenini alır.

**Returns:**
Rectangle nesnesi

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

Göster metin operatöründeki (Tj, TJ) segmentte mevcut segmentin başlangıç karakter indeksini alır.

**Returns:**
int değer

### getText {#getText--}
```
public String getText()
```

{@code TextSegment} nesnesinin temsil ettiği {@code string} metin nesnesini alır.

**Returns:**
String değeri

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Metin düzenleme seçeneklerini alır. Seçenekler, istenen sembolün yazı tipiyle yazılamadığı durumlarda özel davranışı tanımlar.

**Returns:**
TextEditOptions değeri

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> {@code TextSegment} nesnesinin temsil ettiği metnin metin durumunu alır veya ayarlar. </p> <hr> <p> Metnin aşağıdaki özelliklerini değiştirmek için bir yol sağlar: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
TextState değeri

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Metin konumunu, {@code TextSegment} nesnesiyle temsil edilen metin için ayarlar. Position yapısının YIndent özelliği, metin segmentinin temel çizgi koordinatını temsil eder.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Segmentin hiperlinkini alır veya ayarlar (pdf oluşturucu için).

### setPosition {#setPosition-com.aspose.pdf.Position-}
Metin konumunu, {@code TextSegment} nesnesiyle temsil edilen metin için ayarlar.

### setText {#setText-java.lang.String-}
{@code TextSegment} nesnesinin temsil ettiği {@code string} metin nesnesini ayarlar.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Metin düzenleme seçeneklerini ayarlar. Seçenekler, istenen sembolün yazı tipiyle yazılamadığı durumlarda özel davranışı tanımlar.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> {@code TextSegment} nesnesinin temsil ettiği metnin metin durumunu ayarlar. </p> <hr> <p> Metnin aşağıdaki özelliklerini değiştirmek için bir yol sağlar: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
{@code TextSegment} nesnesinin temsil ettiği {@code string} metin nesnesini, güncelleme bastırma isteğiyle ayarlar.
