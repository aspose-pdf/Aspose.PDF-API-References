---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Metin parçacıklarının bir emici nesnesini temsil eder. Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p>."
type: docs
weight: 5120
url: /tr/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> Metin parçacıklarının bir emici nesnesini temsil eder. Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni ve yazı tipini değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> {@code TextFragmentAbsorber} nesnesi temel olarak metin arama senaryosunda kullanılır. Arama tamamlandığında, oluşumlar {@code TextFragment} nesneleriyle temsil edilir ve bu nesneler {@code TextFragmentAbsorber.TextFragments} koleksiyonunda bulunur. {@code TextFragment} nesnesi, arama oluşum metnine, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye izin verir. </p>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> {@code TextFragmentAbsorber} sınıfının, belgenin veya sayfanın tüm metin segmentlerini arayan yeni bir örneğini başlatır. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni bulmayı ve metni değiştirmeyi gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | Absorbe edilen tüm metin parçacıklarına yazı tipi boyutu uygular. Sayfadaki (sayfalardaki) tüm parçacıklar absorbe edilmişse, parçacıklar üzerinde döngü yapmaktan daha hızlı çalışır. Aksi takdirde döngüyle benzer şekilde çalışır. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | Absorbe edilen tüm metin parçacıklarına yazı tipi uygular. Sayfadaki (sayfalardaki) tüm parçacıklar absorbe edilmişse, parçacıklar üzerinde döngü yapmaktan daha hızlı çalışır. Aksi takdirde döngüyle benzer şekilde çalışır. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | Absorbe edilen tüm metin parçacıklarına yazı tipi ve boyutu uygular. Sayfadaki (sayfalardaki) tüm parçacıklar absorbe edilmişse, parçacıklar üzerinde döngü yapmaktan daha hızlı çalışır. Aksi takdirde döngüyle benzer şekilde çalışır. |
| [getErrors](#getErrors--) | {@code TextExtractionError} nesnelerinin listesi. Metin çıkarımı sırasında bulunan hatalar hakkında bilgi içerir. Hataların aranması yalnızca TextSearchOptions.LogTextExtractionErrors = true olduğunda gerçekleştirilecektir; ve bu performansı düşürebilir. |
| [getExtractionOptions](#getExtractionOptions--) | Metin çıkarma seçeneklerini alır. |
| [getPhrase](#getPhrase--) | <p> {@code TextFragmentAbsorber} nesnesinin PDF belge veya sayfa üzerinde aradığı ifadeyi alır. </p> |
| [getRegexResults](#getRegexResults--) | Arama oluşumlarının sözlüğünü alır; anahtar olarak System.Text.RegularExpressions.Regex sınıfı ve değer olarak {@link TextFragment} kullanılır. Örnek, ilk PDF belge sayfasında düzenli ifadeler dizisiyle metnin nasıl bulunacağını gösterir. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | PDF belge veya sayfasında {@code TextAbsorber} tarafından çıkarılan metni alır. |
| [getTextEditOptions](#getTextEditOptions--) | Metin düzenleme seçeneklerini alır. Seçenekler, istenen sembolün yazı tipiyle yazılamadığı durumlarda özel davranışı tanımlar. |
| [getTextFragments](#getTextFragments--) | <p> {@code TextFragment} nesneleriyle sunulan arama oluşumlarının koleksiyonunu alır. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Metin değiştirme seçeneklerini alır. Seçenekler, parça metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Arama seçeneklerini alır. Seçenekler, düzenli ifadeler kullanarak aramayı etkinleştirir. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | Değer, metin çıkarma sırasında hata bulunup bulunmadığını gösterir. Hata arama yalnızca TextSearchOptions.LogTextExtractionErrors = true olduğunda yapılır; ve bu performansı düşürebilir. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | Belgeden tüm metni kaldırır. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | Belirtilen sayfadan tüm metni kaldırır. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Belirtilen sayfada, belirtilen dikdörtgen içindeki metni kaldırır. |
| [reset](#reset--) | Bu {@code TextFragmentAbsorber} nesnesinin TextFragments koleksiyonunu temizler. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Metin çıkarma seçeneklerini ayarlar. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> {@code TextFragmentAbsorber}ın PDF belge veya sayfasında aradığı ifadeyi ayarlar. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Metin düzenleme seçeneklerini ayarlar. Seçenekler, istenen sembolün yazı tipiyle yazılamadığı durumlarda özel davranışı tanımlar. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> {@code TextFragment} nesneleriyle sunulan arama oluşumlarının koleksiyonunu ayarlar. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Metin değiştirme seçeneklerini ayarlar. Seçenekler, parçacık metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Arama seçeneklerini ayarlar. Seçenekler, düzenli ifadeler kullanarak aramayı etkinleştirir. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Belirtilen belgede arama yapar. </p> <hr> <pre> Örnek, PDF belgede metnin nasıl bulunacağını ve tüm arama oluşumlarının metninin nasıl değiştirileceğini gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Belirtilen sayfada arama yapar. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metnin nasıl bulunacağını ve metnin nasıl değiştirileceğini gösterir. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | Belirtilen form nesnesinde arama yapar. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> Belge veya sayfanın tüm metin segmentlerini arayan {@code TextFragmentAbsorber} sınıfının yeni bir örneğini başlatır. </p> <hr> <pre> // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Absorber'ı tüm \"hello world\" metin oluşumlarını arayacak şekilde ayarla absorber.setPhrase ( "hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Metin araması gerçekleştirir ve arama sonuçlarına {@code TextFragmentAbsorber.TextFragments} koleksiyonu aracılığıyla erişim sağlar. </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

Absorbe edilen tüm metin parçacıklarına yazı tipi boyutu uygular. Sayfadaki (sayfalardaki) tüm parçacıklar absorbe edilmişse, parçacıklar üzerinde döngü yapmaktan daha hızlı çalışır. Aksi takdirde döngüyle benzer şekilde çalışır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontSize |  | Metnin yazı tipi boyutu. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
Absorbe edilen tüm metin parçacıklarına yazı tipi uygular. Sayfadaki (sayfalardaki) tüm parçacıklar absorbe edilmişse, parçacıklar üzerinde döngü yapmaktan daha hızlı çalışır. Aksi takdirde döngüyle benzer şekilde çalışır.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
Absorbe edilen tüm metin parçacıklarına yazı tipi ve boyutu uygular. Sayfadaki (sayfalardaki) tüm parçacıklar absorbe edilmişse, parçacıklar üzerinde döngü yapmaktan daha hızlı çalışır. Aksi takdirde döngüyle benzer şekilde çalışır.

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

Metin çıkarma seçeneklerini alır.

**Returns:**
TextExtractionOptions nesnesi

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> {@code TextFragmentAbsorber} nesnesinin PDF belge veya sayfa üzerinde aradığı ifadeyi alır. </p>

**Returns:**
String değeri <hr> <pre> Örnek, metin aramasını birkaç kez nasıl gerçekleştireceğinizi ve metin değişikliklerini nasıl yapacağınızı gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Tüm \"hello\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // başka bir kelimeyi ara ve değiştir absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

Arama oluşumlarının sözlüğünü alır; anahtar olarak System.Text.RegularExpressions.Regex sınıfı ve değer olarak {@link TextFragment} kullanılır. Örnek, ilk PDF belge sayfasında düzenli ifadeler dizisiyle metnin nasıl bulunacağını gösterir. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults();

**Returns:**
Dictionary örneği

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

PDF belge veya sayfasında {@code TextAbsorber} tarafından çıkarılan metni alır.

**Returns:**
String değeri Örnek, PDF belgesinin tüm sayfalarından metin nasıl çıkarılacağını gösterir. // belgeyi aç Document doc = new Document(inFile); // metni çıkarmak için TextAbsorber nesnesi oluştur TextAbsorber absorber = new TextAbsorber(); // absorberi belgenin tüm sayfaları için kabul et doc.getPages().accept(absorber); // çıkarılan metni al String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Metin düzenleme seçeneklerini alır. Seçenekler, istenen sembolün yazı tipiyle yazılamadığı durumlarda özel davranışı tanımlar.

**Returns:**
TextEditOptions nesnesi

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> {@code TextFragment} nesneleriyle sunulan arama oluşumlarının koleksiyonunu alır. </p>

**Returns:**
TextFragmentCollection nesnesi <hr> <pre> Örnek, PDF belgesinin ilk sayfasındaki metni bulmayı ve tüm arama oluşumlarını yeni metinle değiştirmeyi gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metnini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorberi kabul et doc.getPages().get(1).accept(absorber); // Tüm arama oluşumlarının metnini değiştir for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Metin değiştirme seçeneklerini alır. Seçenekler, parça metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar.

**Returns:**
TextReplaceOptions değeri

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Arama seçeneklerini alır. Seçenekler, düzenli ifadeler kullanarak aramayı etkinleştirir. </p>

**Returns:**
TextSearchOptions nesnesi <hr> <pre> Örnek, düzenli ifade kullanarak metin aramasının nasıl yapılacağını gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // düzenli ifade kullanarak 'h' ile başlayıp 'o' ile biten tüm kelimeleri aramak için absorberi ayarla. absorber.setPhrase ( "h\\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // \"hello\" kelimesini bulmalı ve \"Hi\" ile değiştirmeliyiz doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

Değer, metin çıkarma sırasında hata bulunup bulunmadığını gösterir. Hata arama yalnızca TextSearchOptions.LogTextExtractionErrors = true olduğunda yapılır; ve bu performansı düşürebilir.

**Returns:**
boolean değer

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
Belgeden tüm metni kaldırır.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
Belirtilen sayfadan tüm metni kaldırır.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Belirtilen sayfada, belirtilen dikdörtgen içindeki metni kaldırır.

### reset {#reset--}
```
public void reset()
```

Bu {@code TextFragmentAbsorber} nesnesinin TextFragments koleksiyonunu temizler.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
Metin çıkarma seçeneklerini ayarlar.

### setPhrase {#setPhrase-java.lang.String-}
<p> {@code TextFragmentAbsorber}ın PDF belge veya sayfasında aradığı ifadeyi ayarlar. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Metin düzenleme seçeneklerini ayarlar. Seçenekler, istenen sembolün yazı tipiyle yazılamadığı durumlarda özel davranışı tanımlar.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> {@code TextFragment} nesneleriyle sunulan arama oluşumlarının koleksiyonunu ayarlar. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Metin değiştirme seçeneklerini ayarlar. Seçenekler, parçacık metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Arama seçeneklerini ayarlar. Seçenekler, düzenli ifadeler kullanarak aramayı etkinleştirir. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Belirtilen belgede arama yapar. </p> <hr> <pre> Örnek, PDF belgesinde metni nasıl bulup tüm arama sonuçlarının metnini nasıl değiştireceğini gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metin yazı tipini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et absorber.visit(doc); // İlk metin oluşumunun metnini değiştir absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Belirtilen sayfada arama yapar. </p> <hr> <pre> Örnek, ilk PDF belge sayfasında metni nasıl bulup metni nasıl değiştireceğini gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Belge metin yazı tipini değiştirmek için kullanılacak yazı tipini bul Font font = FontRepository.findFont("Arial"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et absorber.visit(doc.getPages().get(1)); // Tüm arama sonuçlarının metnini değiştir for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
Belirtilen form nesnesinde arama yapar.
