---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour s'adapter au rectangle spécifié par les coordonnées gauche, bas, droite et."
type: docs
weight: 1570
url: /fr/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que le rectangle spécifié par les coordonnées left, bottom, right et top tienne entièrement dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs de zoom horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur nulle pour l'un des paramètres peut entraîner un comportement imprévisible.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Crée une destination explicite distante. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | Crée une destination explicite distante. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Crée l'instance et l'initialise à partir de l'objet de page DOM et des paramètres visibles. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBottom](#getBottom--) | Obtient la coordonnée verticale inférieure du rectangle visible. |
| [getLeft](#getLeft--) | Obtient la coordonnée horizontale gauche du rectangle visible. |
| [getRight](#getRight--) | Obtient la coordonnée horizontale droite du rectangle visible. |
| [getTop](#getTop--) | Obtient la coordonnée verticale supérieure du rectangle visible. |
| [toString](#toString--) | Convertit l'état de l'objet en valeur de chaîne. Exemple : "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
Crée une destination explicite distante.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

Crée une destination explicite distante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page de destination du document distant. |
| gauche |  | Coordonnée horizontale gauche du rectangle visible. |
| bas |  | Coordonnée verticale inférieure du rectangle visible. |
| droite |  | Coordonnée horizontale droite du rectangle visible. |
| haut |  | Coordonnée verticale supérieure du rectangle visible. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
Crée l'instance et l'initialise à partir de l'objet de page DOM et des paramètres visibles.

### getBottom {#getBottom--}
```
public double getBottom()
```

Obtient la coordonnée verticale inférieure du rectangle visible.

**Returns:**
valeur double

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtient la coordonnée horizontale gauche du rectangle visible.

**Returns:**
valeur double

### getRight {#getRight--}
```
public double getRight()
```

Obtient la coordonnée horizontale droite du rectangle visible.

**Returns:**
valeur double

### getTop {#getTop--}
```
public double getTop()
```

Obtient la coordonnée verticale supérieure du rectangle visible.

**Returns:**
valeur double

### toString {#toString--}
```
public String toString()
```

Convertit l'état de l'objet en valeur de chaîne. Exemple : "1 FitR 100 200 300 400".

**Returns:**
Valeur chaîne représentant l'état de l'objet.
