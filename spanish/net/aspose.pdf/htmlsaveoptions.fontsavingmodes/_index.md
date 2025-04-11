---
title: Enum HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsFontSavingModes de Aspose.Pdf. Enumera los modos que se pueden utilizar para guardar las fuentes referenciadas en el PDF guardado
type: docs
weight: 5630
url: /es/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## Enumeración HtmlSaveOptions.FontSavingModes

Enumera los modos que se pueden utilizar para guardar las fuentes referenciadas en el PDF guardado.

```csharp
public enum FontSavingModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | Todas las fuentes referenciadas se guardarán y se referenciarán como fuentes WOFF. |
| AlwaysSaveAsTTF | `1` | Todas las fuentes referenciadas se guardarán y se referenciarán como fuentes TTF. |
| AlwaysSaveAsEOT | `2` | Todas las fuentes referenciadas se guardarán y se referenciarán como fuentes EOT. |
| SaveInAllFormats | `3` | Todas las fuentes referenciadas se guardarán (y se referenciarán en CSS) como 3 archivos independientes: EOT, TTH, WOFF. Aumenta el tamaño de los datos de salida, pero hace que la salida sea adecuada para la abrumadora mayoría de los navegadores web. |
| DontSave | `4` | Todas las fuentes referenciadas no se guardarán. |

### Véase también

* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)