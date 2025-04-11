---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Método TextDevice. Converte a página e a salva como fluxo de texto
type: docs
weight: 40
url: /pt/net/aspose.pdf.devices/textdevice/process/
---
## Método TextDevice.Process

Converte a página e a salva como fluxo de texto.

```csharp
public override void Process(Page page, Stream output)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Page | A página a ser convertida. |
| output | Stream | Fluxo de resultado. |

## Exemplos

O exemplo demonstra como extrair texto na primeira página do documento PDF.

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

### Veja Também

* classe [Page](../../../aspose.pdf/page/)
* classe [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)