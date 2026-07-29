---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa tipos de estructura estándar."
type: docs
weight: 130
url: /es/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

Representa tipos de estructura estándar.

## Campos

| Campo | Descripción |
| --- | --- |
| [Annot](#Annot) | (Annotation; PDF 1.5) Una asociación entre una parte del contenido del ILSE y una anotación PDF correspondiente. Annot deberá usarse para todas las anotaciones PDF excepto las anotaciones de enlace y las anotaciones de widget. |
| [Art](#Art) | (Article) Un cuerpo de texto relativamente autónomo que constituye una única narrativa o exposición. Los artículos deben ser disjuntos; es decir, no deben contener otros artículos como elementos constituyentes. |
| [BibEntry](#BibEntry) | (Bibliography entry) Una referencia que identifica la fuente externa de algún contenido citado. Puede contener una etiqueta (tipo de estructura Lbl) como hijo. Aunque una entrada de bibliografía probablemente incluya partes componentes que identifiquen al autor, obra, editorial y demás del contenido citado, no se definen tipos de estructura estándar a este nivel de detalle. |
| [BlockQuote](#BlockQuote) | (Block quotation) Una porción de texto que consiste en uno o más párrafos atribuidos a alguien distinto del autor del texto circundante. |
| [Caption](#Caption) | (Caption) Una breve porción de texto que describe una tabla o figura. |
| [Code](#Code) | (Code) Un fragmento de texto de programa informático. |
| [Div](#Div) | (Division) Un elemento genérico a nivel de bloque o un grupo de elementos. |
| [Document](#Document) | (Document) Un documento completo. Este es el elemento raíz de cualquier árbol de estructura que contenga múltiples partes o múltiples artículos. |
| [Figure](#Figure) | (Figure) Un elemento de contenido gráfico. Su ubicación puede especificarse con el atributo de diseño Placement. |
| [Form](#Form) | (Form) Una anotación de widget que representa un campo de formulario interactivo. |
| [Formula](#Formula) | (Formula) Una fórmula matemática. Este tipo de estructura es útil solo para identificar un elemento de contenido completo como una fórmula. No se definen tipos de estructura estándar para identificar componentes individuales dentro de la fórmula. Desde el punto de vista del formato, la fórmula debe tratarse de manera similar a una figura (tipo de estructura Figure). |
| [H](#H) | (Heading) Una etiqueta para una subdivisión del contenido de un documento. Debe ser el primer hijo de la división que encabeza. |
| [H1](#H1) | Encabezado de nivel 1, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| [H2](#H2) | Encabezado de nivel 2, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| [H3](#H3) | Encabezado de nivel 3, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| [H4](#H4) | Encabezado de nivel 4, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| [H5](#H5) | Encabezado de nivel 5, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| [H6](#H6) | Encabezado de nivel 6, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento. |
| [Index](#Index) | (Índice) Una secuencia de entradas que contienen texto identificador acompañado de elementos de referencia que señalan las apariciones del texto especificado en el cuerpo principal de un documento. |
| [L](#L) | (Lista) Una secuencia de elementos de significado e importancia similares. Sus hijos inmediatos deben ser una leyenda opcional (tipo de estructura Caption) seguida de uno o más elementos de lista (tipo de estructura LI). |
| [Lbl](#Lbl) | (Etiqueta) Un nombre o número que distingue un elemento dado de los demás en la misma lista u otro grupo de elementos similares. |
| [LBody](#LBody) | (Cuerpo de lista) El contenido descriptivo de un elemento de lista. En una lista de diccionario, por ejemplo, contiene la definición del término. Puede contener el contenido directamente o tener otros BLSEs, quizás incluyendo listas anidadas, como hijos. |
| [LI](#LI) | (Elemento de lista) Un miembro individual de una lista. Sus hijos pueden ser una o más etiquetas, cuerpos de lista, o ambos (tipos de estructura Lbl o LBody). |
| [Link](#Link) | (Enlace) Una asociación entre una porción del contenido del ILSE y una anotación o anotaciones de enlace correspondientes. Sus hijos deben ser uno o más elementos de contenido o ILSEs hijos y una o más referencias de objeto que identifiquen las anotaciones de enlace asociadas. |
| [NonStruct](#NonStruct) | (Elemento no estructural) Un elemento de agrupación que no tiene significado estructural inherente; sirve únicamente para propósitos de agrupación. Este tipo de elemento difiere de una división (tipo de estructura Div) en que no debe interpretarse ni exportarse a otros formatos de documento; sin embargo, sus descendientes deben procesarse normalmente. |
| [Note](#Note) | (Nota) Un elemento de texto explicativo, como una nota al pie o una nota final, que se menciona desde el cuerpo del documento. Puede tener una etiqueta (tipo de estructura Lbl) como hijo. La nota puede incluirse como hijo del elemento estructural en el texto del cuerpo que la referencia, o puede incluirse en otro lugar (como en una sección de notas finales) y accederse mediante una referencia (tipo de estructura Reference). El PDF etiquetado no prescribe la ubicación de las notas al pie en el orden del contenido de la página. Pueden estar en línea o al final de la página, a discreción del escritor conforme. |
| [P](#P) | (Párrafo) Una división de bajo nivel del texto. |
| [Part](#Part) | (Parte) Una división a gran escala de un documento. Este tipo de elemento es apropiado para agrupar artículos o secciones. |
| [Private](#Private) | (Elemento privado) Un elemento de agrupación que contiene contenido privado perteneciente a la aplicación que lo produce. El significado estructural de este tipo de elemento no está especificado y debe ser determinado íntegramente por el escritor conforme. Ni el elemento Privado ni ninguno de sus descendientes deben interpretarse o exportarse a otros formatos de documento. |
| [Quote](#Quote) | (Cita) Una porción de texto en línea atribuida a alguien que no sea el autor del texto circundante. El texto citado debe estar contenido en línea dentro de un solo párrafo. Esto difiere del elemento a nivel de bloque BlockQuote, que consiste en uno o más párrafos completos (u otros elementos presentados como si fueran párrafos completos). |
| [RB](#RB) | (Texto base Ruby) El texto de tamaño completo al que se aplica la anotación ruby. RB puede contener texto, otros elementos en línea o una mezcla de ambos. Puede tener el atributo RubyAlign. |
| [Reference](#Reference) | (Referencia) Una citación a contenido en otra parte del documento. |
| [RP](#RP) | (Puntuación Ruby) Puntuación que rodea el texto de la anotación ruby. Se usa solo cuando una anotación ruby no puede formatearse adecuadamente en estilo ruby y, en su lugar, se formatea como un comentario normal, o cuando se formatea como un warichu. Contiene texto (normalmente un solo PARÉNTESES IZQUIERDO o DERECHO o un carácter de corchete similar). |
| [RT](#RT) | (Texto de anotación Ruby) El texto de menor tamaño que debe colocarse adyacente al texto base Ruby. Puede contener texto, otros elementos en línea o una mezcla de ambos. Puede tener los atributos RubyAlign y RubyPosition. |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) Una nota al margen (anotación) escrita en un tamaño de texto más pequeño y colocada adyacente al texto base al que se refiere. Un elemento Ruby también puede contener los elementos RB, RT y RP. (Ruby) El contenedor que rodea todo el conjunto ruby. Debe contener un elemento RB seguido ya sea de un elemento RT o de un grupo de tres elementos compuesto por RP, RT y RP. Los elementos Ruby y sus elementos de contenido no deben dividirse en varias líneas. |
| [Sect](#Sect) | (Section) Un contenedor para agrupar elementos de contenido relacionados. |
| [Span](#Span) | (Span) Una porción genérica en línea de texto que no posee características inherentes particulares. Puede usarse, por ejemplo, para delimitar un rango de texto con un conjunto determinado de atributos de estilo. |
| [Table](#Table) | (Table) Un diseño bidimensional de celdas de datos rectangulares, que puede tener una subestructura compleja. Contiene ya sea una o más filas de tabla (tipo de estructura TR) como hijos; o una cabecera de tabla opcional (tipo de estructura THead) seguida de una o más elementos de cuerpo de tabla (tipo de estructura TBody) y un pie de tabla opcional (tipo de estructura TFoot). Además, una tabla puede tener una leyenda (tipo de estructura Caption) como su primer o último hijo. |
| [TBody](#TBody) | (Table body row group; PDF 1.5) Un grupo de filas que constituyen la parte principal del cuerpo de una tabla. Si la tabla se divide en varias páginas, el área del cuerpo puede separarse en el límite de una fila. Una tabla puede tener múltiples elementos TBody para permitir el dibujo de un borde o fondo para un conjunto de filas. |
| [TD](#TD) | (Table data cell) Una celda de tabla que contiene datos que forman parte del contenido de la tabla. |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) Un grupo de filas que constituyen el pie de una tabla. Si la tabla se divide en varias páginas, estas filas pueden volver a dibujarse al final de cada fragmento de tabla (aunque solo exista un elemento TFoot). |
| [TH](#TH) | (Table header cell) Una celda de tabla que contiene texto de encabezado que describe una o más filas o columnas de la tabla. |
| [THead](#THead) | (Table header row group; PDF 1.5) Un grupo de filas que constituyen el encabezado de una tabla. Si la tabla se divide en varias páginas, estas filas pueden volver a dibujarse en la parte superior de cada fragmento de tabla (aunque solo exista un elemento THead). |
| [TOC](#TOC) | (Table of contents) Una lista compuesta por entradas de elementos de tabla de contenido (tipo de estructura TOCI) y/o otras entradas de tabla de contenido anidadas (TOC). Una entrada TOC que solo incluye entradas TOCI representa una jerarquía plana. Una entrada TOC que incluye otras entradas TOC anidadas (y posiblemente entradas TOCI) representa una jerarquía más compleja. Idealmente, la jerarquía de una entrada TOC de nivel superior refleja la estructura del cuerpo principal del documento. |
| [TOCI](#TOCI) | (Table of contents item) Un miembro individual de una tabla de contenido. Los hijos de esta entrada pueden ser cualquiera de los siguientes tipos de estructura: Lbl - Una etiqueta Reference - Una referencia al título y al número de página NonStruct - Elementos sin estructura para envolver un artefacto líder P - Texto descriptivo TOC - Elementos de tabla de contenido para tablas de contenido jerárquicas, como se describe en la entrada TOC |
| [TR](#TR) | (Table row) Una fila de encabezados o datos en una tabla. Puede contener celdas de encabezado de tabla y celdas de datos de tabla (tipos de estructura TH y TD). |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) Un comentario o anotación en un tamaño de texto más pequeño y formateado en dos líneas más pequeñas dentro de la altura de la línea de texto contenedora y colocado después (en línea) del texto base al que se refiere. Un elemento Warichu también puede contener los elementos WT y WP. (Warichu) El contenedor que rodea todo el conjunto warichu. Puede contener un grupo de tres elementos compuesto por WP, WT y WP. Los elementos Warichu (y sus elementos de contenido) pueden envolver varias líneas, según las reglas de ruptura de warichu descritas en la Norma Industrial Japonesa (JIS) X 4051-1995. |
| [WP](#WP) | (Warichu punctuation) La puntuación que rodea el texto WT. Contiene texto (usualmente un solo PARÉNTESIS IZQUIERDO o DERECHO o un carácter de corchete similar). Según JIS X 4051-1995, los paréntesis que rodean un warichu pueden convertirse en un ESPACIO (nominalmente 1/4 EM de ancho) a discreción del formateador. |
| [WT](#WT) | (Warichu text) El texto de menor tamaño de un comentario warichu que se formatea en dos líneas y se coloca entre los elementos WP circundantes. |

## Métodos

| Método | Descripción |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | Obtiene la categoría del Tipo de Estructura Estándar. |
| [getTag](#getTag--) | Obtiene el nombre de etiqueta de {@code StructureElement}. |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | Realiza una conversión explícita de {@link String} a {@link StructureTypeStandard}. |
| [toString](#toString--) | Devuelve una cadena que representa el objeto actual. |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(Annotation; PDF 1.5) Una asociación entre una parte del contenido del ILSE y una anotación PDF correspondiente. Annot deberá usarse para todas las anotaciones PDF excepto las anotaciones de enlace y las anotaciones de widget.

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(Article) Un cuerpo de texto relativamente autónomo que constituye una única narrativa o exposición. Los artículos deben ser disjuntos; es decir, no deben contener otros artículos como elementos constituyentes.

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(Bibliography entry) Una referencia que identifica la fuente externa de algún contenido citado. Puede contener una etiqueta (tipo de estructura Lbl) como hijo. Aunque una entrada de bibliografía probablemente incluya partes componentes que identifiquen al autor, obra, editorial y demás del contenido citado, no se definen tipos de estructura estándar a este nivel de detalle.

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(Block quotation) Una porción de texto que consiste en uno o más párrafos atribuidos a alguien distinto del autor del texto circundante.

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(Caption) Una breve porción de texto que describe una tabla o figura.

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(Code) Un fragmento de texto de programa informático.

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(Division) Un elemento genérico a nivel de bloque o un grupo de elementos.

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(Document) Un documento completo. Este es el elemento raíz de cualquier árbol de estructura que contenga múltiples partes o múltiples artículos.

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(Figure) Un elemento de contenido gráfico. Su ubicación puede especificarse con el atributo de diseño Placement.

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(Form) Una anotación de widget que representa un campo de formulario interactivo.

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(Formula) Una fórmula matemática. Este tipo de estructura es útil solo para identificar un elemento de contenido completo como una fórmula. No se definen tipos de estructura estándar para identificar componentes individuales dentro de la fórmula. Desde el punto de vista del formato, la fórmula debe tratarse de manera similar a una figura (tipo de estructura Figure).

### H {#H}
```
public static final StructureTypeStandard H
```

(Heading) Una etiqueta para una subdivisión del contenido de un documento. Debe ser el primer hijo de la división que encabeza.

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

Encabezado de nivel 1, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento.

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

Encabezado de nivel 2, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento.

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Encabezado de nivel 3, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento.

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Encabezado de nivel 4, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento.

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Encabezado de nivel 5, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento.

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Encabezado de nivel 6, para su uso en escritores conformes que no pueden anidar jerárquicamente sus secciones y, por lo tanto, no pueden determinar el nivel de un encabezado a partir de su nivel de anidamiento.

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Índice) Una secuencia de entradas que contienen texto identificador acompañado de elementos de referencia que señalan las apariciones del texto especificado en el cuerpo principal de un documento.

### L {#L}
```
public static final StructureTypeStandard L
```

(Lista) Una secuencia de elementos de significado e importancia similares. Sus hijos inmediatos deben ser una leyenda opcional (tipo de estructura Caption) seguida de uno o más elementos de lista (tipo de estructura LI).

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Etiqueta) Un nombre o número que distingue un elemento dado de los demás en la misma lista u otro grupo de elementos similares.

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(Cuerpo de lista) El contenido descriptivo de un elemento de lista. En una lista de diccionario, por ejemplo, contiene la definición del término. Puede contener el contenido directamente o tener otros BLSEs, quizás incluyendo listas anidadas, como hijos.

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(Elemento de lista) Un miembro individual de una lista. Sus hijos pueden ser una o más etiquetas, cuerpos de lista, o ambos (tipos de estructura Lbl o LBody).

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Enlace) Una asociación entre una porción del contenido del ILSE y una anotación o anotaciones de enlace correspondientes. Sus hijos deben ser uno o más elementos de contenido o ILSEs hijos y una o más referencias de objeto que identifiquen las anotaciones de enlace asociadas.

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Elemento no estructural) Un elemento de agrupación que no tiene significado estructural inherente; sirve únicamente para propósitos de agrupación. Este tipo de elemento difiere de una división (tipo de estructura Div) en que no debe interpretarse ni exportarse a otros formatos de documento; sin embargo, sus descendientes deben procesarse normalmente.

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Nota) Un elemento de texto explicativo, como una nota al pie o una nota final, que se menciona desde el cuerpo del documento. Puede tener una etiqueta (tipo de estructura Lbl) como hijo. La nota puede incluirse como hijo del elemento estructural en el texto del cuerpo que la referencia, o puede incluirse en otro lugar (como en una sección de notas finales) y accederse mediante una referencia (tipo de estructura Reference). El PDF etiquetado no prescribe la ubicación de las notas al pie en el orden del contenido de la página. Pueden estar en línea o al final de la página, a discreción del escritor conforme.

### P {#P}
```
public static final StructureTypeStandard P
```

(Párrafo) Una división de bajo nivel del texto.

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Parte) Una división a gran escala de un documento. Este tipo de elemento es apropiado para agrupar artículos o secciones.

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Elemento privado) Un elemento de agrupación que contiene contenido privado perteneciente a la aplicación que lo produce. El significado estructural de este tipo de elemento no está especificado y debe ser determinado íntegramente por el escritor conforme. Ni el elemento Privado ni ninguno de sus descendientes deben interpretarse o exportarse a otros formatos de documento.

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Cita) Una porción de texto en línea atribuida a alguien que no sea el autor del texto circundante. El texto citado debe estar contenido en línea dentro de un solo párrafo. Esto difiere del elemento a nivel de bloque BlockQuote, que consiste en uno o más párrafos completos (u otros elementos presentados como si fueran párrafos completos).

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Texto base Ruby) El texto de tamaño completo al que se aplica la anotación ruby. RB puede contener texto, otros elementos en línea o una mezcla de ambos. Puede tener el atributo RubyAlign.

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Referencia) Una citación a contenido en otra parte del documento.

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Puntuación Ruby) Puntuación que rodea el texto de la anotación ruby. Se usa solo cuando una anotación ruby no puede formatearse adecuadamente en estilo ruby y, en su lugar, se formatea como un comentario normal, o cuando se formatea como un warichu. Contiene texto (normalmente un solo PARÉNTESES IZQUIERDO o DERECHO o un carácter de corchete similar).

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Texto de anotación Ruby) El texto de menor tamaño que debe colocarse adyacente al texto base Ruby. Puede contener texto, otros elementos en línea o una mezcla de ambos. Puede tener los atributos RubyAlign y RubyPosition.

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby; PDF 1.5) Una nota al margen (anotación) escrita en un tamaño de texto más pequeño y colocada adyacente al texto base al que se refiere. Un elemento Ruby también puede contener los elementos RB, RT y RP. (Ruby) El contenedor que rodea todo el conjunto ruby. Debe contener un elemento RB seguido ya sea de un elemento RT o de un grupo de tres elementos compuesto por RP, RT y RP. Los elementos Ruby y sus elementos de contenido no deben dividirse en varias líneas.

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) Un contenedor para agrupar elementos de contenido relacionados.

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) Una porción genérica en línea de texto que no posee características inherentes particulares. Puede usarse, por ejemplo, para delimitar un rango de texto con un conjunto determinado de atributos de estilo.

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) Un diseño bidimensional de celdas de datos rectangulares, que puede tener una subestructura compleja. Contiene ya sea una o más filas de tabla (tipo de estructura TR) como hijos; o una cabecera de tabla opcional (tipo de estructura THead) seguida de una o más elementos de cuerpo de tabla (tipo de estructura TBody) y un pie de tabla opcional (tipo de estructura TFoot). Además, una tabla puede tener una leyenda (tipo de estructura Caption) como su primer o último hijo.

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group; PDF 1.5) Un grupo de filas que constituyen la parte principal del cuerpo de una tabla. Si la tabla se divide en varias páginas, el área del cuerpo puede separarse en el límite de una fila. Una tabla puede tener múltiples elementos TBody para permitir el dibujo de un borde o fondo para un conjunto de filas.

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) Una celda de tabla que contiene datos que forman parte del contenido de la tabla.

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group; PDF 1.5) Un grupo de filas que constituyen el pie de una tabla. Si la tabla se divide en varias páginas, estas filas pueden volver a dibujarse al final de cada fragmento de tabla (aunque solo exista un elemento TFoot).

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) Una celda de tabla que contiene texto de encabezado que describe una o más filas o columnas de la tabla.

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group; PDF 1.5) Un grupo de filas que constituyen el encabezado de una tabla. Si la tabla se divide en varias páginas, estas filas pueden volver a dibujarse en la parte superior de cada fragmento de tabla (aunque solo exista un elemento THead).

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) Una lista compuesta por entradas de elementos de tabla de contenido (tipo de estructura TOCI) y/o otras entradas de tabla de contenido anidadas (TOC). Una entrada TOC que solo incluye entradas TOCI representa una jerarquía plana. Una entrada TOC que incluye otras entradas TOC anidadas (y posiblemente entradas TOCI) representa una jerarquía más compleja. Idealmente, la jerarquía de una entrada TOC de nivel superior refleja la estructura del cuerpo principal del documento.

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) Un miembro individual de una tabla de contenido. Los hijos de esta entrada pueden ser cualquiera de los siguientes tipos de estructura: Lbl - Una etiqueta Reference - Una referencia al título y al número de página NonStruct - Elementos sin estructura para envolver un artefacto líder P - Texto descriptivo TOC - Elementos de tabla de contenido para tablas de contenido jerárquicas, como se describe en la entrada TOC

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) Una fila de encabezados o datos en una tabla. Puede contener celdas de encabezado de tabla y celdas de datos de tabla (tipos de estructura TH y TD).

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu; PDF 1.5) Un comentario o anotación en un tamaño de texto más pequeño y formateado en dos líneas más pequeñas dentro de la altura de la línea de texto contenedora y colocado después (en línea) del texto base al que se refiere. Un elemento Warichu también puede contener los elementos WT y WP. (Warichu) El contenedor que rodea todo el conjunto warichu. Puede contener un grupo de tres elementos compuesto por WP, WT y WP. Los elementos Warichu (y sus elementos de contenido) pueden envolver varias líneas, según las reglas de ruptura de warichu descritas en la Norma Industrial Japonesa (JIS) X 4051-1995.

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) La puntuación que rodea el texto WT. Contiene texto (usualmente un solo PARÉNTESIS IZQUIERDO o DERECHO o un carácter de corchete similar). Según JIS X 4051-1995, los paréntesis que rodean un warichu pueden convertirse en un ESPACIO (nominalmente 1/4 EM de ancho) a discreción del formateador.

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Warichu text) El texto de menor tamaño de un comentario warichu que se formatea en dos líneas y se coloca entre los elementos WP circundantes.

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

Obtiene la categoría del Tipo de Estructura Estándar.

**Returns:**
Valor: Categoría del Tipo de Estructura Estándar.

### getTag {#getTag--}
```
public final String getTag()
```

Obtiene el nombre de etiqueta de {@code StructureElement}.

**Returns:**
Nombre de etiqueta de {@code StructureElement}.

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
Realiza una conversión explícita de {@link String} a {@link StructureTypeStandard}.

### toString {#toString--}
```
public String toString()
```

Devuelve una cadena que representa el objeto actual.

**Returns:**
Cadena que representa el objeto actual.
