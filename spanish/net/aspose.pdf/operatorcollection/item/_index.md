---
title: Item
second_title: Referencia de API de Aspose.PDF para .NET
description: Obtiene el operador por su índice.
type: docs
weight: 40
url: /es/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

Obtiene el operador por su índice.

```csharp
public override Operator this[int index] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| index | Índice de operador. La numeración se inicia desde 1. |

### Valor_devuelto

Operador del índice solicitado

### Ejemplos

El ejemplo demuestra cómo obtener el operador del contenido de la página por index.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Ver también

* class [Operator](../../operator)
* class [OperatorCollection](../../operatorcollection)
* espacio de nombres [Aspose.Pdf](../../operatorcollection)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->