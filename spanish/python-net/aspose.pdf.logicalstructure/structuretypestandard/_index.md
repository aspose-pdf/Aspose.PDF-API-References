---
title: "StructureTypeStandard"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa Standard Structure Types."
type: docs
weight: 560
url: /es/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

Representa Standard Structure Types.

El tipo StructureTypeStandard expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| tag | Obtiene el nombre de la etiqueta de [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/). |
| categoría | Obtiene la categoría del Standard Structure Type. |
| DOCUMENTO | (Document) Un documento completo. Este es el elemento raíz de cualquier árbol estructural que contiene múltiples partes o múltiples artículos. |
| PART | (Part) Una división a gran escala de un documento. Este tipo de elemento es apropiado para agrupar artículos o secciones. |
| ART | (Article) Un cuerpo de texto relativamente autónomo que constituye una única narrativa o exposición. Los artículos deben ser disjuntos; es decir, no deben contener otros artículos como elementos constituyentes. |
| SECT | (Section) Un contenedor para agrupar elementos de contenido relacionados. |
| DIV | (Division) Un elemento genérico a nivel de bloque o un grupo de elementos. |
| BLOCK_QUOTE | (Block quotation) Una porción de texto que consiste en uno o más párrafos atribuidos a alguien distinto del autor del texto circundante. |
| CAPTION | (Caption) Una breve porción de texto que describe una tabla o figura. |
| TOC | (Table of contents) Una lista compuesta por entradas de elementos del índice (tipo de estructura TOCI) y/o otras entradas de índice anidadas (TOC). |
| TOCI | (Table of contents item) Un miembro individual de un índice. Los hijos de esta entrada pueden ser cualquiera de los siguientes tipos de estructura: |
| INDEX | (Index) Una secuencia de entradas que contienen texto identificador acompañado de elementos de referencia que señalan ocurrencias del texto especificado en el cuerpo principal de un documento. |
| NON_STRUCT | (Nonstructural element) Un elemento de agrupación que no tiene una importancia estructural inherente; sirve únicamente con propósitos de agrupación. Este tipo de elemento difiere de una división (tipo de estructura Div) en que no debe interpretarse ni exportarse a otros formatos de documento; sin embargo, sus descendientes deben procesarse normalmente. |
| PRIVATE | (Private element) Un elemento de agrupación que contiene contenido privado perteneciente a la aplicación que lo produce. La importancia estructural de este tipo de elemento no está especificada y debe ser determinada íntegramente por el autor conforme. Ni el elemento Private ni ninguno de sus descendientes deben interpretarse o exportarse a otros formatos de documento. |
| P | (Paragraph) Una división de bajo nivel del texto. |
| H | (Heading) Una etiqueta para una subdivisión del contenido de un documento. Debe ser el primer hijo de la división que encabeza. |
| H1 | Encabezado de nivel 1, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| H2 | Encabezado de nivel 2, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| H3 | Encabezado de nivel 3, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| H4 | Encabezado de nivel 4, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| H5 | Encabezado de nivel 5, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| H6 | Encabezado de nivel 6, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| L | (List) Una secuencia de elementos con significado e importancia similares. Sus hijos inmediatos deben ser una leyenda opcional (structure type Caption) seguida de uno o más elementos de lista (structure type LI). |
| LI | (List item) Un miembro individual de una lista. Sus hijos pueden ser una o más etiquetas, cuerpos de lista, o ambos (structure types Lbl o LBody). |
| LBL | (Label) Un nombre o número que distingue un elemento dado de los demás en la misma lista u otro grupo de elementos similares. |
| L_BODY | (List body) El contenido descriptivo de un elemento de lista. En una lista de diccionario, por ejemplo, contiene la definición del término. Puede contener el contenido directamente o tener otros BLSEs, quizás incluyendo listas anidadas, como hijos. |
| TABLE | (Table) Un diseño bidimensional de celdas de datos rectangulares, que posiblemente tenga una subestructura compleja. Contiene una o más filas de tabla (structure type TR) como hijos; o una cabecera de tabla opcional (structure type THead) seguida de uno o más elementos del cuerpo de tabla (structure type TBody) y un pie de tabla opcional (structure type TFoot). Además, una tabla puede tener una leyenda (structure type Caption) como su primer o último hijo. |
| T_HEAD | (Table header row group; PDF 1.5) Un grupo de filas que constituyen la cabecera de una tabla. Si la tabla se divide en varias páginas, estas filas pueden volver a dibujarse en la parte superior de cada fragmento de tabla (aunque solo haya un elemento THead). |
| T_BODY | (Table body row group; PDF 1.5) Un grupo de filas que constituyen la porción principal del cuerpo de una tabla. Si la tabla se divide en varias páginas, el área del cuerpo puede separarse en un límite de fila. Una tabla puede tener múltiples elementos TBody para permitir el dibujo de un borde o fondo para un conjunto de filas. |
| T_FOOT | (Table footer row group; PDF 1.5) Un grupo de filas que constituyen el pie de una tabla. Si la tabla se divide en varias páginas, estas filas pueden volver a dibujarse al final de cada fragmento de tabla (aunque solo exista un elemento TFoot.) |
| TR | (Table row) Una fila de encabezados o datos en una tabla. Puede contener celdas de encabezado de tabla y celdas de datos de tabla (tipos de estructura TH y TD). |
| TH | (Table header cell) Una celda de tabla que contiene texto de encabezado que describe una o más filas o columnas de la tabla. |
| TD | (Table data cell) Una celda de tabla que contiene datos que forman parte del contenido de la tabla. |
| SPAN | (Span) Una porción genérica en línea de texto sin características inherentes particulares. Puede usarse, por ejemplo, para delimitar un rango de texto con un conjunto dado de atributos de estilo. |
| QUOTE | (Quotation) Una porción en línea de texto atribuida a alguien distinto del autor del texto circundante. |
| NOTA | (Note) Un elemento de texto explicativo, como una nota al pie o una nota final, que se menciona desde el cuerpo del documento. Puede tener una etiqueta (tipo de estructura Lbl) como hijo. La nota puede incluirse como hijo del elemento de estructura en el texto del cuerpo que la referencia, o puede incluirse en otro lugar (como en una sección de notas finales) y accederse mediante una referencia (tipo de estructura Reference). |
| REFERENCE | (Reference) Una cita a contenido en otra parte del documento. |
| BIB_ENTRY | (Bibliography entry) Una referencia que identifica la fuente externa de algún contenido citado. Puede contener una etiqueta (tipo de estructura Lbl) como hijo. |
| CODE | (Code) Un fragmento de texto de programa informático. |
| LINK | (Link) Una asociación entre una porción del contenido de ILSE y una anotación de enlace correspondiente o anotaciones. Sus hijos deben ser uno o más elementos de contenido o ILSEs hijos y una o más referencias de objeto que identifiquen las anotaciones de enlace asociadas. |
| ANNOT | (Annotation; PDF 1.5) Una asociación entre una porción del contenido de ILSE y una anotación PDF correspondiente. Annot se usará para todas las anotaciones PDF excepto anotaciones de enlace y anotaciones de widget. |
| RUBY | (Ruby; PDF 1.5) Una nota al margen (anotación) escrita en un tamaño de texto más pequeño y colocada adyacente al texto base al que se refiere. Un elemento Ruby también puede contener los elementos RB, RT y RP. |
| RB | (Ruby base text) El texto de tamaño completo al que se aplica la anotación ruby. RB puede contener texto, otros elementos en línea o una mezcla de ambos. Puede tener el atributo RubyAlignattribute. |
| RT | (Ruby annotation text) El texto de tamaño más pequeño que se colocará adyacente al texto base ruby. Puede contener texto, otros elementos en línea o una mezcla de ambos. Puede tener los atributos RubyAlign y RubyPosition. |
| RP | (Ruby punctuation) Puntuación que rodea el texto de la anotación ruby. Se usa solo cuando una anotación ruby no puede formatearse correctamente en estilo ruby y en su lugar se formatea como un comentario normal, o cuando se formatea como un warichu. Contiene texto (normalmente un SINGLE LEFT o RIGHT PARENTHESIS o un carácter de corchete similar). |
| WARICHU | (Warichu; PDF 1.5) Un comentario o anotación en un tamaño de texto más pequeño y formateado en dos líneas más pequeñas dentro de la altura de la línea de texto contenedora y colocado después (en línea) del texto base al que se refiere. Un elemento Warichu también puede contener los elementos WT y WP. |
| WT | (Warichu text) El texto de tamaño más pequeño de un comentario warichu que se formatea en dos líneas y se coloca entre los elementos WP circundantes. |
| WP | (Warichu punctuation) La puntuación que rodea el texto WT. Contiene texto (normalmente un SINGLE LEFT o RIGHT PARENTHESIS o un carácter de corchete similar). Según JIS X 4051-1995, los paréntesis que rodean un warichu pueden convertirse en un ESPACIO (nominalmente 1/4 EM de ancho) a discreción del formateador. |
| FIGURE | (Figure) Un elemento de contenido gráfico. Su ubicación puede especificarse con el atributo de diseño Placement. |
| FORMULA | (Formula) Una fórmula matemática. |
| FORM | (Form) Una anotación de widget que representa un campo de formulario interactivo. |

### Ver también

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

