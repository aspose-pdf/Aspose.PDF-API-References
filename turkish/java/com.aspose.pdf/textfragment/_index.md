---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Pdf metninin bir parçacığını temsil eder. </p> <hr> <pre> Örnek, ilk PDF belge sayfasındaki metni bulmayı ve metni ve yazı tipini değiştirmeyi gösterir. // Open document."
type: docs
weight: 5110
url: /tr/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> PDF metninin bir parçasını temsil eder. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document Document doc = new Document(\"input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"output.pdf\"); </pre> <hr> <pre> In a few words, {@code TextFragment} object contains list of {@code TextSegment} objects. In details: Text of pdf document in {@code com.aspose.pdf} is represented by two basic objects: {@code TextFragment} and {@code TextSegment} The differences between them is mostly context-dependent. Let's consider following scenario. User searches text \"hello world\" to operate with it, change it's properties, look etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> Fiziksel pdf metni temsili çok karmaşıktır. \"hello world\" metni birkaç fiziksel bağımsız metin segmentinden oluşabilir. Aspose.Pdf metin modeli temelde {@code TextFragment} nesnesinin, kullanıcının sorgusunu temsil eden fiziksel {@code TextSegment} nesneleri kümesi üzerinde tek bir mantıksal işlem kümesi sağladığını belirler. Metin arama senaryosunda, {@code TextFragment} mantıksal \"hello world\" metin temsili iken, {@code TextSegment} nesne koleksiyonu \"hello world\" metin nesnesini oluşturan tüm fiziksel segmentleri temsil eder. Böylece {@code TextFragment}, mantıksal metin temsiline yakındır. {@code TextSegment} ise fiziksel metin temsiline yakındır. Açıkça her {@code TextSegment} nesnesinin kendi yazı tipi, renk ve konumlandırma özellikleri olabilir. {@code TextFragment}, metni özellikleriyle birlikte değiştirmek için basit bir yol sağlar: yazı tipini ayarla, yazı tipi boyutunu ayarla, yazı tipi rengini ayarla vb. Bu arada {@code TextSegment} nesneleri erişilebilir ve kullanıcılar {@code TextSegment} nesneleriyle bağımsız olarak işlem yapabilir. <p> TextFragment özelliklerini değiştirmek, TextFragment bir toplama nesnesi olduğundan ve iç {@code Segments} koleksiyonunu yeniden düzenleyebileceğinden veya tek bir segmente birleştirebileceğinden iç {@code Segments} koleksiyonunu değiştirebilir. Gereksiniminiz {@code Segments} koleksiyonunu değiştirmemekse, lütfen iç segmentleri ayrı ayrı değiştirin. </p>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextFragment](#TextFragment--) | Yeni {@code TextFragment} nesnesinin bir örneğini başlatır. |
| [TextFragment](#TextFragment-java.lang.String-) | Yeni {@code TextFragment} nesnesinin bir örneğini başlatır. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Yeni {@code TextFragment} nesnesinin bir örneğini başlatır. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | Yeni {@code TextFragment} nesnesinin bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Parçayı tüm segmentlerle kopyalar. |
| [deepClone](#deepClone--) | Parçayı kopyalar. |
| [getBaselinePosition](#getBaselinePosition--) | Metin konumunu, {@code TextFragment} nesnesiyle temsil edilen metin için alır. Position yapısının YIndent özelliği, metin parçasının temel çizgi koordinatını temsil eder. |
| [getEndNote](#getEndNote--) | Paragraf son notunu alır. (yalnızca pdf oluşturma için) |
| [getFootNote](#getFootNote--) | Paragraf dip notunu alır. (yalnızca pdf oluşturma için) |
| [getForm](#getForm--) | TextFragment'i içeren form nesnesini alır. TextFragment nesnesi bir forma ait değilse değer null olabilir. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Metin parçasının yatay hizalamasını alır. |
| [getPage](#getPage--) | TextFragment'i içeren sayfayı alır. TextFragment nesnesi herhangi bir sayfaya ait değilse değer null olabilir. |
| [getPosition](#getPosition--) | <p> Metin konumunu, {@code TextFragment} nesnesiyle temsil edilen metin için alır. </p> |
| [getRectangle](#getRectangle--) | TextFragment'in dikdörtgenini alır |
| [getReplaceOptions](#getReplaceOptions--) | Metin değiştirme seçeneklerini alır. Seçenekler, parça metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar. |
| [getSegments](#getSegments--) | <p> Mevcut {@code TextFragment} için metin segmentlerini alır. </p> |
| [getText](#getText--) | <p> {@code TextFragment} nesnesinin temsil ettiği {@code string} metin nesnesini alır. </p> |
| [getTextEditOptions](#getTextEditOptions--) | Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembol fontla yazılamadığında özel davranışı tanımlar. |
| [getTextState](#getTextState--) | <p> {@code TextFragment} nesnesinin temsil ettiği metin için metin durumunu alır veya ayarlar. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | Metin parçasının dikey hizalamasını alır. |
| [getWrapLinesCount](#getWrapLinesCount--) | Bu paragraf için satır kırma sayısını alır (yalnızca pdf oluşturma için) |
| [isolateTextSegments](#isolateTextSegments-int-int-) | Belirtilen {@code TextFragment} metninin kısmını temsil eden {@code TextSegment}(leri) alır. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Metin konumunu, {@code TextFragment} nesnesiyle temsil edilen metin için ayarlar. Position yapısının YIndent özelliği, metin parçasının temel çizgi koordinatını temsil eder. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | Paragraf son notunu ayarlar. (yalnızca pdf oluşturma için) |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | Paragraf dip notunu ayarlar. (yalnızca pdf oluşturma için) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Metin parçasının yatay hizalamasını ayarlar. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Parçanın hiperlinkini ayarlar |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> Metin konumunu, {@code TextFragment} nesnesiyle temsil edilen metin için ayarlar. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | TextFragment'in dikdörtgenini alır |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | setSegments yöntemini temsil eder |
| [setText](#setText-java.lang.String-) | <p> {@code string} metin nesnesini, {@code TextFragment} nesnesinin temsil ettiği şekilde ayarlar. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembol fontla yazılamadığında özel davranışı tanımlar. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Metin parçacığının dikey hizalamasını ayarlar. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | Bu paragraf için satır sarma sayısını ayarlar (yalnızca pdf oluşturma için) |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

Yeni {@code TextFragment} nesnesinin bir örneğini başlatır.

### TextFragment {#TextFragment-java.lang.String-}
Yeni {@code TextFragment} nesnesinin bir örneğini başlatır.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
Yeni {@code TextFragment} nesnesinin bir örneğini başlatır.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
Yeni {@code TextFragment} nesnesinin bir örneğini başlatır.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Parçayı tüm segmentlerle kopyalar.

**Returns:**
Klonlanmış nesne

### deepClone {#deepClone--}
```
public Object deepClone()
```

Parçayı kopyalar.

**Returns:**
Klonlanmış nesne

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Metin konumunu, {@code TextFragment} nesnesiyle temsil edilen metin için alır. Position yapısının YIndent özelliği, metin parçasının temel çizgi koordinatını temsil eder.

**Returns:**
Konum değeri

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

Paragraf son notunu alır. (yalnızca pdf oluşturma için)

**Returns:**
Not değeri

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

Paragraf dip notunu alır. (yalnızca pdf oluşturma için)

**Returns:**
Not değeri

### getForm {#getForm--}
```
public XForm getForm()
```

TextFragment'i içeren form nesnesini alır. TextFragment nesnesi bir forma ait değilse değer null olabilir.

**Returns:**
XForm değeri

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Metin parçasının yatay hizalamasını alır.

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

TextFragment'i içeren sayfayı alır. TextFragment nesnesi herhangi bir sayfaya ait değilse değer null olabilir.

**Returns:**
Page nesnesi

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> Metin konumunu, {@code TextFragment} nesnesiyle temsil edilen metin için alır. </p>

**Returns:**
Pozisyon değeri <hr> <pre> Bu örnek, {@code TextFragment} nesnesi tarafından temsil edilen bir metnin konumunu nasıl görüntüleyeceğinizi gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Tüm "hello world" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metin ve konum bilgilerini görüntüle TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("parça metni: " + firstOccurrence.getText())); System.out.println("parça X girintisi: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("parça Y girintisi: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

TextFragment'in dikdörtgenini alır

**Returns:**
Rectangle nesnesi

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

Metin değiştirme seçeneklerini alır. Seçenekler, parça metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar.

**Returns:**
TextReplaceOptions örneği

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> Mevcut {@code TextFragment} için metin segmentlerini alır. </p>

**Returns:**
TextSegmentCollection değeri <hr> <pre> Bu örnek, {@code TextFragment} içinde bulunan tüm {@code TextSegment} nesnelerinde nasıl gezileceğini gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Tüm "hello world" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get(1).accept(absorber); // Tüm metin segmentlerinde dolaş ve metin ile konum bilgilerini çıktıla for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment metni: "+ segment.getText())); System.out.println("segment X girintisi: "+ segment.getPosition().getXIndent())); System.out.println("segment Y girintisi: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> Kısaca, {@code TextSegment} nesneleri {@code TextFragment} nesnesinin alt nesneleridir. İleri düzey kullanıcılar segmentlere doğrudan erişerek daha karmaşık metin düzenleme senaryoları gerçekleştirebilir. Ayrıntılar için lütfen {@code TextFragment} nesnesi açıklamasına bakın. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> {@code TextFragment} nesnesinin temsil ettiği {@code string} metin nesnesini alır. </p>

**Returns:**
String değeri <hr> <pre> Bu örnek, bir metni aramayı ve {@code TextFragment} nesnesiyle temsil edilen ilk oluşumu değiştirmeyi gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Tüm "hello world" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembol fontla yazılamadığında özel davranışı tanımlar.

**Returns:**
TextEditOptions örneği

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> {@code TextFragment} nesnesinin temsil ettiği metin için metin durumunu alır veya ayarlar. </p>

**Returns:**
TextFragmentState nesnesi <hr> <pre> Bu örnek, {@code TextState} nesnesiyle metnin renk ve yazı tipi boyutunu nasıl değiştireceğinizi gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Tüm "hello world" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun ön plan rengini değiştir absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // İlk metin oluşumunun yazı tipi boyutunu değiştir absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metnin aşağıdaki özelliklerini değiştirmek için bir yol sağlar: Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Metin parçasının dikey hizalamasını alır.

**Returns:**
int değeri @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

Bu paragraf için satır kırma sayısını alır (yalnızca pdf oluşturma için)

**Returns:**
int değer

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

Belirtilen {@code TextFragment} metninin kısmını temsil eden {@code TextSegment}(leri) alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex |  | Metinde yeni {@code TextSegment}(s) başlayacağı konum. |
| uzunluk |  | Metnin {@code TextSegment}(s) içine izole edileceği uzunluk. |

**Returns:**
{@code TextSegmentCollection} belirli bir konumda başlayan ve belirli bir uzunluğa sahip metin alt dizisini temsil eden metin segmentlerini içerir.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Metin konumunu, {@code TextFragment} nesnesiyle temsil edilen metin için ayarlar. Position yapısının YIndent özelliği, metin parçasının temel çizgi koordinatını temsil eder.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
Paragraf son notunu ayarlar. (yalnızca pdf oluşturma için)

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
Paragraf dip notunu ayarlar. (yalnızca pdf oluşturma için)

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Metin parçasının yatay hizalamasını ayarlar.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Parçanın hiperlinkini ayarlar

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> Metin konumunu, {@code TextFragment} nesnesiyle temsil edilen metin için ayarlar. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
TextFragment'in dikdörtgenini alır

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
setSegments yöntemini temsil eder

### setText {#setText-java.lang.String-}
<p> {@code string} metin nesnesini, {@code TextFragment} nesnesinin temsil ettiği şekilde ayarlar. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembol fontla yazılamadığında özel davranışı tanımlar.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Metin parçacığının dikey hizalamasını ayarlar.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

Bu paragraf için satır sarma sayısını ayarlar (yalnızca pdf oluşturma için)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
