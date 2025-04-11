---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsFontEncodingRules de Aspose.Pdf. Esta enumeración define reglas que ajustan la lógica de codificación
type: docs
weight: 5620
url: /es/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## Enumeración HtmlSaveOptions.FontEncodingRules

Esta enumeración define reglas que ajustan la lógica de codificación

```csharp
public enum FontEncodingRules : byte
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Default | `0` | Dejar la lógica de codificación "tal cual" - de acuerdo con la especificación PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode es un mecanismo especial que ayuda a decodificar códigos de entrada a símbolos unicode. De acuerdo con la especificación, debe ser utilizado primero de todos los mecanismos para obtener símbolos unicode para un código de entrada específico. Pero algunos documentos tienen fuentes no estándar y para convertir estos documentos correctamente puede ser necesario disminuir la prioridad de ToUnicode y utilizar otros mecanismos para decodificar los códigos de entrada. |

### Ver También

* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)