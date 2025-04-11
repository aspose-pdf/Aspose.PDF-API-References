---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber özelliği. Metin çıkarım seçeneklerini alır veya ayarlar
type: docs
weight: 30
url: /tr/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions özelliği

Metin çıkarım seçeneklerini alır veya ayarlar.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Açıklamalar

Çıkarma sırasında metin biçimlendirme modunu [`TextExtractionOptions`](../../textextractionoptions/) tanımlamaya olanak tanır. Varsayılan mod Pure'dur.

## Örnekler

Örnek, Pure metin biçimlendirme modunu nasıl ayarlayacağınızı ve metin çıkarımını nasıl gerçekleştireceğinizi göstermektedir.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### Ayrıca Bakınız

* sınıf [TextExtractionOptions](../../textextractionoptions/)
* sınıf [TextAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)