---
title: Class StructureTypeStandard
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LogicalStructure.StructureTypeStandard. Representa Tipos de Estructura Estándar
type: docs
weight: 6730
url: /es/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## Clase StructureTypeStandard

Representa Tipos de Estructura Estándar.

```csharp
public sealed class StructureTypeStandard
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | Obtiene la categoría del Tipo de Estructura Estándar. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | Obtiene el nombre de la etiqueta de [`StructureElement`](../structureelement/). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Devuelve una cadena que representa el objeto actual. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Realiza una conversión explícita de String a `StructureTypeStandard`. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Anotación; PDF 1.5) Una asociación entre una parte del contenido del ILSE y una anotación PDF correspondiente. Annot se utilizará para todas las anotaciones PDF excepto las anotaciones de enlace y las anotaciones de widget. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Artículo) Un cuerpo de texto relativamente autónomo que constituye una narrativa o exposición única. Los artículos deben ser disjuntos; es decir, no deben contener otros artículos como elementos constitutivos. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Entrada de bibliografía) Una referencia que identifica la fuente externa de algún contenido citado. Puede contener una etiqueta (tipo de estructura Lbl) como hijo. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Cita en bloque) Una porción de texto que consiste en uno o más párrafos atribuidos a alguien que no sea el autor del texto circundante. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Título) Una breve porción de texto que describe una tabla o figura. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Código) Un fragmento de texto de programa informático. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (División) Un elemento de bloque genérico o grupo de elementos. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Documento) Un documento completo. Este es el elemento raíz de cualquier árbol de estructura que contenga múltiples partes o múltiples artículos. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figura) Un elemento de contenido gráfico. Su colocación puede especificarse con el atributo de diseño de colocación. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Formulario) Una anotación de widget que representa un campo de formulario interactivo. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Fórmula) Una fórmula matemática. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Encabezado) Una etiqueta para una subdivisión del contenido de un documento. Debe ser el primer hijo de la división que encabeza. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Encabezado de Nivel 1, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Encabezado de Nivel 2, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Encabezado de Nivel 3, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Encabezado de Nivel 4, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Encabezado de Nivel 5, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Encabezado de Nivel 6, para uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Índice) Una secuencia de entradas que contienen texto identificador acompañado de elementos de referencia que señalan ocurrencias del texto especificado en el cuerpo principal de un documento. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (Lista) Una secuencia de elementos de significado e importancia similares. Sus hijos inmediatos deben ser un título opcional (tipo de estructura Caption) seguido de uno o más elementos de lista (tipo de estructura LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Etiqueta) Un nombre o número que distingue un elemento dado de otros en la misma lista u otro grupo de elementos similares. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (Cuerpo de lista) El contenido descriptivo de un elemento de lista. En una lista de diccionario, por ejemplo, contiene la definición del término. Puede contener el contenido directamente o tener otros BLSEs, quizás incluyendo listas anidadas, como hijos. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (Elemento de lista) Un miembro individual de una lista. Sus hijos pueden ser una o más etiquetas, cuerpos de lista, o ambos (tipos de estructura Lbl o LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Enlace) Una asociación entre una parte del contenido del ILSE y una o más anotaciones de enlace correspondientes. Sus hijos deben ser uno o más elementos de contenido o ILSEs hijos y una o más referencias de objeto que identifiquen las anotaciones de enlace asociadas. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Elemento no estructural) Un elemento de agrupamiento que no tiene un significado estructural inherente; sirve únicamente para fines de agrupamiento. Este tipo de elemento difiere de una división (tipo de estructura Div) en que no se interpretará ni exportará a otros formatos de documento; sin embargo, sus descendientes se procesarán normalmente. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Nota) Un elemento de texto explicativo, como una nota al pie o una nota final, que se menciona desde el cuerpo del documento. Puede tener una etiqueta (tipo de estructura Lbl) como hijo. La nota puede incluirse como un hijo del elemento de estructura en el texto del cuerpo que se refiere a ella, o puede incluirse en otro lugar (como en una sección de notas finales) y accederse mediante una referencia (tipo de estructura Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Párrafo) Una división de bajo nivel de texto. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Parte) Una división a gran escala de un documento. Este tipo de elemento es apropiado para agrupar artículos o secciones. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Elemento privado) Un elemento de agrupamiento que contiene contenido privado perteneciente a la aplicación que lo produce. El significado estructural de este tipo de elemento no está especificado y será determinado completamente por el escritor conforme. Ni el elemento Private ni ninguno de sus descendientes serán interpretados o exportados a otros formatos de documento. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Cita) Una porción de texto en línea atribuida a alguien que no sea el autor del texto circundante. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Texto base Ruby) El texto de tamaño completo al que se aplica la anotación ruby. RB puede contener texto, otros elementos en línea, o una mezcla de ambos. Puede tener el atributo RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Referencia) Una cita a contenido en otro lugar del documento. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Puntuación Ruby) Puntuación que rodea el texto de la anotación ruby. Se utiliza solo cuando una anotación ruby no puede formatearse correctamente en un estilo ruby y en su lugar se formatea como un comentario normal, o cuando se formatea como un warichu. Contiene texto (generalmente un solo PARÉNTESIS IZQUIERDO o DERECHO o un carácter de agrupamiento similar). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Texto de anotación Ruby) El texto de menor tamaño que se colocará junto al texto base ruby. Puede contener texto, otros elementos en línea, o una mezcla de ambos. Puede tener los atributos RubyAlign y RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) Una nota al margen (anotación) escrita en un tamaño de texto más pequeño y colocada junto al texto base al que se refiere. Un elemento Ruby también puede contener los elementos RB, RT y RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Sección) Un contenedor para agrupar elementos de contenido relacionados. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) Una porción de texto en línea genérica que no tiene características inherentes particulares. Puede usarse, por ejemplo, para delimitar un rango de texto con un conjunto dado de atributos de estilo. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Tabla) Un diseño bidimensional de celdas de datos rectangulares, que puede tener una subestructura compleja. Contiene una o más filas de tabla (tipo de estructura TR) como hijos; o un encabezado de tabla opcional (tipo de estructura THead) seguido de uno o más elementos de cuerpo de tabla (tipo de estructura TBody) y un pie de tabla opcional (tipo de estructura TFoot). Además, una tabla puede tener un título (tipo de estructura Caption) como su primer o último hijo. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Grupo de filas del cuerpo de la tabla; PDF 1.5) Un grupo de filas que constituyen la porción principal del cuerpo de una tabla. Si la tabla se divide en múltiples páginas, el área del cuerpo puede separarse en un límite de fila. Una tabla puede tener múltiples elementos TBody para permitir el dibujo de un borde o fondo para un conjunto de filas. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Celda de datos de la tabla) Una celda de tabla que contiene datos que son parte del contenido de la tabla. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Grupo de filas del pie de la tabla; PDF 1.5) Un grupo de filas que constituyen el pie de una tabla. Si la tabla se divide en múltiples páginas, estas filas pueden redibujarse en la parte inferior de cada fragmento de tabla (aunque solo hay un elemento TFoot). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Celda de encabezado de la tabla) Una celda de tabla que contiene texto de encabezado que describe una o más filas o columnas de la tabla. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Grupo de filas del encabezado de la tabla; PDF 1.5) Un grupo de filas que constituyen el encabezado de una tabla. Si la tabla se divide en múltiples páginas, estas filas pueden redibujarse en la parte superior de cada fragmento de tabla (aunque solo hay un elemento THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Tabla de contenido) Una lista compuesta por entradas de elementos de tabla de contenido (tipo de estructura TOCI) y/o otras entradas de tabla de contenido anidadas (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Elemento de tabla de contenido) Un miembro individual de una tabla de contenido. Los hijos de esta entrada pueden ser cualquiera de los siguientes tipos de estructura: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Fila de tabla) Una fila de encabezados o datos en una tabla. Puede contener celdas de encabezado de tabla y celdas de datos de tabla (tipos de estructura TH y TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) Un comentario o anotación en un tamaño de texto más pequeño y formateado en dos líneas más pequeñas dentro de la altura de la línea de texto contenedora y colocado después (en línea) del texto base al que se refiere. Un elemento Warichu también puede contener los elementos WT y WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Puntuación Warichu) La puntuación que rodea el texto WT. Contiene texto (generalmente un solo PARÉNTESIS IZQUIERDO o DERECHO o un carácter de agrupamiento similar). De acuerdo con JIS X 4051-1995, los paréntesis que rodean un warichu pueden convertirse en un ESPACIO (nominalmente 1/4 EM de ancho) a discreción del formateador. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Texto Warichu) El texto de menor tamaño de un comentario warichu que se formatea en dos líneas y se coloca entre los elementos WP circundantes. |

### Ver También

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)