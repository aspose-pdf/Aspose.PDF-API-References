---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Enum TextReplaceOptions.ReplaceAdjustment de Aspose.Pdf.Text. Determina la acción que se realizará después de reemplazar un fragmento de texto por uno más corto. Ninguno sin acción, el texto reemplazado puede superponerse al resto de la línea; AjustarAnchoEspacio intenta ajustar los espacios entre palabras para mantener la longitud de la línea; HifenaciónPalabrasCompletas intenta distribuir las palabras entre las líneas del párrafo para mantener el campo derecho del párrafo; DesplazarRestoDeLaLínea desplaza el resto de la línea de acuerdo con el cambio de longitud del texto, la longitud de la línea puede cambiar; El valor predeterminado es DesplazarRestoDeLaLínea.
type: docs
weight: 11020
url: /es/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## Enumeración TextReplaceOptions.ReplaceAdjustment

Determina la acción que se realizará después de reemplazar un fragmento de texto por uno más corto. Ninguno - sin acción, el texto reemplazado puede superponerse al resto de la línea; AjustarAnchoEspacio - intenta ajustar los espacios entre palabras para mantener la longitud de la línea; HifenaciónPalabrasCompletas - intenta distribuir las palabras entre las líneas del párrafo para mantener el campo derecho del párrafo; DesplazarRestoDeLaLínea - desplaza el resto de la línea de acuerdo con el cambio de longitud del texto, la longitud de la línea puede cambiar; El valor predeterminado es DesplazarRestoDeLaLínea.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | `0` | Sin acción, el texto reemplazado puede superponerse al resto de la línea |
| AjustarAnchoEspacio | `1` | Intenta ajustar los espacios entre palabras para mantener la longitud de la línea |
| HifenaciónPalabrasCompletas | `2` | Intenta distribuir las palabras entre las líneas del párrafo para mantener el campo derecho del párrafo |
| EsModoRellenoDeFormulario | `4` | Intenta distribuir las palabras en el espacio en blanco disponible utilizando el ancho del párrafo. Si el texto desborda, se ocultará. |
| DesplazarRestoDeLaLínea | `8` | (Predeterminado) Desplaza el resto de la línea de acuerdo con el cambio de longitud del texto, la longitud de la línea puede cambiar |

### Ver También

* clase [TextReplaceOptions](../textreplaceoptions/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblaje [Aspose.PDF](../../)