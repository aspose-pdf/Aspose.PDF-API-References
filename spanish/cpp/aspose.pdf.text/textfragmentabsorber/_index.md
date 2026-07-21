---
title: "Clase Aspose::Pdf::Text::TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TextFragmentAbsorber. Representa un objeto absorbente de fragmentos de texto. Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda a través de la colección TextFragmentAbsorber::TextFragments en C++."
type: docs
weight: 4400
url: /es/cpp/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class


Representa un objeto absorbente de fragmentos de texto. Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda mediante la colección [TextFragmentAbsorber::TextFragments](../).

```cpp
class TextFragmentAbsorber : public Aspose::Pdf::Text::TextAbsorber
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ApplyForAllFragments](./applyforallfragments/)(const System::SharedPtr\<Font\>\&) | Aplica la fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos de la(s) página(s) fueron absorbidos. De lo contrario, funciona de manera similar a la iteración. |
| [ApplyForAllFragments](./applyforallfragments/)(float) | Aplica el tamaño de fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos de la(s) página(s) fueron absorbidos. De lo contrario, funciona de manera similar a la iteración. |
| [ApplyForAllFragments](./applyforallfragments/)(const System::SharedPtr\<Font\>\&, float) | Aplica la fuente y el tamaño a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos de la(s) página(s) fueron absorbidos. De lo contrario, funciona de manera similar a la iteración. |
| [get_Errors](./get_errors/)() | Lista de objetos [TextExtractionError](../textextractionerror/). Contiene información sobre los errores encontrados durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| [get_ExtractionOptions](./get_extractionoptions/)() override | Obtiene las opciones de extracción de texto. |
| [get_HasErrors](./get_haserrors/)() | El valor indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| [get_Phrase](./get_phrase/)() const | Obtiene la frase que el [TextFragmentAbsorber](./) busca en el documento o página PDF. |
| [get_RegexResults](./get_regexresults/)() const | Obtiene el diccionario de ocurrencias de búsqueda que se presentan con la clase [System.Text.RegularExpressions.Regex](../../system.text.regularexpressions/regex/) como clave y [TextFragment](../textfragment/) como valor. |
| [get_Text](./get_text/)() override | Obtiene el texto extraído que el [TextAbsorber](../textabsorber/) extrae del documento o página PDF. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Obtiene las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente. |
| [get_TextFragments](./get_textfragments/)() | Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos [TextFragment](../textfragment/). |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Obtiene las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo. |
| [get_TextSearchOptions](./get_textsearchoptions/)() override | Obtiene las opciones de búsqueda. Las opciones permiten buscar usando expresiones regulares. |
| [RemoveAllText](./removealltext/)(const System::SharedPtr\<Page\>\&) | Elimina todo el texto de la página especificada. |
| [RemoveAllText](./removealltext/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Elimina el texto dentro del rectángulo especificado de la página indicada. |
| [RemoveAllText](./removealltext/)(const System::SharedPtr\<Document\>\&) | Elimina todo el texto del documento. |
| [Reset](./reset/)() | Limpia la colección TextFragments de este objeto [TextFragmentAbsorber](./). |
| [set_ExtractionOptions](./set_extractionoptions/)(System::SharedPtr\<TextExtractionOptions\>) override | Establece las opciones de extracción de texto. |
| [set_Phrase](./set_phrase/)(const System::String\&) | Establece la frase que el [TextFragmentAbsorber](./) busca en el documento PDF o página. |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente. |
| [set_TextFragments](./set_textfragments/)(const System::SharedPtr\<TextFragmentCollection\>\&) | Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos [TextFragment](../textfragment/). |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>\&) | Establece las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo. |
| [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) override | Establece las opciones de búsqueda. Las opciones permiten buscar usando expresiones regulares. |
| [TextFragmentAbsorber](./textfragmentabsorber/)() | Inicializa una nueva instancia de [TextFragmentAbsorber](./) que realiza la búsqueda de todos los segmentos de texto del documento o página. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Inicializa una nueva instancia de [TextFragmentAbsorber](./) con opciones de edición de texto, que realiza la búsqueda de todos los segmentos de texto del documento o página. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&) | Inicializa una nueva instancia de la clase [TextFragmentAbsorber](./) para la frase de texto especificada. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&) | Inicializa una nueva instancia de la clase [TextFragmentAbsorber](./) para el objeto de clase [System.Text.RegularExpressions.Regex](../../system.text.regularexpressions/regex/) especificado. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Inicializa una nueva instancia de la clase [TextFragmentAbsorber](./) para la frase de texto especificada y las opciones de búsqueda de texto. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Inicializa una nueva instancia de la clase [TextFragmentAbsorber](./) para la frase de texto especificada y las opciones de búsqueda de texto. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Inicializa una nueva instancia de la clase [TextFragmentAbsorber](./) para la frase de texto especificada y las opciones de búsqueda de texto. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Inicializa una nueva instancia de la clase [TextFragmentAbsorber](./) para la frase de texto especificada, las opciones de búsqueda de texto y las opciones de edición de texto. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Inicializa una nueva instancia de la clase [TextFragmentAbsorber](./) para la frase de texto especificada y las opciones de edición de texto. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Inicializa una nueva instancia de la clase [TextFragmentAbsorber](./) para la frase de texto especificada y las opciones de edición de texto. |
| [Visit](./visit/)(System::SharedPtr\<Page\>) override | Realiza la búsqueda en la página especificada. |
| [Visit](./visit/)(System::SharedPtr\<Document\>) override | Realiza la búsqueda en el documento especificado. |
| [Visit](./visit/)(System::SharedPtr\<XForm\>) override | Realiza la búsqueda en el objeto de formulario especificado. |
## Observaciones


El objeto [TextFragmentAbsorber](./) se utiliza básicamente en escenarios de búsqueda de texto. Cuando la búsqueda se completa, las ocurrencias se representan con objetos [TextFragment](../textfragment/) que contiene la colección [TextFragmentAbsorber::TextFragments](../). El objeto [TextFragment](../textfragment/) proporciona acceso al texto de la ocurrencia de búsqueda, a sus propiedades de texto, y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc).
## Ver también

* Class [TextAbsorber](../textabsorber/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
