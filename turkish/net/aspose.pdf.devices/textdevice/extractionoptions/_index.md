---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextDevice özelliği. Metin çıkarım seçeneklerini alır veya ayarlar
type: docs
weight: 30
url: /tr/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions özelliği

Metin çıkarım seçeneklerini alır veya ayarlar.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Örnekler

Örnek, metni ham sırada nasıl çıkaracağınızı gösterir.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Ayrıca Bakınız

* sınıf [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* sınıf [TextDevice](../)
* ad alanı [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../../)