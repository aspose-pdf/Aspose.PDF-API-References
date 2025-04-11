---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileStamp. Adiciona carimbo ao arquivo
type: docs
weight: 140
url: /pt/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## Método PdfFileStamp.AddStamp

Adiciona carimbo ao arquivo.

```csharp
public void AddStamp(Stamp stamp)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stamp | Stamp | Objeto de carimbo que. |

## Exemplos

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

### Veja Também

* classe [Stamp](../../stamp/)
* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)