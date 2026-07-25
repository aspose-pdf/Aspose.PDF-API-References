---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une destination explicite qui affiche la page avec la coordonnée horizontale gauche positionnée au bord gauche de la fenêtre et le contenu de la page simplement agrandi."
type: docs
weight: 1580
url: /fr/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

Représente une destination explicite qui affiche la page avec la coordonnée horizontale left positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que la hauteur entière de la page tienne dans la fenêtre. Une valeur nulle pour left indique que la valeur actuelle de ce paramètre doit être conservée inchangée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | Crée une destination explicite distante. |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | Crée une destination explicite distante. |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | Crée l’instance et l’initialise à partir de l’objet de page DOM et du paramètre left. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getLeft](#getLeft--) | Obtient la coordonnée horizontale gauche positionnée au bord gauche de la fenêtre. |
| [toString](#toString--) | Convertit l'état de l'objet en valeur de chaîne. Exemple : "1 FitV 100". |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
Crée une destination explicite distante.

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

Crée une destination explicite distante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page de destination du document distant. |
| gauche |  | La coordonnée horizontale gauche positionnée au bord gauche de la fenêtre. |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
Crée l’instance et l’initialise à partir de l’objet de page DOM et du paramètre left.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtient la coordonnée horizontale gauche positionnée au bord gauche de la fenêtre.

**Returns:**
valeur double

### toString {#toString--}
```
public String toString()
```

Convertit l'état de l'objet en valeur de chaîne. Exemple : "1 FitV 100".

**Returns:**
Valeur chaîne représentant l'état de l'objet.
