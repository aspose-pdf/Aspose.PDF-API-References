---
title: "FitBHExplicitDestination"
linktitle: "FitBHExplicitDestination"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une destination explicite qui affiche la page avec la coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre et le contenu de la page simplement agrandi."
type: docs
weight: 1530
url: /fr/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Représente une destination explicite qui affiche la page avec la coordonnée verticale top positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que la largeur entière de sa boîte englobante tienne dans la fenêtre. Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée inchangée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Crée une destination explicite distante. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-int-double-) | Crée une destination explicite distante. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Crée l'instance et l'initialise à l'aide de l'objet de page DOM et du paramètre top. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getTop](#getTop--) | Obtient la coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre. |
| [toString](#toString--) | Convertit l'état de l'objet en valeur chaîne. Exemple : "1 FitBH 100". |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
Crée une destination explicite distante.

### FitBHExplicitDestination {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```

Crée une destination explicite distante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page de destination du document distant. |
| haut |  | La coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre. |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
Crée l'instance et l'initialise à l'aide de l'objet de page DOM et du paramètre top.

### getTop {#getTop--}
```
public double getTop()
```

Obtient la coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre.

**Returns:**
valeur double

### toString {#toString--}
```
public String toString()
```

Convertit l'état de l'objet en valeur chaîne. Exemple : "1 FitBH 100".

**Returns:**
Valeur chaîne représentant l'état de l'objet.
