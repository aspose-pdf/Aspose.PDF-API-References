---
title: DictionaryEditor.Item
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de DictionaryEditor. Obtiene o establece el elemento con la clave especificada
type: docs
weight: 50
url: /es/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## Indexador de DictionaryEditor

Obtiene o establece el elemento con la clave especificada.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| key | La clave del elemento a obtener o establecer. |

### Valor de Retorno

El elemento con la clave especificada.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | La clave es nula. |
| KeyNotFoundException | La propiedad se recupera y la clave no se encuentra. |
| ArgumentException | Lanza una excepción si la clave no se puede editar/establecer. |

### Véase También

* interfaz [ICosPdfPrimitive](../../icospdfprimitive/)
* clase [DictionaryEditor](../)
* espacio de nombres [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* ensamblado [Aspose.PDF](../../../)