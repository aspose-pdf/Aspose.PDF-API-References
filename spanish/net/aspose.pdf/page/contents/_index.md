---
title: Contents
second_title: Referencia de API de Aspose.PDF para .NET
description: Obtiene una colección de operadores en el flujo de contenido de la página. OperatorCollectionaspose.pdf/operatorcollection
type: docs
weight: 90
url: /es/net/aspose.pdf/page/contents/
---
## Page.Contents property

Obtiene una colección de operadores en el flujo de contenido de la página. [`OperatorCollection`](../../operatorcollection)

```csharp
public OperatorCollection Contents { get; }
```

### Ejemplos

El ejemplo muestra cómo escanear el flujo de página de los operadores.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Ver también

* class [OperatorCollection](../../operatorcollection)
* class [Page](../../page)
* espacio de nombres [Aspose.Pdf](../../page)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->