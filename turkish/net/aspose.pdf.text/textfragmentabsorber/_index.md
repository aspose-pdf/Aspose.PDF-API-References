---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentAbsorber sınıfı. Metin parçalarının bir emici nesnesini temsil eder. Metin araması yapar ve arama sonuçlarına TextFragments koleksiyonu aracılığıyla erişim sağlar.
type: docs
weight: 10950
url: /tr/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber sınıfı

Metin parçalarının bir emici nesnesini temsil eder. Metin araması yapar ve arama sonuçlarına [`TextFragments`](./textfragments/) koleksiyonu aracılığıyla erişim sağlar.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Belgenin veya sayfanın tüm metin segmentlerini arayan `TextFragmentAbsorber`'ın yeni bir örneğini başlatır. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Belirtilen System.Text.RegularExpressions.Regex sınıf nesnesi için `TextFragmentAbsorber` sınıfının yeni bir örneğini başlatır. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Belirtilen metin ifadesi için `TextFragmentAbsorber` sınıfının yeni bir örneğini başlatır. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Belgenin veya sayfanın tüm metin segmentlerini arayan metin düzenleme seçenekleri ile `TextFragmentAbsorber`'ın yeni bir örneğini başlatır. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Belirtilen metin ifadesi ve metin düzenleme seçenekleri için `TextFragmentAbsorber` sınıfının yeni bir örneğini başlatır. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Belirtilen metin ifadesi ve metin arama seçenekleri için `TextFragmentAbsorber` sınıfının yeni bir örneğini başlatır. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Belirtilen metin ifadesi ve metin arama seçenekleri için `TextFragmentAbsorber` sınıfının yeni bir örneğini başlatır. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Belirtilen metin ifadesi ve metin düzenleme seçenekleri için `TextFragmentAbsorber` sınıfının yeni bir örneğini başlatır. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Belirtilen metin ifadesi ve metin arama seçenekleri için `TextFragmentAbsorber` sınıfının yeni bir örneğini başlatır. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Belirtilen metin ifadesi, metin arama seçenekleri ve metin düzenleme seçenekleri için `TextFragmentAbsorber` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) nesnelerinin listesidir. Metin çıkarımı sırasında bulunan hatalar hakkında bilgi içerir. Hataları aramak yalnızca TextSearchOptions.LogTextExtractionErrors = true; olduğunda yapılır; ve bu performansı düşürebilir. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Metin çıkarım seçeneklerini alır veya ayarlar. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Hataların metin çıkarımı sırasında bulunup bulunmadığını gösteren değerdir. Hataları aramak yalnızca TextSearchOptions.LogTextExtractionErrors = true; olduğunda yapılır; ve bu performansı düşürebilir. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | `TextFragmentAbsorber`'ın PDF belgesinde veya sayfasında aradığı ifadeyi alır veya ayarlar. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Anahtar olarak System.Text.RegularExpressions.Regex sınıfı ve değer olarak [`TextFragment`](../textfragment/) ile sunulan arama oluşumlarının sözlüğünü alır. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | [`TextAbsorber`](../textabsorber/) tarafından PDF belgesinde veya sayfasında çıkarılan metni alır. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Metin düzenleme seçeneklerini alır veya ayarlar. Seçenekler, istenen sembolün yazı tipi ile yazılamadığı durumlarda özel davranışı tanımlar. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | [`TextFragment`](../textfragment/) nesneleri ile sunulan arama oluşumlarının koleksiyonunu alır veya ayarlar. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Metin değiştirme seçeneklerini alır veya ayarlar. Seçenekler, parça metni daha kısa/uzun bir metinle değiştirildiğinde davranışı tanımlar. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Arama seçeneklerini alır veya ayarlar. Seçenekler, düzenli ifadeler kullanarak arama yapmayı sağlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Emilen tüm metin parçaları için yazı tipi boyutunu uygular. Tüm parçalar sayfa(lar)da emildiğinde, parçalar arasında döngü yapmaktan daha hızlı çalışır. Aksi takdirde, döngü ile benzer şekilde çalışır. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Emilen tüm metin parçaları için yazı tipini uygular. Tüm parçalar sayfa(lar)da emildiğinde, parçalar arasında döngü yapmaktan daha hızlı çalışır. Aksi takdirde, döngü ile benzer şekilde çalışır. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Emilen tüm metin parçaları için yazı tipi ve boyutunu uygular. Tüm parçalar sayfa(lar)da emildiğinde, parçalar arasında döngü yapmaktan daha hızlı çalışır. Aksi takdirde, döngü ile benzer şekilde çalışır. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Belgeden tüm metni kaldırır. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Belirtilen sayfadan tüm metni kaldırır. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Belirtilen sayfadan belirtilen dikdörtgenin içindeki metni kaldırır. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Bu `TextFragmentAbsorber` nesnesinin TextFragments koleksiyonunu temizler. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Belirtilen belgede arama yapar. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Belirtilen sayfada arama yapar. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Belirtilen form nesnesinde arama yapar. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Belirtilen XForm'da metin çıkarır. |

## Açıklamalar

`TextFragmentAbsorber` nesnesi esasen metin arama senaryosunda kullanılır. Arama tamamlandığında, oluşumlar [`TextFragment`](../textfragment/) nesneleri ile temsil edilir ve [`TextFragments`](./textfragments/) koleksiyonu içerir. [`TextFragment`](../textfragment/) nesnesi, arama oluşum metnine, metin özelliklerine erişim sağlar ve metni düzenleme ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirme imkanı sunar.

## Örnekler

Örnek, ilk PDF belgesi sayfasında metni nasıl bulacağınızı ve metni ve yazı tipini nasıl değiştireceğinizi gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ayrıca Bakınız

* sınıf [TextAbsorber](../textabsorber/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)