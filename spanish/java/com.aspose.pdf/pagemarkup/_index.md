---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Marcado de página representado por colecciones de {@code MarkupSection} y {@code MarkupParagraph}."
type: docs
weight: 3420
url: /es/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

Marcado de página representado por colecciones de {@code MarkupSection} y {@code MarkupParagraph}.

## Métodos

| Método | Descripción |
| --- | --- |
| [getNumber](#getNumber--) | Obtiene el número de página procesado. |
| [getParagraphs](#getParagraphs--) | Obtiene la colección de {@code MarkupParagraph} que se encontró en la página. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo de página procesado. |
| [getSections](#getSections--) | Obtiene la colección de {@code MarkupSection} que se encontró en la página. |
| [getTextFragments](#getTextFragments--) | <p> Obtiene la colección de {@code TextFragment} que se encontró en la página. </p><hr> El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, propiedades del texto, y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc). |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Obtiene o establece el valor que indica si las líneas de texto iniciales de una sección siguiente pueden ser tratadas como continuación del último párrafo de una sección anterior. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Obtiene o establece el valor que indica si las líneas de texto iniciales de una sección siguiente pueden ser tratadas como continuación del último párrafo de una sección anterior. |

### getNumber {#getNumber--}
```
public int getNumber()
```

Obtiene el número de página procesado.

**Returns:**
valor int

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Obtiene la colección de {@code MarkupParagraph} que se encontró en la página.

**Returns:**
Lista de instancias de MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo de página procesado.

**Returns:**
objeto Rectangle

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

Obtiene la colección de {@code MarkupSection} que se encontró en la página.

**Returns:**
Lista de instancias de MarkupSection

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> Obtiene la colección de {@code TextFragment} que se encontró en la página. </p><hr> El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, propiedades del texto, y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc).

**Returns:**
Lista de instancias de TextFragment

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
