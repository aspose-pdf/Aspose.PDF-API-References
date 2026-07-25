---
title: "FitHExplicitDestination"
linktitle: "FitHExplicitDestination"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une destination explicite qui affiche la page avec la coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre et le contenu de la page simplement agrandi."
type: docs
weight: 1560
url: /fr/java/com.aspose.pdf/fithexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitHExplicitDestination extends ExplicitDestination
```

Représente une destination explicite qui affiche la page avec la coordonnée verticale top positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que la largeur entière de la page tienne dans la fenêtre. Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée inchangée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Document-int-double-) | Crée une destination explicite distante. |
| [FitHExplicitDestination](#FitHExplicitDestination-int-double-) | Crée une destination explicite distante. |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Page-double-) | Crée l'instance et l'initialise à l'aide de l'objet de page DOM et du paramètre top. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getTop](#getTop--) | Obtient la coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre. |
| [toString](#toString--) | Convertit l'état de l'objet en valeur de chaîne. Exemple : "1 FitH 100". |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Document-int-double-}
Crée une destination explicite distante.

### FitHExplicitDestination {#FitHExplicitDestination-int-double-}
```
public FitHExplicitDestination(int pageNumber, double top)
```

Crée une destination explicite distante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page de destination du document distant. |
| haut |  | La coordonnée verticale supérieure positionnée au bord supérieur de la fenêtre. |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Page-double-}
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

Convertit l'état de l'objet en valeur de chaîne. Exemple : "1 FitH 100".

**Returns:**
Valeur chaîne représentant l'état de l'objet.
