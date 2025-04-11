---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de OperatorCollection. Obtiene el operador por su índice
type: docs
weight: 40
url: /es/net/aspose.pdf/operatorcollection/item/
---
## Indexador de OperatorCollection

Obtiene el operador por su índice.

```csharp
public override Operator this[int index] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| index | Índice del operador. La numeración comienza desde 1. |

### Valor de Retorno

Operador del índice solicitado

## Ejemplos

El ejemplo demuestra cómo obtener el operador del contenido de la página por índice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Ver También

* clase [Operator](../../operator/)
* clase [OperatorCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)