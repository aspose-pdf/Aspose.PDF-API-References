---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe de base pour l'objet graphique sur la page."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Représente la classe de base pour l'objet graphique sur la page.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Ajoute l'élément actuel sur la page. S'il y a de nombreux éléments à ajouter, il vaut mieux utiliser Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | Libère toutes les ressources utilisées par la classe {@link GraphicElement}. |
| [getMatrix](#getMatrix--) | Obtient la matrice de l'élément graphique. La matrice est définie lors de la création de l'élément. Elle change lorsque SetPosition() est appelé. |
| [getOperators](#getOperators--) | Obtient une collection d'opérateurs représentant l'élément. |
| [getParent](#getParent--) | Obtient le {@link XFormPlacement} actuel dans lequel l'élément est situé. |
| [getPosition](#getPosition--) | Obtient ou définit la position dans l'espace de coordonnées actuel. Si Parent #getParent/#setParent(XFormPlacement) n'est pas nul, alors l'élément possède un espace de coordonnées xForm. |
| [getRectangle](#getRectangle--) | Obtient le rectangle englobant du {@link GraphicElement}. |
| [getSourcePage](#getSourcePage--) | Obtient la page à partir de laquelle l'élément graphique est extrait. |
| [remove](#remove--) | Supprime l'élément actuel de la page. S'il y a de nombreux éléments à supprimer, il vaut mieux utiliser Page#deleteGraphics(GraphicElementCollection). |
| [saveToSvg](#saveToSvg--) | Convertit l'élément en une image SVG unique. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Convertit l'élément en une image SVG unique. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Obtient ou définit la position dans l'espace de coordonnées actuel. Si Parent #getParent/#setParent(XFormPlacement) n'est pas nul, alors l'élément possède un espace de coordonnées xForm. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Ajoute l'élément actuel sur la page. S'il y a de nombreux éléments à ajouter, il vaut mieux utiliser Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

Libère toutes les ressources utilisées par la classe {@link GraphicElement}.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Obtient la matrice de l'élément graphique. La matrice est définie lors de la création de l'élément. Elle change lorsque SetPosition() est appelé.

**Returns:**
Instance de matrice

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Obtient une collection d'opérateurs représentant l'élément.

**Returns:**
Liste des instances d'Opérateur

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Obtient le {@link XFormPlacement} actuel dans lequel l'élément est situé.

**Returns:**
Instance XFormPlacement

### getPosition {#getPosition--}
```
public Point getPosition()
```

Obtient ou définit la position dans l'espace de coordonnées actuel. Si Parent #getParent/#setParent(XFormPlacement) n'est pas nul, alors l'élément possède un espace de coordonnées xForm.

**Returns:**
Instance de Point

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

Obtient le rectangle englobant du {@link GraphicElement}.

**Returns:**
Instance de Rectangle

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Obtient la page à partir de laquelle l'élément graphique est extrait.

**Returns:**
Instance de page

### remove {#remove--}
```
public final void remove()
```

Supprime l'élément actuel de la page. S'il y a de nombreux éléments à supprimer, il vaut mieux utiliser Page#deleteGraphics(GraphicElementCollection).

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Convertit l'élément en une image SVG unique.

**Returns:**
La chaîne SVG.

### saveToSvg {#saveToSvg-java.lang.String-}
Convertit l'élément en une image SVG unique.

**Returns:**
La chaîne SVG.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Obtient ou définit la position dans l'espace de coordonnées actuel. Si Parent #getParent/#setParent(XFormPlacement) n'est pas nul, alors l'élément possède un espace de coordonnées xForm.
