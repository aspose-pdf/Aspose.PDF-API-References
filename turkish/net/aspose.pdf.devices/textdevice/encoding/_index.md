---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: TextDevice özelliği. Çıkarılan metnin kodlamasını alır veya ayarlar
type: docs
weight: 20
url: /tr/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding özelliği

Çıkarılan metnin kodlamasını alır veya ayarlar.

```csharp
public Encoding Encoding { get; set; }
```

## Örnekler

Örnek, çıkarılan metni UTF-8 kodlamasında nasıl temsil edeceğini göstermektedir.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(Encoding.UTF8);

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### Ayrıca Bakınız

* sınıf [TextDevice](../)
* ad alanı [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../../)