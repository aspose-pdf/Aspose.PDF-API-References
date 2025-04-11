---
title: CosPdfDictionary.Remove
second_title: Aspose.PDF for .NET API Reference
description: Método CosPdfDictionary. Elimina el elemento con la clave especificada del CosPdfDictionary
type: docs
weight: 150
url: /es/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

Elimina el elemento con la clave especificada del [`CosPdfDictionary`](../).

```csharp
public bool Remove(string key)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | String | La clave del elemento a eliminar. |

### Valor de Retorno

True si el elemento se elimina con éxito; de lo contrario, false. Este método también devuelve false si la clave no se encontró en el diccionario original o si la clave no es editable.

### Véase También

* clase [CosPdfDictionary](../)
* espacio de nombres [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* ensamblado [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Elimina la primera ocurrencia de un objeto específico del [`CosPdfDictionary`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | KeyValuePair`2 | El objeto a eliminar del [`CosPdfDictionary`](../). |

### Valor de Retorno

true si el item se eliminó con éxito del [`CosPdfDictionary`](../); de lo contrario, false. Este método también devuelve false si el item no se encuentra en el [`CosPdfDictionary`](../).

### Véase También

* interfaz [ICosPdfPrimitive](../../icospdfprimitive/)
* clase [CosPdfDictionary](../)
* espacio de nombres [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* ensamblado [Aspose.PDF](../../../)