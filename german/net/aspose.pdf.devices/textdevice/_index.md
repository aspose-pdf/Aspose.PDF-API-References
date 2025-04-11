---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TextDevice-Klasse. Stellt eine Klasse zum Konvertieren von PDF-Dokumentseiten in Text dar.
type: docs
weight: 3680
url: /de/net/aspose.pdf.devices/textdevice/
---
## TextDevice-Klasse

Stellt eine Klasse zum Konvertieren von PDF-Dokumentseiten in Text dar.

```csharp
public sealed class TextDevice : PageDevice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Initialisiert eine neue Instanz von `TextDevice` mit dem Rohtextformatierungsmodus und der Unicode-Textkodierung. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Initialisiert eine neue Instanz von `TextDevice` für die angegebene Kodierung. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Initialisiert eine neue Instanz von `TextDevice` mit Textextraktionsoptionen. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Initialisiert eine neue Instanz von `TextDevice` für die angegebene Kodierung mit Textextraktionsoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Ruft die Kodierung des extrahierten Textes ab oder legt sie fest. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Ruft die Textextraktionsoptionen ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Konvertiert die Seite und speichert sie als Textstream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine Operation auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

## Bemerkungen

Das `TextDevice`-Objekt wird im Wesentlichen verwendet, um Text von einer PDF-Seite zu extrahieren.

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [PageDevice](../pagedevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)