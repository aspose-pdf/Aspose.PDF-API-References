---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: Método DictionaryEditor. Para acceso a tipos de datos simples como string, nombre, bool, número. Devuelve null para otros tipos
type: docs
weight: 150
url: /es/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## Método DictionaryEditor.TryGetValue

Para acceso a tipos de datos simples como string, nombre, bool, número. Devuelve null para otros tipos.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | String | Valor de la clave |
| value | ICosPdfPrimitive& | devuelve [`ICosPdfPrimitive`](../../icospdfprimitive/) para la clave o null. |

### Valor de Retorno

Devuelve true si [`ICosPdfPrimitive`](../../icospdfprimitive/) es como string, nombre, bool, número. Devuelve false para todos los otros tipos.

### Véase También

* interfaz [ICosPdfPrimitive](../../icospdfprimitive/)
* clase [DictionaryEditor](../)
* espacio de nombres [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* ensamblaje [Aspose.PDF](../../../)