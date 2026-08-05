---
title: "TextAbsorber"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un objeto absorbente de texto.<br/>            Realiza la extracción de texto y proporciona acceso al resultado mediante el objeto [text](/pdf/python-net/aspose.pdf.text/textabsorber/)."
type: docs
weight: 320
url: /es/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

Representa un objeto absorbente de texto.<br/>            Realiza la extracción de texto y proporciona acceso al resultado mediante el objeto [text](/pdf/python-net/aspose.pdf.text/textabsorber/).

El tipo TextAbsorber expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| TextAbsorber() | Inicializa una nueva instancia de [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/). |
| TextAbsorber(extraction_options) | Inicializa una nueva instancia de la clase TextAbsorber |
| TextAbsorber(extraction_options, text_search_options) | Inicializa una nueva instancia de la clase TextAbsorber |
| TextAbsorber(text_search_options) | Inicializa una nueva instancia de la clase TextAbsorber |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| text | Obtiene el texto extraído que el [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extrae del documento PDF o página. |
| has_errors | El valor indica si se encontraron errores durante la extracción de texto.<br/>            La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| errors | Lista de objetos [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Contiene información sobre los errores encontrados durante la extracción de texto.<br/>            La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| extraction_options | Obtiene o establece las opciones de extracción de texto. |
| text_search_options | Obtiene o establece las opciones de búsqueda de texto. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| visit(page) | Extrae texto en la página especificada |
| visit(form) | Extrae texto en el XForm especificado. |
| visit(pdf) | Extrae texto en el documento especificado |

### Ver también

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

