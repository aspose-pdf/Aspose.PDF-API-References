---
title: "ParagraphAbsorber"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un objeto absorbente de objetos de estructura de página como secciones y párrafos.<br/>            Realiza búsquedas de secciones y párrafos de texto y proporciona acceso a rectángulos y polígonos que lo describen en el espacio de coordenadas del texto. <br/>            También realiza búsquedas de segmentos de texto y proporciona acceso a los resultados de búsqueda mediante colecciones de TextFragments agrupadas por elementos de estructura."
type: docs
weight: 240
url: /es/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

Representa un objeto absorbente de objetos de estructura de página como secciones y párrafos.<br/>            Realiza búsquedas de secciones y párrafos de texto y proporciona acceso a rectángulos y polígonos que lo describen en el espacio de coordenadas del texto. <br/>            También realiza búsquedas de segmentos de texto y proporciona acceso a los resultados de búsqueda mediante colecciones de TextFragments agrupadas por elementos de estructura.

El tipo ParagraphAbsorber expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| ParagraphAbsorber() | Inicializa una nueva instancia de [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) que realiza la búsqueda de secciones/párrafos del documento o página. |
| ParagraphAbsorber(sections_search_depth) | Inicializa una nueva instancia de la clase ParagraphAbsorber |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| page_markups | Obtiene la colección de [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) que fueron absorbidos. |
| sections_search_depth | Obtiene o establece el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos más finos de la estructura.<br/>            La profundidad de búsqueda predeterminada es 3.<br/>            Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas). |
| is_multicolumn_paragraphs_allowed | Obtiene o establece el valor que indica si las líneas de texto iniciales de una sección siguiente pueden tratarse como continuación del último párrafo de una sección anterior. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| visit(doc) | Realiza la búsqueda de secciones y párrafos en el [Document](/pdf/python-net/aspose.pdf/document/) especificado. |
| visit(page) | Realiza una búsqueda en la [Page](/pdf/python-net/aspose.pdf/page/) especificada. |

### Ver también

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

