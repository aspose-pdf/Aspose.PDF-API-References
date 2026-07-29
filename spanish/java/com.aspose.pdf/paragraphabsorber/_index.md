---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa un objeto absorbente de objetos de estructura de página como secciones y párrafos. Realiza búsquedas de secciones y párrafos de texto y proporciona acceso a.</p>"
type: docs
weight: 3470
url: /es/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> Representa un objeto absorbente de objetos de estructura de página como secciones y párrafos. Realiza búsquedas de secciones y párrafos de texto y proporciona acceso a rectángulos y polígonos que lo describen en el espacio de coordenadas del texto. También realiza búsquedas de segmentos de texto y proporciona acceso a los resultados de búsqueda mediante colecciones de {@code TextFragments} agrupadas por elementos de estructura. </p> El ejemplo muestra cómo encontrar el primer segmento de texto de cada párrafo en la primera página del documento PDF y resaltarlo. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Cuando la búsqueda se completa, la colección {@code ParagraphAbsorber.PageMarkups} contendrá objetos {@code PageMarkup} que representan la estructura de la página mediante colecciones de {@code MarkupSection} y {@code MarkupParagraph}. El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, a sus propiedades y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | Inicializa una nueva instancia de {@code ParagraphAbsorber} que realiza búsquedas de secciones/párrafos del documento o página. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> Inicializa una nueva instancia de {@code ParagraphAbsorber} que realiza búsquedas de secciones/párrafos del documento o página. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | Inicializa una nueva instancia de {@code ParagraphAbsorber} que realiza búsquedas de secciones/párrafos del documento o página. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | Inicializa una nueva instancia de {@code ParagraphAbsorber} que realiza búsquedas de secciones/párrafos del documento o página. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | Obtiene la colección de {@code PageMarkup} que fueron absorbidos. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | Obtiene el ParagraphAbsorberOptions. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> Obtiene o establece el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos más finos de la estructura. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas). </p><hr> Incrementar este valor puede provocar una ligera disminución del rendimiento sin cambios visibles en el resultado de la búsqueda. Disminuir este valor puede conducir a una determinación incorrecta de los párrafos en las secciones. No recomendamos establecer un valor inferior al predeterminado si no desea obtener solo elementos 'básicos' de la estructura de la página. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Obtiene o establece el TextReplaceOptions. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Obtiene o establece el valor que indica si las líneas de texto iniciales de una sección siguiente pueden ser tratadas como continuación del último párrafo de una sección anterior. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Obtiene o establece el valor que indica si las líneas de texto iniciales de una sección siguiente pueden ser tratadas como continuación del último párrafo de una sección anterior. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | Establece el ParagraphAbsorberOptions. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> Obtiene o establece el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos más finos de la estructura. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas). </p><hr> Incrementar este valor puede provocar una ligera disminución del rendimiento sin cambios visibles en el resultado de la búsqueda. Disminuir este valor puede conducir a una determinación incorrecta de los párrafos en las secciones. No recomendamos establecer un valor inferior al predeterminado si no desea obtener solo elementos 'básicos' de la estructura de la página. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Obtiene o establece el TextReplaceOptions. |
| [visit](#visit-com.aspose.pdf.Document-) | Realiza una búsqueda de secciones y párrafos en el {@link Document} especificado. |
| [visit](#visit-com.aspose.pdf.Page-) | Realiza una búsqueda en la {@code Page} especificada. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

Inicializa una nueva instancia de {@code ParagraphAbsorber} que realiza búsquedas de secciones/párrafos del documento o página.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> Inicializa una nueva instancia de {@code ParagraphAbsorber} que realiza búsquedas de secciones/párrafos del documento o página. </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sectionsSearchDepth |  | Número de búsquedas secuenciales para elementos de estructura más finos que se realizarán. <hr> Consulte la propiedad {@code ParagraphAbsorber.SectionsSearchDepth} para obtener más indicaciones sobre el parámetro. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
Inicializa una nueva instancia de {@code ParagraphAbsorber} que realiza búsquedas de secciones/párrafos del documento o página.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
Inicializa una nueva instancia de {@code ParagraphAbsorber} que realiza búsquedas de secciones/párrafos del documento o página.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

Obtiene la colección de {@code PageMarkup} que fueron absorbidos.

**Returns:**
Lista de instancias de PageMarkup

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

Obtiene el ParagraphAbsorberOptions.

**Returns:**
Instancia de ParagraphAbsorberOptions

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> Obtiene o establece el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos más finos de la estructura. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas). </p><hr> Incrementar este valor puede provocar una ligera disminución del rendimiento sin cambios visibles en el resultado de la búsqueda. Disminuir este valor puede conducir a una determinación incorrecta de los párrafos en las secciones. No recomendamos establecer un valor inferior al predeterminado si no desea obtener solo elementos 'básicos' de la estructura de la página.

**Returns:**
valor int

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

Obtiene o establece el TextReplaceOptions.

**Returns:**
Instancia de TextReplaceOptions

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Obtiene o establece el valor que indica si las líneas de texto iniciales de una sección siguiente pueden ser tratadas como continuación del último párrafo de una sección anterior.

**Returns:**
valor booleano

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Obtiene o establece el valor que indica si las líneas de texto iniciales de una sección siguiente pueden ser tratadas como continuación del último párrafo de una sección anterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
Establece el ParagraphAbsorberOptions.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> Obtiene o establece el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos más finos de la estructura. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas). </p><hr> Incrementar este valor puede provocar una ligera disminución del rendimiento sin cambios visibles en el resultado de la búsqueda. Disminuir este valor puede conducir a una determinación incorrecta de los párrafos en las secciones. No recomendamos establecer un valor inferior al predeterminado si no desea obtener solo elementos 'básicos' de la estructura de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Obtiene o establece el TextReplaceOptions.

### visit {#visit-com.aspose.pdf.Document-}
Realiza una búsqueda de secciones y párrafos en el {@link Document} especificado.

### visit {#visit-com.aspose.pdf.Page-}
Realiza una búsqueda en la {@code Page} especificada.
