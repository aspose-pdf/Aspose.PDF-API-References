---
title: "TextDevice.Process"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo TextDevice. Converte la pagina e la salva come flusso di testo."
type: docs
weight: 40
url: /it/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

Converti la pagina e salvala come stream di testo.

```csharp
public override void Process(Page page, Stream output)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Page | La pagina da convertire. |
| output | Stream | Flusso di risultato. |

## Esempi

L'esempio dimostra come estrarre testo nella prima pagina del documento PDF.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // crea dispositivo di testo
    TextDevice device = new TextDevice();

    // converti la pagina e salva il testo nello stream
    device.Process(doc.Pages[1], ms);

    // usa il testo estratto
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Vedi anche

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


