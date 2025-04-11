---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de la página. Obtiene o establece el cuadro de recorte de la página
type: docs
weight: 100
url: /es/net/aspose.pdf/page/cropbox/
---
## Propiedad Page.CropBox

Obtiene o establece el cuadro de recorte de la página.

```csharp
public Rectangle CropBox { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo obtener el cuadro de recorte de la página:

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### Véase también

* clase [Rectangle](../../rectangle/)
* clase [Page](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)