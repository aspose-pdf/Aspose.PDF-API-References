---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de página. Obtiene o establece la duración de visualización de la página. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve 1 si la duración no está definida
type: docs
weight: 110
url: /es/net/aspose.pdf/page/duration/
---
## Propiedad Page.Duration

Obtiene o establece la duración de visualización de la página. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve -1 si la duración no está definida.

```csharp
public double Duration { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo obtener la duración de la página

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Ver También

* clase [Page](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)