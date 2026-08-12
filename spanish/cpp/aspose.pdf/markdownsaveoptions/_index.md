---
title: "Aspose::Pdf::MarkdownSaveOptions clase"
linktitle: "MarkdownSaveOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::MarkdownSaveOptions. Representa la clase de opción de guardado de documento en formato markdown en C++."
type: docs
weight: 10800
url: /es/cpp/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class


Representa la clase de opción de guardado de documento en formato markdown.

```cpp
class MarkdownSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AreaToExtract](./get_areatoextract/)() const | Obtenga o establezca un área rectangular para extraer contenido a markdown. |
| [get_EmphasisStyle](./get_emphasisstyle/)() const | Obtiene el estilo de énfasis para el documento generado. |
| [get_ExtractVectorGraphics](./get_extractvectorgraphics/)() const | Obtiene y establece una propiedad que indica si se deben extraer gráficos vectoriales. |
| [get_HeadingLevels](./get_headinglevels/)() const | Define los niveles de encabezado esperados para usar en la estrategia de reconocimiento de encabezados por tamaño de fuente. Si se establece este valor de propiedad, entonces la estrategia de reconocimiento de encabezados [HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) se seleccionará cuando se configuren las estrategias [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../) incluso si el documento contiene marcadores. |
| [get_HeadingRecognitionStrategy](./get_headingrecognitionstrategy/)() const | Obtiene la estrategia de reconocimiento de encabezados. |
| [get_HeadingStyle](./get_headingstyle/)() const | Obtiene el estilo de encabezado para el documento generado. |
| [get_LineBreakStyle](./get_linebreakstyle/)() const | Obtiene el estilo de salto de línea para el documento generado. |
| [get_ResourcesDirectoryName](./get_resourcesdirectoryname/)() const | Obtiene y establece el nombre del directorio para guardar los recursos del documento, como imágenes. Si no se especifica el valor, las imágenes se escribirán en el mismo directorio que el propio archivo markdown. ¡Esto no es una ruta, es solo un nombre! Este directorio se creará automáticamente en el directorio donde se guardó el archivo markdown. |
| [get_SubscriptAndSuperscriptConversion](./get_subscriptandsuperscriptconversion/)() const | Obtiene y establece la permisividad para convertir subíndices y superíndices. Este valor es verdadero por defecto. |
| [get_UseImageHtmlTag](./get_useimagehtmltag/)() const | Obtiene y establece la permisividad para usar una etiqueta img para insertar imágenes a la izquierda y derecha del texto. En este caso, en el visor markdown, el texto se ajustará alrededor de la imagen. |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | Crea una opción de instancia para guardar un documento en formato markdown. |
| [set_AreaToExtract](./set_areatoextract/)(const System::SharedPtr\<Rectangle\>\&) | Obtenga o establezca un área rectangular para extraer contenido a markdown. |
| [set_EmphasisStyle](./set_emphasisstyle/)(Aspose::Pdf::EmphasisStyle) | Establece el estilo de énfasis para el documento generado. |
| [set_ExtractVectorGraphics](./set_extractvectorgraphics/)(bool) | Obtiene y establece una propiedad que indica si se deben extraer gráficos vectoriales. |
| [set_HeadingLevels](./set_headinglevels/)(const System::SharedPtr\<Aspose::Pdf::HeadingLevels\>\&) | Define los niveles de encabezado esperados para usar en la estrategia de reconocimiento de encabezados por tamaño de fuente. Si se establece este valor de propiedad, entonces la estrategia de reconocimiento de encabezados [HeadingRecognitionStrategy::Heuristic](../headingrecognitionstrategy/) se seleccionará cuando se configuren las estrategias [PdfToMarkdown::HeadingRecognitionStrategy::Auto](../) incluso si el documento contiene marcadores. |
| [set_HeadingRecognitionStrategy](./set_headingrecognitionstrategy/)(Aspose::Pdf::HeadingRecognitionStrategy) | Establece la estrategia de reconocimiento de encabezados. |
| [set_HeadingStyle](./set_headingstyle/)(Aspose::Pdf::HeadingStyle) | Establece el estilo de encabezado para el documento generado. |
| [set_LineBreakStyle](./set_linebreakstyle/)(Aspose::Pdf::LineBreakStyle) | Establece el estilo de salto de línea para el documento generado. |
| [set_ResourcesDirectoryName](./set_resourcesdirectoryname/)(const System::String\&) | Obtiene y establece el nombre del directorio para guardar los recursos del documento, como imágenes. Si no se especifica el valor, las imágenes se escribirán en el mismo directorio que el propio archivo markdown. ¡Esto no es una ruta, es solo un nombre! Este directorio se creará automáticamente en el directorio donde se guardó el archivo markdown. |
| [set_SubscriptAndSuperscriptConversion](./set_subscriptandsuperscriptconversion/)(bool) | Obtiene y establece la permisividad para convertir subíndices y superíndices. Este valor es verdadero por defecto. |
| [set_UseImageHtmlTag](./set_useimagehtmltag/)(bool) | Obtiene y establece la permisividad para usar una etiqueta img para insertar imágenes a la izquierda y derecha del texto. En este caso, en el visor markdown, el texto se ajustará alrededor de la imagen. |
## Ver también

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
