---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de TextDevice. Obtiene o establece opciones de extracción de texto
type: docs
weight: 30
url: /es/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## Propiedad TextDevice.ExtractionOptions

Obtiene o establece opciones de extracción de texto.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo extraer texto en orden crudo.

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

### Ver También

* clase [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* clase [TextDevice](../)
* espacio de nombres [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* ensamblado [Aspose.PDF](../../../)