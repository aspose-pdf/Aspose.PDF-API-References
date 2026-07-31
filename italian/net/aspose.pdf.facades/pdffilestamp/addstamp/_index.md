---
title: "PdfFileStamp.AddStamp"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfFileStamp metodo. Aggiunge il timbro al file"
type: docs
weight: 140
url: /it/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp method

Aggiunge il timbro al file.

```csharp
public void AddStamp(Stamp stamp)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| timbro | Timbro | Oggetto timbro. |

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

### Vedi anche

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


