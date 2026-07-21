---
title: "Aspose::Pdf::Text::ParagraphAbsorber clase"
linktitle: "ParagraphAbsorber"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::ParagraphAbsorber clase. Representa un objeto absorbente de objetos de estructura de página como secciones y párrafos. Realiza búsquedas de secciones y párrafos de texto y proporciona acceso a rectángulos y polígonos que los describen en el espacio de coordenadas del texto. También realiza búsquedas de segmentos de texto y proporciona acceso a los resultados de búsqueda mediante colecciones de TextFragments agrupadas por elementos de estructura en C++."
type: docs
weight: 2600
url: /es/cpp/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class


Representa un objeto absorbente de objetos de estructura de página, como secciones y párrafos. Realiza búsquedas de secciones y párrafos de texto y proporciona acceso a rectángulos y polígonos que lo describen en el espacio de coordenadas del texto. También realiza búsquedas de segmentos de texto y proporciona acceso a los resultados de búsqueda mediante colecciones de [TextFragments](../) agrupadas por elementos de estructura.

```cpp
class ParagraphAbsorber : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_IsMulticolumnParagraphsAllowed](./get_ismulticolumnparagraphsallowed/)() const | Obtiene el valor que indica si las líneas de texto iniciales de una sección siguiente pueden tratarse como continuación del último párrafo de una sección anterior. |
| [get_PageMarkups](./get_pagemarkups/)() const | Obtiene la colección de [PageMarkup](../pagemarkup/) que fueron absorbidos. |
| [get_ParagraphAbsorberOptions](./get_paragraphabsorberoptions/)() const | Obtiene el [ParagraphAbsorberOptions](../paragraphabsorberoptions/). |
| [get_SectionsSearchDepth](./get_sectionssearchdepth/)() const | Obtiene el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos de estructura más finos. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas). |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Obtiene el [TextReplaceOptions](../textreplaceoptions/). |
| [ParagraphAbsorber](./paragraphabsorber/)() | Inicializa una nueva instancia de [ParagraphAbsorber](./) que realiza búsquedas de secciones/párrafos del documento o página. |
| [ParagraphAbsorber](./paragraphabsorber/)(int32_t) | Inicializa una nueva instancia de [ParagraphAbsorber](./) que realiza búsquedas de secciones/párrafos del documento o página. |
| [ParagraphAbsorber](./paragraphabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>\&) | Inicializa una nueva instancia de [ParagraphAbsorber](./) que realiza búsquedas de secciones/párrafos del documento o página con los parámetros especificados. |
| [ParagraphAbsorber](./paragraphabsorber/)(int32_t, const System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>\&) | Inicializa una nueva instancia de [ParagraphAbsorber](./) que realiza búsquedas de secciones/párrafos del documento o página con los parámetros especificados. |
| [set_IsMulticolumnParagraphsAllowed](./set_ismulticolumnparagraphsallowed/)(bool) | Establece el valor que indica si las líneas de texto iniciales de una sección siguiente pueden tratarse como continuación del último párrafo de una sección anterior. |
| [set_ParagraphAbsorberOptions](./set_paragraphabsorberoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>\&) | Establece el [ParagraphAbsorberOptions](../paragraphabsorberoptions/). |
| [set_SectionsSearchDepth](./set_sectionssearchdepth/)(int32_t) | Establece el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos de estructura más finos. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas). |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>\&) | Establece el [TextReplaceOptions](../textreplaceoptions/). |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Realiza una búsqueda de secciones y párrafos en el [Document](../../aspose.pdf/document/) especificado. |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Realiza una búsqueda en la [Page](../../aspose.pdf/page/) especificada. |
## Observaciones


Cuando la búsqueda se complete, la colección [ParagraphAbsorber::PageMarkups](../) contendrá objetos [PageMarkup](../pagemarkup/) que representan la estructura de la página mediante colecciones de [MarkupSection](../markupsection/) y [MarkupParagraph](../markupparagraph/). El objeto [TextFragment](../textfragment/) proporciona acceso al texto de la ocurrencia de búsqueda, a sus propiedades y permite editar el texto y cambiar su estado (fuente, tamaño de fuente, color, etc.).
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
