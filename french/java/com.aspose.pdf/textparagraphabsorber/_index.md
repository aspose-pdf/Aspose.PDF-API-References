---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un objet absorbeur de paragraphes de texte. Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextParagraphAbsorber.TextParagraphs}."
type: docs
weight: 5220
url: /fr/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

Représente un objet absorbeur de paragraphes de texte. Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextParagraphAbsorber.TextParagraphs}.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> Initialise une nouvelle instance de {@code TextParagraphAbsorber} avec la collection de rectangles. </p> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getRectangles](#getRectangles--) | Obtient les rectangles que {@code TextParagraphAbsorber} utilise pour rechercher des paragraphes de texte dans le document PDF ou la page. |
| [getTextParagraphs](#getTextParagraphs--) | Obtient la collection des occurrences de recherche présentées avec des objets {@code TextParagraph}. |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | Définit les rectangles que {@code TextParagraphAbsorber} utilise pour rechercher des paragraphes de texte dans le document PDF ou la page. |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Définit la collection des occurrences de recherche présentées avec des objets {@code TextParagraph}. |
| [visit](#visit-com.aspose.pdf.Page-) | Effectue la recherche sur la page spécifiée. |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> Initialise une nouvelle instance de {@code TextParagraphAbsorber} avec la collection de rectangles. </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

Obtient les rectangles que {@code TextParagraphAbsorber} utilise pour rechercher des paragraphes de texte dans le document PDF ou la page.

**Returns:**
tableau de rectangles

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

Obtient la collection des occurrences de recherche présentées avec des objets {@code TextParagraph}.

**Returns:**
Valeur TextParagraphCollection

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
Définit les rectangles que {@code TextParagraphAbsorber} utilise pour rechercher des paragraphes de texte dans le document PDF ou la page.

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
Définit la collection des occurrences de recherche présentées avec des objets {@code TextParagraph}.

### visit {#visit-com.aspose.pdf.Page-}
Effectue la recherche sur la page spécifiée.
