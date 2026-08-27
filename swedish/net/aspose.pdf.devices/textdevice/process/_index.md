---
title: "TextDevice.Process"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextDevice-metoden. Konvertera sidan och spara den som textström"
type: docs
weight: 40
url: /sv/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

Konvertera sidan och spara den som textström.

```csharp
public override void Process(Page page, Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Page | Sidan som ska konverteras. |
| utdata | Stream | Resultatström. |

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

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


