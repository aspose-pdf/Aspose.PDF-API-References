---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TextSearchOptions. Representa opciones de búsqueda de texto
type: docs
weight: 11040
url: /es/net/aspose.pdf.text/textsearchoptions/
---
## Clase TextSearchOptions

Representa opciones de búsqueda de texto

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Inicializa una nueva instancia del objeto `TextSearchOptions`. Especifica el modo de uso de expresiones regulares. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Inicializa una nueva instancia del objeto `TextSearchOptions`. Especifica el rectángulo que delimita el texto buscado. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Inicializa una nueva instancia del objeto `TextSearchOptions`. Especifica el rectángulo que delimita el texto buscado y el modo de uso de expresiones regulares. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Obtiene o establece la indicación de que se ignorarán los errores relacionados con la ausencia de fuentes por el absorbedor de texto (fragmento). verdadero - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que se refieren a recursos incorrectos se omitirán durante el procesamiento. falso (predeterminado) - el error de ausencia de fuente terminará el procesamiento lanzando una excepción. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Obtiene o establece la indicación de que los fragmentos de texto que representan la sombra del texto normal se ignorarán durante la búsqueda. verdadero - significa que no se encontrará texto en sombra (prueba esto si la búsqueda de texto devuelve fragmentos duplicados en posiciones cercanas) falso - significa que se encontrará texto en sombra así como texto normal (valor predeterminado) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Obtiene o establece la indicación de que se utiliza una expresión regular. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Obtiene o establece la indicación de que el texto se busca dentro de los límites de la página. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Obtiene o establece la indicación de que los errores de extracción de texto (decodificación) se registrarán en el absorbedor de texto (fragmento). verdadero - significa que se registrarán los errores de extracción de texto (decodificación). Puede disminuir el rendimiento. falso (predeterminado) - sin registro de errores. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Obtiene o establece el rectángulo que limita el texto buscado. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Obtiene o establece el valor que permite buscar gráficos relacionados con el texto (subrayado, fondo, etc.) durante la búsqueda de texto. verdadero - se realizará la búsqueda de gráficos relacionados con el texto (valor predeterminado). falso - se ignorarán los elementos gráficos que pueden estar presentes en el documento fuente. Establezca esto en caso de problemas de rendimiento o si no es necesario manejar subrayados, fondos o recortes. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Obtiene o establece el valor que permite buscar texto en Anotaciones. verdadero - se buscará texto en Anotaciones. falso - el texto en Anotaciones no será analizado por TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Obtiene o establece el valor que limita la búsqueda de gráficos relacionados con el texto (subrayado, fondo, etc.) en una página para el número especificado de elementos. El valor predeterminado es 250. Establezca un valor menor en caso de problemas de rendimiento, intente un valor mayor en caso de que no se encuentren algunos elementos gráficos. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Obtiene o establece la indicación de que el texto se buscará utilizando la codificación del motor de fuentes. verdadero - significa que se utilizará la codificación del motor de fuentes (prueba esto si la búsqueda de texto falla debido a una codificación imperfecta en el documento) falso - significa que se utilizará la codificación de fuentes del documento (valor predeterminado) |

### Véase también

* clase [TextOptions](../textoptions/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblaje [Aspose.PDF](../../)