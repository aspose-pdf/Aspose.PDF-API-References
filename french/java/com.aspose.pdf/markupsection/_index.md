---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une section de balisage – la région rectangulaire d’une page qui contient du texte et qui peut être visuellement séparée d’autres blocs de texte."
type: docs
weight: 2890
url: /fr/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

Représente une section de balisage – la région rectangulaire d’une page qui contient du texte et qui peut être visuellement séparée d’autres blocs de texte.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFragments](#getFragments--) | <p> Collection d'objets {@code TextFragment} non vides qui se trouvent dans la section. </p><hr> L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence recherchée, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc). |
| [getParagraphs](#getParagraphs--) | Collection d'objets {@code MarkupParagraph} qui se trouvent dans la section. |
| [getRectangle](#getRectangle--) | Rectangle de la section |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Collection d'objets {@code TextFragment} non vides qui se trouvent dans la section. </p><hr> L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence recherchée, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc).

**Returns:**
liste d'instances TextFragment

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Collection d'objets {@code MarkupParagraph} qui se trouvent dans la section.

**Returns:**
liste d'instances MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Rectangle de la section

**Returns:**
Instance de Rectangle
