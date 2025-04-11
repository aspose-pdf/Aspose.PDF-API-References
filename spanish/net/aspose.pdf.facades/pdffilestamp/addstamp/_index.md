---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileStamp. Agrega un sello al archivo
type: docs
weight: 140
url: /es/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## Método PdfFileStamp.AddStamp

Agrega un sello al archivo.

```csharp
public void AddStamp(Stamp stamp)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stamp | Stamp | Objeto de sello que. |

## Ejemplos

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

### Ver También

* clase [Stamp](../../stamp/)
* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)