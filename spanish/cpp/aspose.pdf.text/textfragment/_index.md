---
title: "Aspose::Pdf::Text::TextFragment clase"
linktitle: "TextFragment"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextFragment clase. Representa un fragmento de texto Pdf en C++."
type: docs
weight: 4300
url: /es/cpp/aspose.pdf.text/textfragment/
---
## TextFragment class


Representa un fragmento de texto [Pdf](../../aspose.pdf/).

```cpp
class TextFragment : public Aspose::Pdf::BaseParagraph
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clona el fragmento. |
| virtual [CloneWithSegments](./clonewithsegments/)() | Clona el fragmento con todos los segmentos. |
| [get_BaselinePosition](./get_baselineposition/)() | Obtiene la posición del texto, representado con el objeto [TextFragment](./). El YIndent de la estructura [Position](../position/) representa la coordenada de la línea base del fragmento de texto. |
| [get_EndNote](./get_endnote/)() const | Obtiene la nota final del párrafo (solo para generación de pdf). |
| [get_FootNote](./get_footnote/)() const | Obtiene la nota al pie del párrafo (solo para generación de pdf). |
| [get_Form](./get_form/)() const | Obtiene el objeto de formulario que contiene el [TextFragment](./). |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Obtiene una alineación horizontal del fragmento de texto. |
| [get_Page](./get_page/)() const | Obtiene la página que contiene el [TextFragment](./). |
| [get_Position](./get_position/)() | Obtiene la posición del texto, representado con el objeto [TextFragment](./). |
| [get_Rectangle](./get_rectangle/)() | Obtiene el rectángulo del [TextFragment](./). |
| [get_ReplaceOptions](./get_replaceoptions/)() const | Obtiene las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo. |
| [get_Segments](./get_segments/)() const | Obtiene los segmentos de texto del [TextFragment](./) actual. |
| [get_Text](./get_text/)() | Obtiene el objeto de texto [System::String](../../system/string/) que representa el objeto [TextFragment](./). |
| [get_TextEditOptions](./get_texteditoptions/)() const | Obtiene las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente. |
| [get_TextState](./get_textstate/)() | Obtiene el estado del texto para el texto que representa el objeto [TextFragment](./). |
| [get_VerticalAlignment](./get_verticalalignment/)() override | Obtiene una alineación vertical del fragmento de texto. |
| [get_WrapLinesCount](./get_wraplinescount/)() const | Obtiene el recuento de líneas de ajuste para este párrafo (solo para generación de pdf). |
| [IsolateTextSegments](./isolatetextsegments/)(int32_t, int32_t) | Obtiene [TextSegment](../textsegment/)(s) que representan la parte especificada del texto del [TextFragment](./). |
| [set_BaselinePosition](./set_baselineposition/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Obtiene la posición del texto, representado con el objeto [TextFragment](./). El YIndent de la estructura [Position](../position/) representa la coordenada de la línea base del fragmento de texto. |
| [set_EndNote](./set_endnote/)(const System::SharedPtr\<Note\>\&) | Establece la nota final del párrafo (solo para generación de pdf). |
| [set_FootNote](./set_footnote/)(const System::SharedPtr\<Note\>\&) | Establece la nota al pie del párrafo (solo para generación de pdf). |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Establece una alineación horizontal del fragmento de texto. |
| [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) override | Establece el hipervínculo del fragmento. |
| [set_Position](./set_position/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Establece la posición del texto, representado con el objeto [TextFragment](./). |
| [set_Segments](./set_segments/)(const System::SharedPtr\<TextSegmentCollection\>\&) | Obtiene los segmentos de texto del [TextFragment](./) actual. |
| [set_Text](./set_text/)(const System::String\&) | Establece el objeto de texto [System::String](../../system/string/) que representa el objeto [TextFragment](./). |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) override | Establece una alineación vertical del fragmento de texto. |
| [set_WrapLinesCount](./set_wraplinescount/)(int32_t) | Establece la cantidad de líneas de ajuste para este párrafo (solo para generación de PDF). |
| [TextFragment](./textfragment/)() | Inicializa una nueva instancia del objeto [TextFragment](./). |
| [TextFragment](./textfragment/)(const System::SharedPtr\<TabStops\>\&) | Inicializa una nueva instancia del objeto [TextFragment](./) con posiciones predefinidas de [TabStops](../tabstops/). |
| [TextFragment](./textfragment/)(const System::String\&) | Crea un objeto [TextFragment](./) con un único objeto [TextSegment](../textsegment/) dentro. Especifica la cadena de texto dentro del segmento. |
| [TextFragment](./textfragment/)(const System::String\&, const System::SharedPtr\<TabStops\>\&) | Crea un objeto [TextFragment](./) con un único objeto [TextSegment](../textsegment/) dentro y posiciones predefinidas de [TabStops](../tabstops/). |
## Observaciones


En pocas palabras, el objeto [TextFragment](./) contiene una lista de objetos [TextSegment](../textsegment/).

En detalle: el [Text](../) del documento PDF en [Aspose::Pdf](../../aspose.pdf/) está representado por dos objetos básicos: [TextFragment](./) y [TextSegment](../textsegment/).

Las diferencias entre ellos son mayormente dependientes del contexto.

Consideremos el siguiente escenario. El usuario busca el texto "hello world" para operar con él, cambiar sus propiedades, verlo, etc.
```cpp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```
La representación física del texto PDF es muy compleja. El texto "hello world" puede consistir en varios segmentos de texto físicamente independientes.

El modelo de texto de [Aspose.Pdf](../../aspose.pdf/) establece básicamente que el objeto [TextFragment](./) proporciona un conjunto de operaciones lógicas sobre el conjunto de objetos [TextSegment](../textsegment/) físicos que representan la consulta del usuario.

En el escenario de búsqueda de texto, [TextFragment](./) es la representación lógica del texto "hello world", y la colección de objetos [TextSegment](../textsegment/) representa todos los segmentos físicos que construyen el objeto de texto "hello world".

Así, [TextFragment](./) se acerca a la representación lógica del texto. Y [TextSegment](../textsegment/) se acerca a la representación física del texto.

Obviamente, cada objeto [TextSegment](../textsegment/) puede tener su propia fuente, coloración y propiedades de posicionamiento.

[TextFragment](./) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile [TextSegment](../textsegment/) objects are accessible and users are able to operate with [TextSegment](../textsegment/) objects independently.

[Note](../../aspose.pdf/note/) that changing [TextFragment](./) properties may change inner [Segments](../) collection because [TextFragment](./) is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the [Segments](../) collection unchanged, please change inner segments individually. 
## Ver también

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
