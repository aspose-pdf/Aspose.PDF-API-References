---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TextEditOptions. Descubre opciones de operaciones de edición de texto
type: docs
weight: 10820
url: /es/net/aspose.pdf.text/texteditoptions/
---
## Clase TextEditOptions

Descubre opciones de operaciones de edición de texto.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Inicializa una nueva instancia del objeto `TextEditOptions` para el permiso de transformación de idioma especificado. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Inicializa una nueva instancia del objeto `TextEditOptions` para el modo de comportamiento de reemplazo de fuente especificado. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Inicializa una nueva instancia del objeto `TextEditOptions` para el modo de comportamiento de transformación de idioma especificado. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Inicializa una nueva instancia del objeto `TextEditOptions` para el modo de comportamiento sin carácter especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Obtiene o establece el valor que permite el uso de la transformación de idioma durante la adición o edición de texto. true - se aplicará la transformación de idioma si es necesario (valor predeterminado). false - NO se aplicará la transformación de idioma. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Obtiene el modo para procesar la ruta de recorte del texto editado. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Obtiene el modo que define el comportamiento para escenarios de reemplazo de fuentes. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Obtiene el modo que define el comportamiento para escenarios de transformación de idioma. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Obtiene o establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Obtiene o establece el valor que permite buscar subrayado de texto en la página del documento fuente. (Obsoleto) Por favor, use TextSearchOptions.SearchForTextRelatedGraphics en su lugar. |

### Ver También

* clase [TextOptions](../textoptions/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../)