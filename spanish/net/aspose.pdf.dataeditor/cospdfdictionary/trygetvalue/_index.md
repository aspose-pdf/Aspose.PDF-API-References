---
title: CosPdfDictionary.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: Método CosPdfDictionary. Para acceso a tipos de datos simples como cadena, nombre, booleano, número. Devuelve null para otros tipos
type: docs
weight: 170
url: /es/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## Método CosPdfDictionary.TryGetValue

Para acceso a tipos de datos simples como cadena, nombre, booleano, número. Devuelve null para otros tipos.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | String | Valor de la clave |
| value | ICosPdfPrimitive& | devuelve [`ICosPdfPrimitive`](../../icospdfprimitive/) para la clave o null. |

### Valor de Retorno

Devuelve true si [`ICosPdfPrimitive`](../../icospdfprimitive/) es como cadena, nombre, booleano, número. Devuelve false para todos los otros tipos.

### Véase También

* interfaz [ICosPdfPrimitive](../../icospdfprimitive/)
* clase [CosPdfDictionary](../)
* espacio de nombres [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* ensamblaje [Aspose.PDF](../../../)