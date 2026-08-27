---
title: "Yazı Tipi"
linktitle: "Yazı Tipi"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Yazı tipi nesnesini temsil eder. </p> <hr> <pre> Örnek, ilk sayfada metin aramayı ve ilk arama sonucunun yazı tipini değiştirmeyi gösterir. // Open document Document doc.</pre>"
type: docs
weight: 1650
url: /tr/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Klonlanabilir

```
public final class Font extends Object implements Cloneable
```

<p> Yazı tipi nesnesini temsil eder. </p> <hr> <pre> Örnek, ilk sayfada metin aramayı ve ilk arama sonucunun yazı tipini değiştirmeyi gösterir. // Open document Document doc = new Document("input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | Yazı tipinin belirtilen karakterleri içerip içermediğini belirler |
| [getActualFontName](#getActualFontName--) | <p> {@code Font} nesnesi başlatıldıysa gerçek yazı tipi adını alır. Yazı tipi değiştirilmiş ya da PDF için dahili bir adı olsa bile. Başlatılmamışsa boş dize döndürür. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | Maksimum yükseliş noktasını ölçer. |
| [getBaseFont](#getBaseFont--) | PDF yazı tipi nesnesinin BaseFont değerini alır. Ayrıca yazı tipinin PostScript adı olarak da bilinir. |
| [getDecodedFontName](#getDecodedFontName--) | Bazen PDF yazı tipleri (genellikle Çince/Japonca/Korece yazı tipleri) belirli bir yazı tipi adına sahip olabilir. Bu ad, PDF yazı tipi özelliği "BaseFont" değeridir ve bazen bu özellik onaltılık biçimde temsil edilebilir. Bu adı doğrudan okursanız okunamaz bir biçimde görünebilir. Okunabilir bir biçim elde etmek için, bu yazı tipine özgü kurallara göre yazı tipi adını çözmek gerekir. Bu özellik, çözümlenmiş yazı tipi adını döndürür; bu nedenle okunamaz bir {@code FontName} ile karşılaştığınız durumlarda kullanın. Eğer {@code FontName} özelliği zaten okunabilir bir biçimdeyse, bu özellik {@code FontName} ile aynı olacaktır; böylece okunabilir bir yazı tipi adı almanız gerektiğinde bu özelliği her türlü durumda kullanabilirsiniz. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | Maksimum alçalış noktasını ölçer. |
| [getFontName](#getFontName--) | <p> {@code Font} nesnesinin yazı tipi adını alır. </p> |
| [getFontOptions](#getFontOptions--) | Yazı tipi davranışını ayarlamak için faydalı özellikler |
| [getIFont](#getIFont--) | <p> Sistem yazı tipi nesnesi. </p> <hr> <p> Yalnızca dahili kullanım için </p> |
| [getIPdfFont](#getIPdfFont--) | <p> PDF yazı tipi nesnesi. </p> <hr> <p> Yalnızca dahili kullanım için </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | Bu yöntemin amacı - yazı tipini gömmeye yönelik bir deneme başarısız olursa hata açıklamasını döndürmektir. Hata durumu yoksa boş dize döndürür. |
| [getType](#getType--) | Yazı tipinin tür adı |
| [isAccessible](#isAccessible--) | <p> Yazı tipinin sistemde mevcut (kurulu) olup olmadığını gösteren değeri alır. </p> |
| [isEmbedded](#isEmbedded--) | <p> Yazı tipinin gömülü olup olmadığını gösteren bir değer alır. IFont tabanlı yazı tipleri otomatik olarak alt küme haline getirilir ve gömülür </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> Yazı tipinin bir alt küme olup olmadığını gösteren bir değer alır. IFont tabanlı yazı tipleri otomatik olarak alt küme haline getirilir ve gömülür </p> <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | Dizgeyi ölçer. |
| [save](#save-java.io.OutputStream-) | Yazı tipini akışa kaydeder. Yazı tipinin yalnızca orijinal belgenin dönüştürülmüş bir kopyasında kullanılmak üzere ara TTF formatında kaydedildiğini unutmayın. Yazı tipi dosyası, orijinal belge bağlamı dışına kullanılmak üzere tasarlanmamıştır. |
| [setEmbedded](#setEmbedded-boolean-) | Yazı tipinin gömülü olup olmadığını gösteren bir değer ayarlar. IFont tabanlı yazı tipleri otomatik olarak alt küme haline getirilir ve gömülür |
| [setSubset](#setSubset-boolean-) | Yazı tipinin bir alt küme olup olmadığını gösteren bir değer ayarlar. IFont tabanlı yazı tipleri otomatik olarak alt küme haline getirilir ve gömülür |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
Yazı tipinin belirtilen karakterleri içerip içermediğini belirler

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> {@code Font} nesnesi başlatıldıysa gerçek yazı tipi adını alır. Yazı tipi değiştirilmiş ya da PDF için dahili bir adı olsa bile. Başlatılmamışsa boş dize döndürür. </p>

**Returns:**
Dize değeri <hr> <pre> Bu örnek, ilk sayfada metin aramayı ve birinci metin oluşumunun gerçek yazı tipi adını görüntülemeyi gösterir. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
Maksimum yükseliş noktasını ölçer.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

PDF yazı tipi nesnesinin BaseFont değerini alır. Ayrıca yazı tipinin PostScript adı olarak da bilinir.

**Returns:**
String değeri

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

Bazen PDF yazı tipleri (genellikle Çince/Japonca/Korece yazı tipleri) belirli bir yazı tipi adına sahip olabilir. Bu ad, PDF yazı tipi özelliği "BaseFont" değeridir ve bazen bu özellik onaltılık biçimde temsil edilebilir. Bu adı doğrudan okursanız okunamaz bir biçimde görünebilir. Okunabilir bir biçim elde etmek için, bu yazı tipine özgü kurallara göre yazı tipi adını çözmek gerekir. Bu özellik, çözümlenmiş yazı tipi adını döndürür; bu nedenle okunamaz bir {@code FontName} ile karşılaştığınız durumlarda kullanın. Eğer {@code FontName} özelliği zaten okunabilir bir biçimdeyse, bu özellik {@code FontName} ile aynı olacaktır; böylece okunabilir bir yazı tipi adı almanız gerektiğinde bu özelliği her türlü durumda kullanabilirsiniz.

**Returns:**
String değeri

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
Maksimum alçalış noktasını ölçer.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> {@code Font} nesnesinin yazı tipi adını alır. </p>

**Returns:**
Dize değeri <hr> <pre> Bu örnek, ilk sayfada metin aramayı ve birinci metin oluşumunun yazı tipi adını görüntülemeyi gösterir. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

Yazı tipi davranışını ayarlamak için faydalı özellikler

**Returns:**
IFontOptions nesnesi

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> Sistem yazı tipi nesnesi. </p> <hr> <p> Yalnızca dahili kullanım için </p>

**Returns:**
IFont nesnesi

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> PDF yazı tipi nesnesi. </p> <hr> <p> Yalnızca dahili kullanım için </p>

**Returns:**
IPdfFont nesnesi

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

Bu yöntemin amacı - yazı tipini gömmeye yönelik bir deneme başarısız olursa hata açıklamasını döndürmektir. Hata durumu yoksa boş dize döndürür.

**Returns:**
Hata açıklaması

### getType {#getType--}
```
public String getType()
```

Yazı tipinin tür adı

**Returns:**
Dize nesnesi

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> Yazı tipinin sistemde mevcut (kurulu) olup olmadığını gösteren değeri alır. </p>

**Returns:**
boolean değer <hr> <pre> Bu örnek, ilk sayfada metin aramayı ve yazı tipinin sistemde yüklü olup olmadığını gösteren değeri almayı gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Tüm "hello world" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipinin IsSubset değerini görüntüle if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println("the font is installed in the system"); </pre> <hr> <p> Sistemde bulunamayan yazı tipleriyle bazı işlemler kullanılamaz. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> Yazı tipinin gömülü olup olmadığını gösteren bir değer alır. IFont tabanlı yazı tipleri otomatik olarak alt küme oluşturulur ve gömülür. </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Yazı tipini oluştur ve gömülü olarak işaretle com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // Belgeyi aç com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf"); // Tüm "hello world" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre>

**Returns:**
boolean değer @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> Yazı tipinin bir alt küme olup olmadığını gösteren bir değer alır. IFont tabanlı yazı tipleri otomatik olarak alt küme oluşturulur ve gömülür. </p> <hr> <pre> Bu örnek, ilk sayfada metin aramayı ve yazı tipinin bir alt küme olup olmadığını gösteren değeri almayı gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Tüm "hello world" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipinin IsSubset değerini görüntüle if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre>

**Returns:**
boolean değer @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
Dizgeyi ölçer.

### save {#save-java.io.OutputStream-}
Yazı tipini akışa kaydeder. Yazı tipinin yalnızca orijinal belgenin dönüştürülmüş bir kopyasında kullanılmak üzere ara TTF formatında kaydedildiğini unutmayın. Yazı tipi dosyası, orijinal belge bağlamı dışına kullanılmak üzere tasarlanmamıştır.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

Yazı tipinin gömülü olup olmadığını gösteren bir değer ayarlar. IFont tabanlı yazı tipleri otomatik olarak alt küme haline getirilir ve gömülür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

Yazı tipinin bir alt küme olup olmadığını gösteren bir değer ayarlar. IFont tabanlı yazı tipleri otomatik olarak alt küme haline getirilir ve gömülür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
