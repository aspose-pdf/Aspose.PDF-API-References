---
title: "Aspose::Pdf::LogicalStructure::StructureTypeStandard class"
linktitle: "StructureTypeStandard"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LogicalStructure::StructureTypeStandard class. Representa los tipos de estructura estándar en C++."
type: docs
weight: 5900
url: /es/cpp/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class


Representa los tipos estándar de [Structure](../../aspose.pdf.structure/).

```cpp
class StructureTypeStandard : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Category](./get_category/)() const | Obtiene la categoría del tipo estándar de [Structure](../../aspose.pdf.structure/). |
| [get_Tag](./get_tag/)() const | Obtiene el nombre de etiqueta de [Aspose::Pdf::LogicalStructure::StructureElement](../structureelement/). |
| static [to_StructureTypeStandard](./to_structuretypestandard/)(const System::String\&) | Realiza una conversión explícita de [System::String](../../system/string/) a [Aspose::Pdf::LogicalStructure::StructureTypeStandard](./). |
| [ToString](./tostring/)() const override | Devuelve una cadena que representa el objeto actual. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Annot](./annot/) | (Annotation; PDF 1.5) Una asociación entre una parte del contenido del ILSE y una anotación PDF correspondiente. Annot se utilizará para todas las anotaciones PDF, excepto las anotaciones de enlace y las anotaciones de widget. |
| static [Art](./art/) | (Article) Un cuerpo de texto relativamente autónomo que constituye una única narrativa o exposición. Los artículos deben ser disjuntos; es decir, no deben contener otros artículos como elementos constituyentes. |
| static [BibEntry](./bibentry/) |  |
| static [BlockQuote](./blockquote/) | (Block quotation) Una porción de texto que consta de uno o más párrafos atribuidos a alguien distinto del autor del texto circundante. |
| static [Caption](./caption/) | (Caption) Una breve porción de texto que describe una tabla o figura. |
| static [Code](./code/) | (Code) Un fragmento de texto de programa informático. |
| static [Div](./div/) | (Division) Un elemento genérico a nivel de bloque o un grupo de elementos. |
| static [Document](./document/) | ([Document](../../aspose.pdf/document/)) Un documento completo. Este es el elemento raíz de cualquier árbol estructural que contenga múltiples partes o múltiples artículos. |
| static [Figure](./figure/) | (Figure) Un elemento de contenido gráfico. Su ubicación puede especificarse con el atributo de diseño Placement. |
| static [Form](./form/) | (Form) Una anotación de widget que representa un campo de formulario interactivo. |
| static [Formula](./formula/) |  |
| static [H](./h/) | ([Heading](../../aspose.pdf/heading/)) Una etiqueta para una subdivisión del contenido de un documento. Debe ser el primer hijo de la división que encabeza. |
| static [H1](./h1/) | Nivel 1 [Heading](../../aspose.pdf/heading/), para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static [H2](./h2/) | Nivel 2 [Heading](../../aspose.pdf/heading/), para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static [H3](./h3/) | Nivel 3 [Heading](../../aspose.pdf/heading/), para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static [H4](./h4/) | Nivel 4 [Heading](../../aspose.pdf/heading/), para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static [H5](./h5/) | Nivel 5 [Heading](../../aspose.pdf/heading/), para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static [H6](./h6/) | Nivel 6 [Heading](../../aspose.pdf/heading/), para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static [Index](./index/) | (Index) Una secuencia de entradas que contiene texto identificador acompañado de elementos de referencia que señalan las apariciones del texto especificado en el cuerpo principal de un documento. |
| static [L](./l/) | (List) Una secuencia de elementos de significado e importancia similares. Sus hijos inmediatos deben ser una leyenda opcional (tipo de estructura Caption) seguida de uno o más elementos de lista (tipo de estructura LI). |
| static [Lbl](./lbl/) | (Label) Un nombre o número que distingue un elemento dado de los demás en la misma lista u otro grupo de elementos similares. |
| static [LBody](./lbody/) | (List body) El contenido descriptivo de un elemento de lista. En una lista de diccionario, por ejemplo, contiene la definición del término. Puede contener el contenido directamente o tener otros BLSEs, quizás incluyendo listas anidadas, como hijos. |
| static [LI](./li/) | (List item) Un miembro individual de una lista. Sus hijos pueden ser una o más etiquetas, cuerpos de lista, o ambos (tipos de estructura Lbl o LBody). |
| static [Link](./link/) | (Link) Una asociación entre una porción del contenido del ILSE y una anotación o anotaciones de enlace correspondientes. Sus hijos deben ser uno o más elementos de contenido o ILSEs hijos y una o más referencias de objeto que identifiquen las anotaciones de enlace asociadas. |
| static [NonStruct](./nonstruct/) | (Nonstructural element) Un elemento de agrupación que no tiene una importancia estructural inherente; sirve únicamente para propósitos de agrupación. Este tipo de elemento difiere de una división (tipo de estructura Div) en que no debe interpretarse ni exportarse a otros formatos de documento; sin embargo, sus descendientes deben procesarse normalmente. |
| static [Note](./note/) |  |
| static [P](./p/) | (Paragraph) Una división de texto de bajo nivel. |
| static [Part](./part/) | (Part) Una división a gran escala de un documento. Este tipo de elemento es apropiado para agrupar artículos o secciones. |
| static [Private](./private/) | (Private element) Un elemento de agrupación que contiene contenido privado perteneciente a la aplicación que lo produce. La importancia estructural de este tipo de elemento no está especificada y debe ser determinada íntegramente por el escritor conforme. Ni el elemento Private ni ninguno de sus descendientes deben interpretarse o exportarse a otros formatos de documento. |
| static [Quote](./quote/) |  |
| static [RB](./rb/) | (Ruby base text) El texto de tamaño completo al que se aplica la anotación ruby. RB puede contener texto, otros elementos en línea, o una mezcla de ambos. Puede tener el atributo RubyAlignattribute. |
| static [Reference](./reference/) | (Reference) Una cita a contenido en otra parte del documento. |
| static [RP](./rp/) | (Ruby punctuation) Puntuación que rodea el texto de la anotación ruby. Se usa solo cuando una anotación ruby no puede formatearse correctamente en estilo ruby y en su lugar se formatea como un comentario normal, o cuando se formatea como un warichu. Contiene texto (usualmente un solo LEFT o RIGHT PARENTHESIS o carácter de corchete similar). |
| static [RT](./rt/) | (Ruby annotation text) El texto de tamaño menor que se colocará adyacente al texto base ruby. Puede contener texto, otros elementos en línea, o una mezcla de ambos. Puede tener los atributos RubyAlign y RubyPosition. |
| static [Ruby](./ruby/) |  |
| static [Sect](./sect/) | (Section) Un contenedor para agrupar elementos de contenido relacionados. |
| static [Span](./span/) | (Span) Una porción genérica en línea de texto que no tiene características inherentes particulares. Puede usarse, por ejemplo, para delimitar un rango de texto con un conjunto dado de atributos de estilo. |
| static [Table](./table/) | ([Table](../../aspose.pdf/table/)) Un diseño bidimensional de celdas de datos rectangulares, posiblemente con una subestructura compleja. Contiene una o más filas de tabla (tipo de estructura TR) como hijos; o un encabezado de tabla opcional (tipo de estructura THead) seguido de una o más elementos de cuerpo de tabla (tipo de estructura TBody) y un pie de tabla opcional (tipo de estructura TFoot). Además, una tabla puede tener un título (tipo de estructura Caption) como su primer o último hijo. |
| static [TBody](./tbody/) | ([Table](../../aspose.pdf/table/) body row group; PDF 1.5) Un grupo de filas que constituyen la porción principal del cuerpo de una tabla. Si la tabla se divide en varias páginas, el área del cuerpo puede romperse en un límite de fila. Una tabla puede tener múltiples elementos TBody para permitir el dibujo de un borde o fondo para un conjunto de filas. |
| static [TD](./td/) | ([Table](../../aspose.pdf/table/) data cell) Una celda de tabla que contiene datos que forman parte del contenido de la tabla. |
| static [TFoot](./tfoot/) | ([Table](../../aspose.pdf/table/) footer row group; PDF 1.5) Un grupo de filas que constituyen el pie de una tabla. Si la tabla se divide en varias páginas, estas filas pueden volver a dibujarse al final de cada fragmento de tabla (aunque solo haya un elemento TFoot). |
| static [TH](./th/) | ([Table](../../aspose.pdf/table/) header cell) Una celda de tabla que contiene texto de encabezado que describe una o más filas o columnas de la tabla. |
| static [THead](./thead/) | ([Table](../../aspose.pdf/table/) header row group; PDF 1.5) Un grupo de filas que constituyen el encabezado de una tabla. Si la tabla se divide en varias páginas, estas filas pueden volver a dibujarse en la parte superior de cada fragmento de tabla (aunque solo haya un elemento THead). |
| static [TOC](./toc/) |  |
| static [TOCI](./toci/) |  |
| static [TR](./tr/) | ([Table](../../aspose.pdf/table/) row) Una fila de encabezados o datos en una tabla. Puede contener celdas de encabezado de tabla y celdas de datos de tabla (tipos de estructura TH y TD). |
| static [Warichu](./warichu/) |  |
| static [WP](./wp/) | (Warichu punctuation) La puntuación que rodea el texto WT. Contiene texto (usualmente un solo LEFT o RIGHT PARENTHESIS o carácter de corchete similar). Según JIS X 4051-1995, los paréntesis que rodean un warichu pueden convertirse en un ESPACIO (nominalmente 1/4 EM de ancho) a discreción del formateador. |
| static [WT](./wt/) | (Warichu text) El texto de menor tamaño de un comentario warichu que se formatea en dos líneas y se coloca entre los elementos WP circundantes. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
