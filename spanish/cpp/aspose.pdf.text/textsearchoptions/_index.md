---
title: "Aspose::Pdf::Text::TextSearchOptions clase"
linktitle: "TextSearchOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::TextSearchOptions clase. Representa opciones de búsqueda de texto en C++."
type: docs
weight: 5000
url: /es/cpp/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class


Representa opciones de búsqueda de texto.

```cpp
class TextSearchOptions : public Aspose::Pdf::Text::TextOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Obtiene la indicación de que los errores relacionados con la ausencia de fuentes serán ignorados por el absorbente de texto (fragmento). true - indica que los errores de ausencia de fuentes serán ignorados. Los segmentos [Text](../) que hacen referencia a recursos incorrectos se omitirán durante el procesamiento. false (por defecto) - el error de ausencia de fuente terminará el procesamiento lanzando una excepción. |
| [get_IgnoreShadowText](./get_ignoreshadowtext/)() const | Obtiene la indicación de que los fragmentos de texto que representan la sombra del texto normal serán ignorados durante la búsqueda. true - indica que el texto en sombra no será encontrado (pruebe esto si la búsqueda de texto devuelve fragmentos duplicados en posiciones cercanas). false - indica que el texto en sombra será encontrado junto con el texto normal (valor por defecto). |
| [get_IsRegularExpressionUsed](./get_isregularexpressionused/)() const | Obtiene la indicación de que se utiliza expresión regular. |
| [get_LimitToPageBounds](./get_limittopagebounds/)() const | Obtiene la indicación de que el texto se busca dentro de los límites de la página. |
| [get_LogTextExtractionErrors](./get_logtextextractionerrors/)() const | Obtiene la indicación de que los errores de extracción de texto (decodificación) se registrarán en el absorbente de texto (fragmento). true - indica que los errores de extracción de texto (decodificación) se registrarán. Puede disminuir el rendimiento. false (por defecto) - no se registran errores. |
| [get_Rectangle](./get_rectangle/)() const | Obtiene el rectángulo que delimita el texto buscado. |
| [get_SearchForTextRelatedGraphics](./get_searchfortextrelatedgraphics/)() const | Obtiene el valor que permite buscar gráficos relacionados con el texto (subrayado, fondo, etc.) durante la búsqueda de texto. true - la búsqueda de gráficos relacionados con el texto se realizará (valor por defecto). false - los elementos gráficos que puedan estar presentes en el documento fuente serán ignorados. Configure esto en caso de problemas de rendimiento o si no necesita manejar subrayado, fondo o recorte. |
| [get_SearchInAnnotations](./get_searchinannotations/)() const | Obtiene el valor que permite buscar texto en [Annotations](../../aspose.pdf.annotations/). true - el texto se buscará en [Annotations](../../aspose.pdf.annotations/). false - el texto en [Annotations](../../aspose.pdf.annotations/) no será analizado por [TextFragmentAbsorber](../textfragmentabsorber/). |
| [get_StoredGraphicElementsMaxCount](./get_storedgraphicelementsmaxcount/)() const | Obtiene el valor que limita la búsqueda de gráficos relacionados con el texto (subrayado, fondo, etc.) en una página al número especificado de elementos. El valor predeterminado es 250. Establezca un valor menor en caso de problemas de rendimiento, pruebe un valor mayor si algunos elementos gráficos no se encuentran. |
| [get_UseFontEngineEncoding](./get_usefontengineencoding/)() const | Obtiene la indicación de que el texto se buscará usando la codificación del motor de fuentes. true - indica que se utilizará la codificación del motor de fuentes (pruebe esto si la búsqueda de texto falla debido a una codificación imperfecta en el documento). false - indica que se utilizará la codificación de fuentes del documento (valor por defecto). |
| [set_IgnoreResourceFontErrors](./set_ignoreresourcefonterrors/)(bool) | Establece la indicación de que los errores relacionados con la ausencia de fuente serán ignorados por el absorbente de texto (fragmento). true - indica que los errores de ausencia de fuente serán ignorados. Los segmentos [Text](../) que hacen referencia a recursos incorrectos se omitirán durante el procesamiento. false (por defecto) - el error de ausencia de fuente terminará el procesamiento lanzando una excepción. |
| [set_IgnoreShadowText](./set_ignoreshadowtext/)(bool) | Establece la indicación de que los fragmentos de texto que representan la sombra del texto normal serán ignorados durante la búsqueda. true - indica que el texto en sombra no se encontrará (pruebe esto si la búsqueda de texto devuelve fragmentos duplicados en posiciones cercanas). false - indica que el texto en sombra se encontrará junto con el texto normal (valor por defecto). |
| [set_IsRegularExpressionUsed](./set_isregularexpressionused/)(bool) | Establece la indicación de que se utiliza una expresión regular. |
| [set_LimitToPageBounds](./set_limittopagebounds/)(bool) | Establece la indicación de que el texto se busca dentro de los límites de la página. |
| [set_LogTextExtractionErrors](./set_logtextextractionerrors/)(bool) | Establece la indicación de que los errores de extracción de texto (decodificación) se registrarán en el absorbente de texto (fragmento). true - indica que los errores de extracción de texto (decodificación) se registrarán. Puede disminuir el rendimiento. false (por defecto) - sin registro de errores. |
| [set_Rectangle](./set_rectangle/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece el rectángulo que delimita el texto buscado. |
| [set_SearchForTextRelatedGraphics](./set_searchfortextrelatedgraphics/)(bool) | Establece el valor que permite buscar gráficos relacionados con el texto (subrayado, fondo, etc.) durante la búsqueda de texto. true - la búsqueda de gráficos relacionados con el texto se realizará (valor por defecto). false - los elementos gráficos que puedan estar presentes en el documento fuente se ignorarán. Configure esto en caso de problemas de rendimiento o si no es necesario manejar subrayado, fondo o recorte. |
| [set_SearchInAnnotations](./set_searchinannotations/)(bool) | Establece el valor que permite buscar texto en [Annotations](../../aspose.pdf.annotations/). true - el texto se buscará en [Annotations](../../aspose.pdf.annotations/). false - el texto en [Annotations](../../aspose.pdf.annotations/) no será analizado por [TextFragmentAbsorber](../textfragmentabsorber/). |
| [set_StoredGraphicElementsMaxCount](./set_storedgraphicelementsmaxcount/)(int32_t) | Establece el valor que limita la búsqueda de gráficos relacionados con el texto (subrayado, fondo, etc.) en una página al número especificado de elementos. El valor por defecto es 250. Use un valor menor en caso de problemas de rendimiento, pruebe un valor mayor si algunos elementos gráficos no se encuentran. |
| [set_UseFontEngineEncoding](./set_usefontengineencoding/)(bool) | Establece la indicación de que el texto se buscará utilizando la codificación del motor de fuentes. true - indica que se usará la codificación del motor de fuentes (pruebe esto si la búsqueda de texto falla debido a una codificación imperfecta en el documento). false - indica que se usará la codificación de fuentes del documento (valor por defecto). |
| [TextSearchOptions](./textsearchoptions/)(bool) | Inicializa una nueva instancia del objeto [TextSearchOptions](./). Especifica el modo de uso de expresiones regulares. |
| [TextSearchOptions](./textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Inicializa una nueva instancia del objeto [TextSearchOptions](./). Especifica el rectángulo que delimita el texto buscado. |
| [TextSearchOptions](./textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, bool) | Inicializa una nueva instancia del objeto [TextSearchOptions](./). Especifica el rectángulo que delimita el texto buscado y el modo de uso de expresiones regulares. |
## Ver también

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
