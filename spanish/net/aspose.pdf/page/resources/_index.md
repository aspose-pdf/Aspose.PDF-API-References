---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de página. Obtiene recursos de la página. El objeto Resources contiene colecciones de imágenes, formularios y fuentes. Resources
type: docs
weight: 240
url: /es/net/aspose.pdf/page/resources/
---
## Propiedad Page.Resources

Obtiene recursos de la página. El objeto Resources contiene colecciones de imágenes, formularios y fuentes. `Resources`

```csharp
public Resources Resources { get; }
```

## Ejemplos

El ejemplo demuestra cómo escanear a través de las imágenes de la página:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### Ver También

* clase [Resources](../../resources/)
* clase [Page](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)