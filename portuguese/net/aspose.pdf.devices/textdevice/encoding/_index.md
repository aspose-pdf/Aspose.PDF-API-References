---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextDevice. Obtém ou define a codificação do texto extraído
type: docs
weight: 20
url: /pt/net/aspose.pdf.devices/textdevice/encoding/
---
## Propriedade TextDevice.Encoding

Obtém ou define a codificação do texto extraído.

```csharp
public Encoding Encoding { get; set; }
```

## Exemplos

O exemplo demonstra como representar o texto extraído na codificação UTF-8.

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

### Veja Também

* classe [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)