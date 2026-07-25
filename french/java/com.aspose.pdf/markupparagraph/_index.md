---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un paragraphe."
type: docs
weight: 2880
url: /fr/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

Représente un paragraphe.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | Liste des numéros de page sur lesquels le paragraphe se poursuit. Elle correspondra à la page où le paragraphe a commencé s'il continue dans la colonne suivante sur la même page. |
| [getFragments](#getFragments--) | <p> Collection d'objets {@code TextFragment} non vides du paragraphe. </p><hr> L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence de recherche, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc). |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> Lignes du paragraphe. Chaque ligne est représentée par une liste de fragments de texte. </p><hr> L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence de recherche, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc). |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | Points du polygone qui décrit le paragraphe. Le point de départ est le coin inférieur gauche du paragraphe. Les points suivants sont dans l'ordre anti-horaire. |
| [getSecondaryPoints](#getSecondaryPoints--) | Points du polygone secondaire qui décrit la continuation du paragraphe. Il ne sera pas nul si le paragraphe se poursuit dans la colonne suivante ou sur la page suivante. Le point de départ est le coin inférieur gauche du paragraphe. Les points suivants sont dans l'ordre anti-horaire. |
| [getText](#getText--) | Obtient l'objet texte {@code string} que représente l'objet {@code MarkupParagraph}. |
| [setText](#setText-java.lang.String-) | Obtient ou définit le texte du paragraphe. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

Liste des numéros de page sur lesquels le paragraphe se poursuit. Elle correspondra à la page où le paragraphe a commencé s'il continue dans la colonne suivante sur la même page.

**Returns:**
liste d'Integer

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Collection d'objets {@code TextFragment} non vides du paragraphe. </p><hr> L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence de recherche, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc).

**Returns:**
liste d'instances TextFragment

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> Lignes du paragraphe. Chaque ligne est représentée par une liste de fragments de texte. </p><hr> L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence de recherche, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc).

**Returns:**
liste d'instances TextFragment

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Points du polygone qui décrit le paragraphe. Le point de départ est le coin inférieur gauche du paragraphe. Les points suivants sont dans l'ordre anti-horaire.

**Returns:**
tableau d'instances de Point

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

Points du polygone secondaire qui décrit la continuation du paragraphe. Il ne sera pas nul si le paragraphe se poursuit dans la colonne suivante ou sur la page suivante. Le point de départ est le coin inférieur gauche du paragraphe. Les points suivants sont dans l'ordre anti-horaire.

**Returns:**
liste de Point[]

### getText {#getText--}
```
public String getText()
```

Obtient l'objet texte {@code string} que représente l'objet {@code MarkupParagraph}.

**Returns:**
valeur String

### setText {#setText-java.lang.String-}
Obtient ou définit le texte du paragraphe.
