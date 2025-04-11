---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Devices.TextDevice. Representa una clase para convertir páginas de documentos pdf en texto
type: docs
weight: 3680
url: /es/net/aspose.pdf.devices/textdevice/
---
## Clase TextDevice

Representa una clase para convertir páginas de documentos pdf en texto.

```csharp
public sealed class TextDevice : PageDevice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Inicializa una nueva instancia de `TextDevice` con el modo de formato de texto sin procesar y codificación de texto Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Inicializa una nueva instancia de `TextDevice` para la codificación especificada. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Inicializa una nueva instancia de `TextDevice` con opciones de extracción de texto. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Inicializa una nueva instancia de `TextDevice` para la codificación especificada con opciones de extracción de texto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Obtiene o establece la codificación del texto extraído. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Obtiene o establece las opciones de extracción de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Convierte la página y la guarda como un flujo de texto. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |

## Observaciones

El objeto `TextDevice` se utiliza básicamente para extraer texto de la página pdf.

## Ejemplos

El ejemplo demuestra cómo extraer texto en la primera página del documento PDF.

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

### Véase también

* clase [PageDevice](../pagedevice/)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* ensamblado [Aspose.PDF](../../)