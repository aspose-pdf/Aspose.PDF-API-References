---
title: "Clase Aspose::Pdf::Text::TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TextAbsorber. Representa un objeto absorbente de texto. Realiza la extracción de texto y proporciona acceso al resultado a través del objeto TextAbsorber::Text en C++."
type: docs
weight: 3600
url: /es/cpp/aspose.pdf.text/textabsorber/
---
## TextAbsorber class


Representa un objeto absorbente de texto. Realiza la extracción de texto y proporciona acceso al resultado mediante el objeto [TextAbsorber::Text](../).

```cpp
class TextAbsorber : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Errors](./get_errors/)() const | Lista de objetos [TextExtractionError](../textextractionerror/). Contiene información sobre los errores encontrados durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| virtual [get_ExtractionOptions](./get_extractionoptions/)() | Obtiene las opciones de extracción de texto. |
| [get_HasErrors](./get_haserrors/)() const | El valor indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| virtual [get_Text](./get_text/)() | Obtiene el texto extraído que el [TextAbsorber](./) extrae del documento PDF o de la página. |
| virtual [get_TextSearchOptions](./get_textsearchoptions/)() | Obtiene opciones de búsqueda de texto. |
| virtual [set_ExtractionOptions](./set_extractionoptions/)(System::SharedPtr\<TextExtractionOptions\>) | Establece las opciones de extracción de texto. |
| virtual [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Establece opciones de búsqueda de texto. |
| [TextAbsorber](./textabsorber/)() | Inicializa una nueva instancia de [TextAbsorber](./). |
| [TextAbsorber](./textabsorber/)(const System::SharedPtr\<TextExtractionOptions\>\&) | Inicializa una nueva instancia de [TextAbsorber](./) con opciones de extracción. |
| [TextAbsorber](./textabsorber/)(const System::SharedPtr\<TextExtractionOptions\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Inicializa una nueva instancia de [TextAbsorber](./) con opciones de extracción y búsqueda de texto. |
| [TextAbsorber](./textabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Inicializa una nueva instancia de [TextAbsorber](./) con opciones de búsqueda de texto. |
| virtual [Visit](./visit/)(System::SharedPtr\<Page\>) | Extrae texto en la página especificada. |
| virtual [Visit](./visit/)(System::SharedPtr\<XForm\>) | Extrae texto en el [XForm](../../aspose.pdf/xform/) especificado. |
| virtual [Visit](./visit/)(System::SharedPtr\<Document\>) | Extrae texto en el documento especificado. |
## Observaciones


El objeto [TextAbsorber](./) se usa para extraer texto de un documento [Pdf](../../aspose.pdf/) o de la página del documento.
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
