---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una sección de marcado: la región rectangular de una página que contiene texto y puede dividirse visualmente de otros bloques de texto."
type: docs
weight: 2890
url: /es/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

Representa una sección de marcado: la región rectangular de una página que contiene texto y puede dividirse visualmente de otros bloques de texto.

## Métodos

| Método | Descripción |
| --- | --- |
| [getFragments](#getFragments--) | <p> Colección de objetos {@code TextFragment} no vacíos que están dentro de la sección. </p><hr> El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, propiedades del texto, y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc). |
| [getParagraphs](#getParagraphs--) | Colección de objetos {@code MarkupParagraph} que están dentro de la sección. |
| [getRectangle](#getRectangle--) | Rectángulo de la sección |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Colección de objetos {@code TextFragment} no vacíos que están dentro de la sección. </p><hr> El objeto {@code TextFragment} proporciona acceso al texto de la ocurrencia de búsqueda, propiedades del texto, y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc).

**Returns:**
lista de instancias de TextFragment

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Colección de objetos {@code MarkupParagraph} que están dentro de la sección.

**Returns:**
lista de instancias de MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Rectángulo de la sección

**Returns:**
Instancia de Rectangle
