---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Método TextDevice. Convertir página y guardarla como flujo de texto
type: docs
weight: 40
url: /es/net/aspose.pdf.devices/textdevice/process/
---
## Método TextDevice.Process

Convertir página y guardarla como flujo de texto.

```csharp
public override void Process(Page page, Stream output)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Page | La página a convertir. |
| output | Stream | Flujo de resultado. |

## Ejemplos

El ejemplo demuestra cómo extraer texto de la primera página del documento PDF.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Ver También

* clase [Page](../../../aspose.pdf/page/)
* clase [TextDevice](../)
* espacio de nombres [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* ensamblaje [Aspose.PDF](../../../)