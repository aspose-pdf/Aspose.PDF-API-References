---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de la página. Obtiene o establece el recuadro de corte de la página
type: docs
weight: 290
url: /es/net/aspose.pdf/page/trimbox/
---
## Propiedad Page.TrimBox

Obtiene o establece el recuadro de corte de la página.

```csharp
public Rectangle TrimBox { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo obtener el recuadro de corte de la página:

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### Ver También

* clase [Rectangle](../../rectangle/)
* clase [Page](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)