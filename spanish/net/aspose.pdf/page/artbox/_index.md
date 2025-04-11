---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de la página. Obtiene o establece el cuadro de arte de la página
type: docs
weight: 30
url: /es/net/aspose.pdf/page/artbox/
---
## Propiedad Page.ArtBox

Obtiene o establece el cuadro de arte de la página.

```csharp
public Rectangle ArtBox { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo obtener el cuadro de arte de la página:

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### Ver También

* clase [Rectangle](../../rectangle/)
* clase [Page](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)