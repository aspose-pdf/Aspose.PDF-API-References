---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de TextDevice. Obtiene o establece la codificación del texto extraído
type: docs
weight: 20
url: /es/net/aspose.pdf.devices/textdevice/encoding/
---
## Propiedad TextDevice.Encoding

Obtiene o establece la codificación del texto extraído.

```csharp
public Encoding Encoding { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo representar el texto extraído en codificación UTF-8.

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

### Ver También

* clase [TextDevice](../)
* espacio de nombres [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* ensamblado [Aspose.PDF](../../../)