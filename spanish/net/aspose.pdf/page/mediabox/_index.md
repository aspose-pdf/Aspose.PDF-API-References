---
title: Page.MediaBox
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de la página. Obtiene o establece el cuadro de medios de la página
type: docs
weight: 180
url: /es/net/aspose.pdf/page/mediabox/
---
## Propiedad Page.MediaBox

Obtiene o establece el cuadro de medios de la página.

```csharp
public Rectangle MediaBox { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo obtener el cuadro de medios de la página:

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### Véase también

* clase [Rectangle](../../rectangle/)
* clase [Page](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)