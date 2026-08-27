---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une cellule de tableau qui existe sur la page"
type: docs
weight: 10
url: /fr/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

Représente une cellule de tableau qui existe sur la page

## Méthodes

| Méthode | Description |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | Compare l'objet AbsorbedCell actuel avec un autre objet AbsorbedCell et renvoie un entier qui indique si l'objet actuel précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet. |
| [getBorderInfo](#getBorderInfo--) | Renvoie les informations de bordure pour la cellule lorsque la propriété FlowEngine.TableAbsorber.UseFlowEngine est définie sur true. |
| [getColSpan](#getColSpan--) | Renvoie le nombre de colonnes que la cellule doit occuper lorsque la propriété TableAbsorber.UseFlowEngine est définie sur true. |
| [getRectangle](#getRectangle--) | Obtient le rectangle qui décrit la position de la cellule sur la page |
| [getTextFragments](#getTextFragments--) | Obtient la collection d'objets {@code TextFragment} qui décrit le texte contenu dans la cellule |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
Compare l'objet AbsorbedCell actuel avec un autre objet AbsorbedCell et renvoie un entier qui indique si l'objet actuel précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

Renvoie les informations de bordure pour la cellule lorsque la propriété FlowEngine.TableAbsorber.UseFlowEngine est définie sur true.

**Returns:**
Instance BorderInfo

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Renvoie le nombre de colonnes que la cellule doit occuper lorsque la propriété TableAbsorber.UseFlowEngine est définie sur true.

**Returns:**
valeur int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle qui décrit la position de la cellule sur la page

**Returns:**
objet Rectangle

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

Obtient la collection d'objets {@code TextFragment} qui décrit le texte contenu dans la cellule

**Returns:**
Objet TextFragmentCollection
