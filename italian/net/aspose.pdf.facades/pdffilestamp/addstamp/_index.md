---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileStamp. Aggiunge un timbro al file
type: docs
weight: 140
url: /it/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## Metodo PdfFileStamp.AddStamp

Aggiunge un timbro al file.

```csharp
public void AddStamp(Stamp stamp)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stamp | Stamp | Oggetto timbro che. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Vedi Anche

* classe [Stamp](../../stamp/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)