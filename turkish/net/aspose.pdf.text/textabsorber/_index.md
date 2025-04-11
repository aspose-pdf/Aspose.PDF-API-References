---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextAbsorber sınıfı. Bir metin emici nesnesini temsil eder. Metin çıkarımı yapar ve sonucu [`Text`](./text/) nesnesi aracılığıyla erişime sunar.
type: docs
weight: 10800
url: /tr/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber sınıfı

Bir metin emici nesnesini temsil eder. Metin çıkarımı yapar ve sonucu [`Text`](./text/) nesnesi aracılığıyla erişime sunar.

```csharp
public class TextAbsorber
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | `TextAbsorber`'ın yeni bir örneğini başlatır. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Çıkarma seçenekleri ile `TextAbsorber`'ın yeni bir örneğini başlatır. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Metin arama seçenekleri ile `TextAbsorber`'ın yeni bir örneğini başlatır. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Çıkarma ve metin arama seçenekleri ile `TextAbsorber`'ın yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) nesnelerinin listesi. Metin çıkarımı sırasında bulunan hatalar hakkında bilgi içerir. Hataları arama, yalnızca TextSearchOptions.LogTextExtractionErrors = true; olduğunda yapılacaktır; ve bu performansı düşürebilir. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Metin çıkarım seçeneklerini alır veya ayarlar. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Değer, metin çıkarımı sırasında hataların bulunup bulunmadığını gösterir. Hataları arama, yalnızca TextSearchOptions.LogTextExtractionErrors = true; olduğunda yapılacaktır; ve bu performansı düşürebilir. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | `TextAbsorber`'ın PDF belgesinden veya sayfasından çıkardığı metni alır. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Metin arama seçeneklerini alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Belirtilen belgede metin çıkarır. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Belirtilen sayfada metin çıkarır. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Belirtilen XForm'da metin çıkarır. |

## Açıklamalar

`TextAbsorber` nesnesi, bir PDF belgesinden veya belgenin sayfasından metin çıkarmak için kullanılır.

## Örnekler

Örnek, ilk PDF belgesi sayfasında metin çıkarmayı gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)