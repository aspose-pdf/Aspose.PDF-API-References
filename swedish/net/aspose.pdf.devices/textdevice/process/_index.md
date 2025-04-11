---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: TextDevice-metod. Konvertera sidan och spara den som textström
type: docs
weight: 40
url: /sv/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process metod

Konvertera sidan och spara den som textström.

```csharp
public override void Process(Page page, Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Page | Sidan som ska konverteras. |
| output | Stream | Resultatström. |

## Exempel

Exemplet visar hur man extraherar text från den första sidan i PDF-dokumentet.

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

* klass [Page](../../../aspose.pdf/page/)
* klass [TextDevice](../)
* namnrymd [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)