---
title: "Klass TextDevice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Devices.TextDevice class. Representerar en klass för att konvertera pdf-dokumentets sidor till text"
type: docs
weight: 3800
url: /sv/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

Representerar klass för att konvertera PDF-dokumentets sidor till text.

```csharp
public sealed class TextDevice : PageDevice
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Initierar en ny instans av `TextDevice` med råtextformateringsläge och Unicode-textkodning. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Initierar en ny instans av `TextDevice` för den angivna kodningen. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Initierar en ny instans av `TextDevice` med alternativ för textutdragning. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Initierar en ny instans av `TextDevice` för den angivna kodningen med alternativ för textutdragning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Hämtar eller anger kodning för extraherad text. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Hämtar eller anger alternativ för textutdragning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Konvertera sidan och spara den som textström. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultatet i filen. |

## Anmärkningar

`TextDevice`-objektet används i huvudsak för att extrahera text från en pdf-sida.

## Exempel

Exemplet visar hur man extraherar text på den första PDF-dokumentets sida.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // skapa textenhet
    TextDevice device = new TextDevice();

    // konvertera sidan och spara texten till strömmen
    device.Process(doc.Pages[1], ms);

    // använd den extraherade texten
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Se även

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


