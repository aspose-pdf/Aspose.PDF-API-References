---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de página. Obtiene la colección de operadores en el flujo de contenido de la página. OperatorCollection
type: docs
weight: 90
url: /es/net/aspose.pdf/page/contents/
---
## Propiedad Page.Contents

Obtiene la colección de operadores en el flujo de contenido de la página. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Ejemplos

El ejemplo demuestra cómo escanear el flujo de operadores de la página.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Ver También

* clase [OperatorCollection](../../operatorcollection/)
* clase [Page](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)