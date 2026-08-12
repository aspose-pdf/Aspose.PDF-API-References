---
title: "Clase Aspose::Pdf::Text::TextSegment"
linktitle: "TextSegment"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TextSegment. Representa un segmento de texto Pdf en C++."
type: docs
weight: 5100
url: /es/cpp/aspose.pdf.text/textsegment/
---
## TextSegment class


Representa un segmento de texto [Pdf](../../aspose.pdf/).

```cpp
class TextSegment : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BaselinePosition](./get_baselineposition/)() const | Obtiene la posición del texto, representado con el objeto [TextSegment](./). El YIndent de la estructura [Position](../position/) representa la coordenada de la línea base del segmento de texto. |
| [get_Characters](./get_characters/)() | Obtiene la colección de objetos [CharInfo](../charinfo/) que representan información sobre los caracteres en el segmento de texto. |
| [get_EndCharIndex](./get_endcharindex/)() const | Obtiene el índice del carácter final del segmento actual en el operador de visualización de texto (Tj, TJ). |
| [get_Hyperlink](./get_hyperlink/)() const | Obtiene el hipervínculo del segmento (para generador de pdf). |
| [get_Position](./get_position/)() const | Obtiene la posición del texto, representado con el objeto [TextSegment](./). |
| [get_Rectangle](./get_rectangle/)() | Obtiene el rectángulo del [TextSegment](./). |
| [get_StartCharIndex](./get_startcharindex/)() const | Obtiene el índice del carácter inicial del segmento actual en el operador de visualización de texto (Tj, TJ). |
| [get_Text](./get_text/)() const | Obtiene el objeto de texto [System::String](../../system/string/) que representa el objeto [TextSegment](./). |
| [get_TextEditOptions](./get_texteditoptions/)() const | Obtiene las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente. |
| [get_TextState](./get_textstate/)() const | Obtiene el estado del texto para el texto que representa el objeto [TextSegment](./). |
| static [MyHtmlEncode](./myhtmlencode/)(const System::String\&) | Codifica la cadena como html. |
| [set_BaselinePosition](./set_baselineposition/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Obtiene la posición del texto, representado con el objeto [TextSegment](./). El YIndent de la estructura [Position](../position/) representa la coordenada de la línea base del segmento de texto. |
| [set_Hyperlink](./set_hyperlink/)(const System::SharedPtr\<Aspose::Pdf::Hyperlink\>\&) | Establece el hipervínculo del segmento (para generador de pdf). |
| [set_Position](./set_position/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Obtiene la posición del texto, representado con el objeto [TextSegment](./). |
| [set_Text](./set_text/)(const System::String\&) | Establece el objeto de texto [System::String](../../system/string/) que representa el objeto [TextSegment](./). |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente. |
| [set_TextState](./set_textstate/)(const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Establece el estado del texto para el texto que representa el objeto [TextSegment](./). |
| [TextSegment](./textsegment/)() | Crea el objeto [TextSegment](./). |
| [TextSegment](./textsegment/)(const System::String\&) | Crea el objeto [TextSegment](./). |
## Observaciones


En pocas palabras, los objetos [TextSegment](./) son hijos del objeto [TextFragment](../textfragment/).

En detalle:

[Text](../) of pdf document in [Aspose::Pdf](../../aspose.pdf/) is represented by two basic objects: [TextFragment](../textfragment/) and [TextSegment](./)

Las diferencias entre ellos son mayormente dependientes del contexto.

Consideremos el siguiente escenario. El usuario busca el texto "hello world" para operar con él, cambiar sus propiedades, verlo, etc.
```cpp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```
La representación física del texto PDF es muy compleja. El texto "hello world" puede consistir en varios segmentos de texto físicamente independientes.

El modelo de texto [Aspose.Pdf](../../aspose.pdf/) básicamente establece que el objeto [TextFragment](../textfragment/) proporciona un conjunto único de operaciones lógicas sobre el conjunto de objetos [TextSegment](./) físicos que representan la consulta del usuario.

En el escenario de búsqueda de texto, [TextFragment](../textfragment/) es la representación lógica del texto "hello world", y la colección de objetos [TextSegment](./) representa todos los segmentos físicos que construyen el objeto de texto "hello world".

Así, [TextFragment](../textfragment/) se acerca a la representación lógica del texto. Y [TextSegment](./) se acerca a la representación física del texto.

Obviamente, cada objeto [TextSegment](./) puede tener su propia fuente, coloración y propiedades de posicionamiento.

[TextFragment](../textfragment/) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile [TextSegment](./) objects are accessible and users are able to operate with [TextSegment](./) objects independently. 
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
