---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: Método DictionaryEditor. Elimina el elemento con la clave especificada del DictionaryEditor
type: docs
weight: 140
url: /es/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

Elimina el elemento con la clave especificada del [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | String | La clave del elemento a eliminar. |

### Valor de Retorno

True si el elemento se elimina con éxito; de lo contrario, false. Este método también devuelve false si la clave no se encontró en el diccionario original o si la clave no es editable.

### Véase También

* clase [DictionaryEditor](../)
* espacio de nombres [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* ensamblado [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Elimina la primera ocurrencia de un objeto específico del [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | KeyValuePair`2 | El objeto a eliminar del [`DictionaryEditor`](../). |

### Valor de Retorno

true si el item se eliminó con éxito del [`DictionaryEditor`](../); de lo contrario, false. Este método también devuelve false si el item no se encuentra en el [`DictionaryEditor`](../) original.

### Véase También

* interfaz [ICosPdfPrimitive](../../icospdfprimitive/)
* clase [DictionaryEditor](../)
* espacio de nombres [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* ensamblado [Aspose.PDF](../../../)