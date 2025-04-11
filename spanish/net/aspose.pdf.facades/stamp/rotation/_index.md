---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Propiedad Stamp. Obtiene o establece la rotación del sello en grados
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/stamp/rotation/
---
## Propiedad Stamp.Rotation

Obtiene o establece la rotación del sello en grados.

```csharp
public float Rotation { get; set; }
```

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ver También

* clase [Stamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)