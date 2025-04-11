---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Propiedad del documento. Obtiene o establece la colección de páginas del documento. Tenga en cuenta que las páginas están numeradas desde 1 en la colección.
type: docs
weight: 470
url: /es/net/aspose.pdf/document/pages/
---
## Propiedad Document.Pages

Obtiene o establece la colección de páginas del documento. Tenga en cuenta que las páginas están numeradas desde 1 en la colección.

```csharp
public PageCollection Pages { get; }
```

## Ejemplos

El ejemplo a continuación demuestra cómo operar con las páginas del documento: Cómo obtener el número de páginas y cómo obtener el rectángulo de la página de inicio del documento.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Véase también

* clase [PageCollection](../../pagecollection/)
* clase [Document](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)