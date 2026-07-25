---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le markup de page est représenté par des collections de {@code MarkupSection} et {@code MarkupParagraph}."
type: docs
weight: 3420
url: /fr/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

Le markup de page est représenté par des collections de {@code MarkupSection} et {@code MarkupParagraph}.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getNumber](#getNumber--) | Obtient le numéro de page traité. |
| [getParagraphs](#getParagraphs--) | Obtient la collection de {@code MarkupParagraph} qui a été trouvée sur la page. |
| [getRectangle](#getRectangle--) | Obtient le rectangle de page traité. |
| [getSections](#getSections--) | Obtient la collection de {@code MarkupSection} qui a été trouvée sur la page. |
| [getTextFragments](#getTextFragments--) | <p> Obtient la collection de {@code TextFragment} qui a été trouvée sur la page. </p><hr> L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence recherchée, aux propriétés du texte, et permet d'éditer le texte et de changer l'état du texte (police, taille de police, couleur, etc). |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente. |

### getNumber {#getNumber--}
```
public int getNumber()
```

Obtient le numéro de page traité.

**Returns:**
valeur int

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Obtient la collection de {@code MarkupParagraph} qui a été trouvée sur la page.

**Returns:**
Liste d'instances de MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle de page traité.

**Returns:**
objet Rectangle

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

Obtient la collection de {@code MarkupSection} qui a été trouvée sur la page.

**Returns:**
Liste d'instances de MarkupSection

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> Obtient la collection de {@code TextFragment} qui a été trouvée sur la page. </p><hr> L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence recherchée, aux propriétés du texte, et permet d'éditer le texte et de changer l'état du texte (police, taille de police, couleur, etc).

**Returns:**
Liste d'instances de TextFragment

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente.

**Returns:**
valeur booléenne

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
