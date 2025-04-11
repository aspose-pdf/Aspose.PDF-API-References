---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TextDevice klass. Representerar klass för att konvertera pdf-dokument sidor till text
type: docs
weight: 3680
url: /sv/net/aspose.pdf.devices/textdevice/
---
## TextDevice klass

Representerar klass för att konvertera pdf-dokument sidor till text.

```csharp
public sealed class TextDevice : PageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Initierar en ny instans av `TextDevice` med rå textformateringsläge och Unicode-teckenkodning. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Initierar en ny instans av `TextDevice` för den angivna kodningen. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Initierar en ny instans av `TextDevice` med textutvinningsalternativ. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Initierar en ny instans av `TextDevice` för den angivna kodningen med textutvinningsalternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Hämtar eller ställer in kodningen av den extraherade texten. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Hämtar eller ställer in textutvinningsalternativ. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Konverterar sidan och sparar den som textström. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför en operation på den angivna sidan och sparar resultaten i filen. |

## Kommentarer

`TextDevice`-objektet används i grunden för att extrahera text från pdf-sidan.

## Exempel

Exemplet visar hur man extraherar text på den första PDF-dokument sidan.

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

### Se Även

* klass [PageDevice](../pagedevice/)
* namnrymd [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)