---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.MarkdownSaveOptions. Representa la clase de opciones de guardado de documentos en formato markdown
type: docs
weight: 6910
url: /es/net/aspose.pdf/markdownsaveoptions/
---
## Clase MarkdownSaveOptions

Representa la clase de opciones de guardado de documentos en formato markdown.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Obtiene o establece un área rectangular para extraer contenido a markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtiene o establece un valor booleano que indica si se almacenarán en caché los glifos de fuente mientras se preparan las páginas aps. Mejora el rendimiento de la conversión de pdf a otros formatos, pero aumenta el consumo de memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtiene o establece un valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Obtiene o establece el estilo de énfasis para el documento generado. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo activa la funcionalidad para extraer imágenes o texto de documentos PDF con subcapa OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Obtiene y establece una propiedad que indica si se deben extraer gráficos vectoriales. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Define los niveles de encabezado esperados para usar en la estrategia de reconocimiento de encabezados FontSize. Si se establece el valor de esta propiedad, se seleccionará la estrategia de reconocimiento de encabezados !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic cuando se establezcan las estrategias !:PdfToMarkdown.HeadingRecognitionStrategy.Auto, incluso si el documento contiene marcadores. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Obtiene o establece la estrategia de reconocimiento de encabezados. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Obtiene o establece el estilo de encabezado para el documento generado. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Obtiene o establece el estilo de salto de línea para el documento generado. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Obtiene y establece el nombre del directorio para guardar los recursos del documento, como imágenes. Si no se especifica el valor, las imágenes se escribirán en el mismo directorio que el archivo markdown. ¡Esto no es una ruta, solo es un nombre! Este directorio se creará automáticamente en el directorio con el archivo markdown guardado. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de guardado de datos. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Obtiene y establece la posibilidad de convertir subíndices y superíndices. Este valor es verdadero por defecto. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Obtiene y establece la posibilidad de usar una etiqueta img para insertar imágenes a la izquierda y derecha del texto. En este caso, en el visor de markdown, el texto se ajustará alrededor de la imagen. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve un elemento de enumeración ReturnAction que especifica Continuar o Abortar. Continuar es la acción predeterminada y la operación de guardado continúa, sin embargo, el usuario también puede devolver Abortar, en cuyo caso la operación de guardado debe cesar. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Procesar páginas en varios hilos. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A veces, los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico iguales colocadas una cerca de la otra. En tal caso, los renderizadores de formatos de destino (por ejemplo, MsWord para el formato DOCS) a veces generan límites visibles entre partes de imágenes de fondo, ya que sus técnicas de suavizado de bordes de imagen (anti-aliasing) son diferentes de Acrobat Reader. Si parece que el documento exportado contiene tales límites visibles entre partes de las mismas imágenes de fondo, intente usar esta configuración para deshacerse de ese efecto no deseado. ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión, así que, por favor, use esta opción solo cuando sea realmente necesario. |

### Véase También

* clase [UnifiedSaveOptions](../unifiedsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)