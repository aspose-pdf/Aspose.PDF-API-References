---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un objeto absorbente de párrafos de texto. Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda mediante la colección {@code TextParagraphAbsorber.TextParagraphs}."
type: docs
weight: 5220
url: /es/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

Representa un objeto absorbente de párrafos de texto. Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda mediante la colección {@code TextParagraphAbsorber.TextParagraphs}.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> Inicializa una nueva instancia de {@code TextParagraphAbsorber} con la colección de rectángulos. </p> |

## Métodos

| Método | Descripción |
| --- | --- |
| [getRectangles](#getRectangles--) | Obtiene los rectángulos que {@code TextParagraphAbsorber} utiliza para buscar párrafos de texto en el documento PDF o página. |
| [getTextParagraphs](#getTextParagraphs--) | Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos {@code TextParagraph}. |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | Establece los rectángulos que {@code TextParagraphAbsorber} usa para buscar párrafos de texto en el documento PDF o página. |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Establece la colección de ocurrencias de búsqueda que se presentan con objetos {@code TextParagraph}. |
| [visit](#visit-com.aspose.pdf.Page-) | Realiza la búsqueda en la página especificada. |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> Inicializa una nueva instancia de {@code TextParagraphAbsorber} con la colección de rectángulos. </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

Obtiene los rectángulos que {@code TextParagraphAbsorber} utiliza para buscar párrafos de texto en el documento PDF o página.

**Returns:**
matriz de rectángulos

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos {@code TextParagraph}.

**Returns:**
valor de TextParagraphCollection

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
Establece los rectángulos que {@code TextParagraphAbsorber} usa para buscar párrafos de texto en el documento PDF o página.

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
Establece la colección de ocurrencias de búsqueda que se presentan con objetos {@code TextParagraph}.

### visit {#visit-com.aspose.pdf.Page-}
Realiza la búsqueda en la página especificada.
