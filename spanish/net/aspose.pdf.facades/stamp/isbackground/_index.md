---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Propiedad Stamp. Obtiene o establece el estado de fondo. Si es verdadero, el sello se colocará como fondo de la página sellada. Por defecto se establece en falso.
type: docs
weight: 30
url: /es/net/aspose.pdf.facades/stamp/isbackground/
---
## Propiedad Stamp.IsBackground

Obtiene o establece el estado de fondo. Si es verdadero, el sello se colocará como fondo de la página sellada. Por defecto se establece en falso.

```csharp
public bool IsBackground { get; set; }
```

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ver También

* clase [Stamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)