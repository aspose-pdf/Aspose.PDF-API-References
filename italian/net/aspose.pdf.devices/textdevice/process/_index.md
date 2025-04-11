---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Metodo TextDevice. Converti la pagina e salvala come flusso di testo
type: docs
weight: 40
url: /it/net/aspose.pdf.devices/textdevice/process/
---
## Metodo TextDevice.Process

Converti la pagina e salvala come flusso di testo.

```csharp
public override void Process(Page page, Stream output)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Page | La pagina da convertire. |
| output | Stream | Flusso di risultato. |

## Esempi

L'esempio dimostra come estrarre il testo dalla prima pagina del documento PDF.

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

### Vedi Anche

* classe [Page](../../../aspose.pdf/page/)
* classe [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)