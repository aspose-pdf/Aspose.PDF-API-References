---
title: StructureTypeStandard
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa tipos de estructura estándar.
type: docs
weight: 4560
url: /es/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

Representa tipos de estructura estándar.

```csharp
public sealed class StructureTypeStandard
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category) { get; } | Obtiene la categoría del tipo de estructura estándar. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag) { get; } | Obtiene el nombre de etiqueta de[`StructureElement`](../structureelement) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring)() | Devuelve una cadena que representa el objeto actual. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit) | Realiza una conversión explícita deString a[`StructureTypeStandard`](../structuretypestandard) . |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot) | (Anotación; PDF 1.5) Una asociación entre una parte del contenido de ILSE y una anotación PDF correspondiente. Annot se utilizará para todas las anotaciones de PDF, excepto las anotaciones de enlaces y las anotaciones de widgets. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art) | (Artículo) Un cuerpo de texto relativamente autónomo que constituye una sola narración o exposición. Los artículos deben ser disjuntos; es decir, no deben contener otros artículos como elementos constitutivos. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry) | (Entrada de bibliografía) Una referencia que identifica la fuente externa de algún contenido citado. Puede contener una etiqueta (tipo de estructura Lbl) como elemento secundario. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote) | (Cita en bloque) Una porción de texto que consta de uno o más párrafos atribuidos a alguien que no es el autor del texto circundante. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption) | (Título) Una breve porción de texto que describe una tabla o figura. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code) | (Código) Un fragmento de texto de programa de computadora. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div) | (División) Un elemento genérico a nivel de bloque o grupo de elementos. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document) | (Documento) Un documento completo. Este es el elemento raíz de cualquier estructura de árbol que contenga varias partes o varios artículos. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure) | (Figura) Un elemento de contenido gráfico. Su ubicación se puede especificar con el atributo Diseño de ubicación. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form) | (Formulario) Una anotación de widget que representa un campo de formulario interactivo. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula) | (Fórmula) Una fórmula matemática. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h) | (Título) Una etiqueta para una subdivisión del contenido de un documento. Debe ser el primer hijo de la división que encabeza. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1) | Encabezado de nivel 1, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2) | Encabezado de nivel 2, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3) | Encabezado de nivel 3, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4) | Encabezado de nivel 4, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5) | Encabezado de nivel 5, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6) | Encabezado de nivel 6, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index) | (Índice) Secuencia de entradas que contienen texto de identificación acompañado de elementos de referencia que señalan las apariciones del texto especificado en el cuerpo principal de un documento. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l) | (Lista) Una secuencia de elementos de igual significado e importancia. Sus hijos inmediatos deben ser un título opcional (tipo de estructura Título) seguido de uno o más elementos de lista (tipo de estructura LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl) | (Etiqueta) Nombre o número que distingue un elemento dado de otros en la misma lista u otro grupo de elementos similares. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody) | (Cuerpo de lista) El contenido descriptivo de un elemento de lista. En una lista de diccionario, por ejemplo, contiene la definición del término. Puede contener el contenido directamente o tener otros BLSE, tal vez incluyendo listas anidadas, como elementos secundarios. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li) | (Elemento de lista) Un miembro individual de una lista. Sus elementos secundarios pueden ser una o más etiquetas, cuerpos de lista o ambos (tipos de estructura Lbl o LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link) | (Enlace) Una asociación entre una parte del contenido de ILSE y una anotación o anotaciones de enlace correspondientes. Sus elementos secundarios deben ser uno o más elementos de contenido o ILSE secundarios y una o más referencias de objetos que identifiquen las anotaciones de enlace asociadas. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct) | (Elemento no estructural) Un elemento de agrupación que no tiene un significado estructural inherente; sirve únicamente para fines de agrupación. Este tipo de elemento se diferencia de una división (estructura tipo Div) en que no se interpretará ni exportará a otros formatos de documento; sin embargo, sus descendientes serán procesados normalmente. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note) | (Nota) Elemento de texto explicativo, como una nota al pie o al final, al que se hace referencia desde el cuerpo del documento. Puede tener una etiqueta (tipo de estructura Lbl) como hijo. La nota se puede incluir como elemento secundario del elemento de estructura en el cuerpo del texto que hace referencia a ella, o se puede incluir en otro lugar (como en una sección de notas al final) y se puede acceder a ella por medio de una referencia (tipo de estructura Referencia). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p) | (Párrafo) Una división de texto de bajo nivel. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part) | (Parte) Una división a gran escala de un documento. Este tipo de elemento es apropiado para agrupar artículos o secciones. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private) | (Elemento privado) Un elemento de agrupación que contiene contenido privado perteneciente a la aplicación que lo produce. El significado estructural de este tipo de elemento no se especifica y será determinado en su totalidad por el redactor conforme. Ni el elemento Privado ni ninguno de sus descendientes será interpretado o exportado a otros formatos de documento. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote) | (Cita) Una porción de texto en línea atribuida a alguien que no es el autor del texto circundante. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb) | (Texto base Ruby) El texto de tamaño completo al que se aplica la anotación Ruby. RB puede contener texto, otros elementos en línea o una combinación de ambos. Puede tener el atributo RubyAlignattribute. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference) | (Referencia) Una cita del contenido en otra parte del documento. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp) | (puntuación rubí) Puntuación que rodea el texto de la anotación rubí. Se usa solo cuando una anotación ruby no se puede formatear correctamente en un estilo ruby y en su lugar se formatea como un comentario normal, o cuando se formatea como warichu. Contiene texto (generalmente un paréntesis IZQUIERDO o DERECHO o un carácter de corchete similar). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt) | (Texto de anotación Ruby) El texto de menor tamaño que se colocará junto al texto base Ruby. Puede contener texto, otros elementos en línea o una combinación de ambos. Puede tener los atributos RubyAlign y RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby) | (Ruby; PDF 1.5) Una nota al margen (anotación) escrita en un tamaño de texto más pequeño y colocada junto al texto base al que se refiere. Un elemento Ruby también puede contener los elementos RB, RT y RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect) | (Sección) Un contenedor para agrupar elementos de contenido relacionados. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span) | (Span) Una porción de texto en línea genérica que no tiene características inherentes particulares. Se puede utilizar, por ejemplo, para delimitar un rango de texto con un conjunto determinado de atributos de estilo. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table) | (Tabla) Diseño bidimensional de celdas de datos rectangulares, posiblemente con una subestructura compleja. Contiene una o más filas de tabla (tipo de estructura TR) como elementos secundarios; o un encabezado de tabla opcional (tipo de estructura THead) seguido de uno o más elementos del cuerpo de la tabla (tipo de estructura TBody) y un pie de tabla opcional (tipo de estructura TFoot). Además, una tabla puede tener un título (tipo de estructura Título) como su primer o último hijo. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody) | (Grupo de filas del cuerpo de la tabla; PDF 1.5) Un grupo de filas que constituyen la parte principal del cuerpo de una tabla. Si la tabla está dividida en varias páginas, el área del cuerpo puede dividirse en un límite de fila. Una tabla puede tener varios elementos TBody para permitir el dibujo de un borde o fondo para un conjunto de filas. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td) | (Celda de datos de tabla) Una celda de tabla que contiene datos que forman parte del contenido de la tabla. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot) | (Grupo de filas de pie de página de tabla; PDF 1.5) Un grupo de filas que constituyen el pie de página de una tabla. Si la tabla está dividida en varias páginas, estas filas se pueden volver a dibujar en la parte inferior de cada fragmento de la tabla (aunque solo hay un elemento TFoot). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th) | (celda de encabezado de tabla) Una celda de tabla que contiene texto de encabezado que describe una o más filas o columnas de la tabla. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead) | (Grupo de filas de encabezado de tabla; PDF 1.5) Un grupo de filas que constituyen el encabezado de una tabla. Si la tabla está dividida en varias páginas, estas filas se pueden volver a dibujar en la parte superior de cada fragmento de la tabla (aunque solo hay un elemento THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc) | (Tabla de contenidos) Una lista formada por entradas de elementos de la tabla de contenidos (tipo de estructura TOCI) y/u otras entradas anidadas de la tabla de contenidos (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci) | (Elemento de tabla de contenido) Un miembro individual de una tabla de contenido. Los hijos de esta entrada pueden ser cualquiera de los siguientes tipos de estructuras: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr) | (fila de tabla) Una fila de encabezados o datos en una tabla. Puede contener celdas de encabezado de tabla y celdas de datos de tabla (tipos de estructura TH y TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu) | (Warichu; PDF 1.5) Un comentario o anotación en un tamaño de texto más pequeño y formateado en dos líneas más pequeñas dentro de la altura de la línea de texto que lo contiene y colocado después (en línea) del texto base al que se refiere. Un elemento Warichu también puede contener los elementos WT y WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp) | (puntuación Warichu) La puntuación que rodea el texto WT. Contiene texto (por lo general, un solo paréntesis IZQUIERDO o DERECHO o un carácter de corchete similar). De acuerdo con JIS X 4051-1995, los paréntesis que rodean a un warichu se pueden convertir en un ESPACIO (nominalmente 1/4 EM de ancho) a discreción del formateador. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt) | (texto Warichu) El texto de tamaño más pequeño de un comentario warichu que se formatea en dos líneas y se coloca entre los elementos circundantes de WP. |

### Ver también

* espacio de nombres [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
