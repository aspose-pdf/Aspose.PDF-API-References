---
title: ExtractionOptions
second_title: Aspose.PDF for .NET API Referansı
description: Metin çıkarma seçeneklerini alır veya ayarlar.
type: docs
weight: 30
url: /tr/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

Metin çıkarma seçeneklerini alır veya ayarlar.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

### Örnekler

Örnek, metnin ham sırada nasıl çıkarılacağını gösterir.

```csharp
Document doc = new Document(inFile);
string extractedText;

// metin aygıtı oluştur
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// sayfayı dönüştür ve metni akışa kaydet
device.Process(doc.Pages[1], outFile);

// ayıklanan metni kullan
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Ayrıca bakınız

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions)
* class [TextDevice](../../textdevice)
* ad alanı [Aspose.Pdf.Devices](../../textdevice)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->