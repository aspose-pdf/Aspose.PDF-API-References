---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de la página. Obtiene o establece el rectángulo de la página. Para obtener, se devuelve el cuadro de recorte de la página si se especifica, de lo contrario se devuelve el cuadro de medios de la página. Para establecer, siempre se establece el cuadro de medios de la página. Tenga en cuenta que esta propiedad no considera la rotación de la página. Para obtener el rectángulo de la página considerando la rotación, utilice ActualRect.
type: docs
weight: 230
url: /es/net/aspose.pdf/page/rect/
---
## Propiedad Page.Rect

Obtiene o establece el rectángulo de la página. Para obtener: se devuelve el cuadro de recorte de la página si se especifica, de lo contrario se devuelve el cuadro de medios de la página. Para establecer: siempre se establece el cuadro de medios de la página. Tenga en cuenta que esta propiedad no considera la rotación de la página. Para obtener el rectángulo de la página considerando la rotación, utilice ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo obtener el rectángulo de la página:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Ver También

* clase [Rectangle](../../rectangle/)
* clase [Page](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)