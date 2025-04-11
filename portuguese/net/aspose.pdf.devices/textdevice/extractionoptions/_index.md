---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextDevice. Obtém ou define opções de extração de texto
type: docs
weight: 30
url: /pt/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## Propriedade TextDevice.ExtractionOptions

Obtém ou define opções de extração de texto.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Exemplos

O exemplo demonstra como extrair texto na ordem bruta.

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

### Veja Também

* classe [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* classe [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)