---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: TextDevice-Methode. Konvertieren Sie die Seite und speichern Sie sie als Textstream
type: docs
weight: 40
url: /de/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process-Methode

Konvertieren Sie die Seite und speichern Sie sie als Textstream.

```csharp
public override void Process(Page page, Stream output)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Page | Die zu konvertierende Seite. |
| output | Stream | Ergebnisstream. |

## Beispiele

Das Beispiel zeigt, wie man Text von der ersten Seite des PDF-Dokuments extrahiert.

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

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [TextDevice](../)
* Namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../../)