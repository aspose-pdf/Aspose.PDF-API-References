---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Bir metnin absorber nesnesini temsil eder. Metin çıkarımı yapar ve sonucu {@code TextAbsorber.Text} nesnesi aracılığıyla erişilebilir kılar. </p> <hr> <pre> Örnek."
type: docs
weight: 4900
url: /tr/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> Bir metin emici nesneyi temsil eder. Metin çıkarımı gerçekleştirir ve sonucu {@code TextAbsorber.Text} nesnesi aracılığıyla erişilebilir kılar. </p> <hr> <pre> Örnek, ilk PDF belge sayfasından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> {@code TextAbsorber} nesnesi, bir Pdf belgesinden veya belgenin sayfasından metin çıkarmak için kullanılır. </p>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> {@code TextAbsorber}'ın yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, PDF belgesinin tüm sayfalarından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Metin çıkarımı yapar ve çıkarılan metne {@code TextAbsorber.Text} nesnesi aracılığıyla erişim sağlar. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> {@code TextAbsorber}'ın yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, PDF belgesinin tüm sayfalarından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Metin çıkarımı yapar ve çıkarılan metne {@code TextAbsorber.Text} nesnesi aracılığıyla erişim sağlar. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextAbsorber}'ın yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, PDF belgesinin tüm sayfalarından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Metin çıkarımı yapar ve çıkarılan metne {@code TextAbsorber.Text} nesnesi aracılığıyla erişim sağlar. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextAbsorber}'ın yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, PDF belgesinin tüm sayfalarından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Metin çıkarımı yapar ve çıkarılan metne {@code TextAbsorber.Text} nesnesi aracılığıyla erişim sağlar. </p> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getErrors](#getErrors--) | {@code TextExtractionError} nesnelerinin listesi. Metin çıkarımı sırasında bulunan hatalar hakkında bilgi içerir. Hataların aranması yalnızca TextSearchOptions.LogTextExtractionErrors = true olduğunda gerçekleştirilecektir; ve bu performansı düşürebilir. |
| [getExtractionOptions](#getExtractionOptions--) | <p> Metin çıkarma seçeneklerini alır. </p> <hr> <pre> Örnek, Saf metin biçimlendirme modunu ayarlamayı ve metin çıkarımını göstermektedir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Çıkarma sırasında {@code TextExtractionOptions} ile metin biçimlendirme modunu tanımlamaya izin verir. Varsayılan mod {@code TextExtractionOptions.TextFormattingMode.Pure}'dır. </p> |
| [getText](#getText--) | <p> {@code TextAbsorber} tarafından PDF belgesi veya sayfasında çıkarılan metni alır. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | Metin arama seçeneklerini alır. Çıkarılan metni sınırlayan bir dikdörtgen tanımlamaya izin verir. Varsayılan olarak dikdörtgen boştur. Bu, yalnızca sayfa sınırlarının metin çıkarma bölgesini tanımladığı anlamına gelir. |
| [hasErrors](#hasErrors--) | Değer, metin çıkarma sırasında hata bulunup bulunmadığını gösterir. Hata arama yalnızca TextSearchOptions.LogTextExtractionErrors = true olduğunda yapılır; ve bu performansı düşürebilir. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Metin çıkarma seçeneklerini ayarlar. </p> <hr> <pre> Örnek, Saf metin biçimlendirme modunu ayarlamayı ve metin çıkarımını göstermektedir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Çıkarma sırasında {@code TextExtractionOptions} ile metin biçimlendirme modunu tanımlamaya izin verir. Varsayılan mod {@code TextExtractionOptions.TextFormattingMode.Pure}'dır. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Metin arama seçeneklerini ayarlar. Çıkarılan metni sınırlayan bir dikdörtgen tanımlamaya izin verir. Varsayılan olarak dikdörtgen boştur. Bu, yalnızca sayfa sınırlarının metin çıkarma bölgesini tanımladığı anlamına gelir. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Belirtilen belgede metni çıkarır </p> <hr> <pre> Örnek, PDF belgesinde metnin nasıl çıkarılacağını gösterir. // belgeyi aç Document doc = new Document(inFile); // metni çıkarmak için TextAbsorber nesnesi oluştur TextAbsorber absorber = new TextAbsorber(); // absorbere belgenin tüm sayfalarını kabul ettir absorber.visit(doc); // çıkarılan metni al String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Belirtilen sayfada metni çıkarır </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metnin nasıl çıkarılacağını gösterir. // belgeyi aç Document doc = new Document(inFile); // metni çıkarmak için TextAbsorber nesnesi oluştur TextAbsorber absorber = new TextAbsorber(); // absorbere belgenin tüm sayfalarını kabul ettir absorber.visit(doc.getPages(1)); // çıkarılan metni al String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> Belirtilen XForm'da metni çıkarır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metnin nasıl çıkarılacağını gösterir. // belgeyi aç Document doc = new Document(inFile); // metni çıkarmak için TextAbsorber nesnesi oluştur TextAbsorber absorber = new TextAbsorber(); // absorbere belgenin tüm sayfalarını kabul ettir absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // çıkarılan metni al String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> {@code TextAbsorber}'ın yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, PDF belgesinin tüm sayfalarından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Metin çıkarımı yapar ve çıkarılan metne {@code TextAbsorber.Text} nesnesi aracılığıyla erişim sağlar. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> {@code TextAbsorber}'ın yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, PDF belgesinin tüm sayfalarından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Metin çıkarımı yapar ve çıkarılan metne {@code TextAbsorber.Text} nesnesi aracılığıyla erişim sağlar. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> {@code TextAbsorber}'ın yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, PDF belgesinin tüm sayfalarından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Metin çıkarımı yapar ve çıkarılan metne {@code TextAbsorber.Text} nesnesi aracılığıyla erişim sağlar. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> {@code TextAbsorber}'ın yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, PDF belgesinin tüm sayfalarından metin nasıl çıkarılacağını gösterir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Metin çıkarımı yapar ve çıkarılan metne {@code TextAbsorber.Text} nesnesi aracılığıyla erişim sağlar. </p>

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

{@code TextExtractionError} nesnelerinin listesi. Metin çıkarımı sırasında bulunan hatalar hakkında bilgi içerir. Hataların aranması yalnızca TextSearchOptions.LogTextExtractionErrors = true olduğunda gerçekleştirilecektir; ve bu performansı düşürebilir.

**Returns:**
TextExtractionError nesnelerinin listesi

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Metin çıkarma seçeneklerini alır. </p> <hr> <pre> Örnek, Saf metin biçimlendirme modunu ayarlamayı ve metin çıkarımını göstermektedir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Çıkarma sırasında {@code TextExtractionOptions} ile metin biçimlendirme modunu tanımlamaya izin verir. Varsayılan mod {@code TextExtractionOptions.TextFormattingMode.Pure}'dır. </p>

**Returns:**
TextExtractionOptions değeri

### getText {#getText--}
```
public String getText()
```

<p> {@code TextAbsorber} tarafından PDF belgesi veya sayfasında çıkarılan metni alır. </p>

**Returns:**
String değeri <hr> <pre> Örnek, PDF belgesinin tüm sayfalarından metnin nasıl çıkarılacağını gösterir. // belgeyi aç Document doc = new Document(inFile); // metni çıkarmak için TextAbsorber nesnesi oluştur TextAbsorber absorber = new TextAbsorber(); // absorbere belgenin tüm sayfalarını kabul ettir doc.getPages().accept(absorber); // çıkarılan metni al String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Metin arama seçeneklerini alır. Çıkarılan metni sınırlayan bir dikdörtgen tanımlamaya izin verir. Varsayılan olarak dikdörtgen boştur. Bu, yalnızca sayfa sınırlarının metin çıkarma bölgesini tanımladığı anlamına gelir.

**Returns:**
TextSearchOptions değeri

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

Değer, metin çıkarma sırasında hata bulunup bulunmadığını gösterir. Hata arama yalnızca TextSearchOptions.LogTextExtractionErrors = true olduğunda yapılır; ve bu performansı düşürebilir.

**Returns:**
boolean değer

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Metin çıkarma seçeneklerini ayarlar. </p> <hr> <pre> Örnek, Saf metin biçimlendirme modunu ayarlamayı ve metin çıkarımını göstermektedir. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Çıkarma sırasında {@code TextExtractionOptions} ile metin biçimlendirme modunu tanımlamaya izin verir. Varsayılan mod {@code TextExtractionOptions.TextFormattingMode.Pure}'dır. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Metin arama seçeneklerini ayarlar. Çıkarılan metni sınırlayan bir dikdörtgen tanımlamaya izin verir. Varsayılan olarak dikdörtgen boştur. Bu, yalnızca sayfa sınırlarının metin çıkarma bölgesini tanımladığı anlamına gelir.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Belirtilen belgede metni çıkarır </p> <hr> <pre> Örnek, PDF belgesinde metnin nasıl çıkarılacağını gösterir. // belgeyi aç Document doc = new Document(inFile); // metni çıkarmak için TextAbsorber nesnesi oluştur TextAbsorber absorber = new TextAbsorber(); // absorbere belgenin tüm sayfalarını kabul ettir absorber.visit(doc); // çıkarılan metni al String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Belirtilen sayfada metni çıkarır </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metnin nasıl çıkarılacağını gösterir. // belgeyi aç Document doc = new Document(inFile); // metni çıkarmak için TextAbsorber nesnesi oluştur TextAbsorber absorber = new TextAbsorber(); // absorbere belgenin tüm sayfalarını kabul ettir absorber.visit(doc.getPages(1)); // çıkarılan metni al String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> Belirtilen XForm'da metni çıkarır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metnin nasıl çıkarılacağını gösterir. // belgeyi aç Document doc = new Document(inFile); // metni çıkarmak için TextAbsorber nesnesi oluştur TextAbsorber absorber = new TextAbsorber(); // absorbere belgenin tüm sayfalarını kabul ettir absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // çıkarılan metni al String extractedText = absorber.getText(); </pre>
