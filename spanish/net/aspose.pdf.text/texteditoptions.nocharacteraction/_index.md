---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Enum de Aspose.Pdf.Text.TextEditOptionsNoCharacterAction. Acción a realizar si la fuente no contiene el carácter requerido
type: docs
weight: 10860
url: /es/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## Enumeración TextEditOptions.NoCharacterAction

Acción a realizar si la fuente no contiene el carácter requerido

```csharp
public enum NoCharacterAction
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ThrowException | `0` | Lanzar excepción |
| UseStandardFont | `1` | Reemplazar fuente por una fuente estándar que contenga el carácter requerido |
| ReplaceAnyway | `2` | Reemplazar texto de todos modos sin sustitución de fuente |
| ReplaceFonts | `3` | Reemplaza fuentes según sea necesario para asegurar que todos los caracteres en el texto puedan ser mostrados. El algoritmo de sustitución de fuentes sigue estos pasos: 1. Si el usuario establece explícitamente la propiedad Font, verifica si la fuente especificada puede mostrar los caracteres deseados. 2. Si no se establece ninguna fuente definida por el usuario, busca entre las fuentes añadidas a través de los [`Sources`](../fontrepository/sources/). 3. Analiza el texto para identificar su alfabeto o escritura y sugiere nombres de fuentes en consecuencia. Intenta localizar y usar estas fuentes del sistema. 4. Como último recurso, busca en el sistema cualquier fuente capaz de mostrar los caracteres requeridos. |
| UseCustomReplacementFont | `4` | Reemplazar fuente por la fuente de reemplazo definida |

### Ver También

* clase [TextEditOptions](../texteditoptions/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblaje [Aspose.PDF](../../)