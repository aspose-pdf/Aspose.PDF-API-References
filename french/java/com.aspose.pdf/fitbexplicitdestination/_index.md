---
title: "FitBExplicitDestination"
linktitle: "FitBExplicitDestination"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que sa boîte englobante tienne entièrement dans la fenêtre à la fois horizontalement et."
type: docs
weight: 1520
url: /fr/java/com.aspose.pdf/fitbexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBExplicitDestination extends ExplicitDestination
```

Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que sa boîte englobante tienne entièrement dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs de zoom horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant la boîte englobante dans la fenêtre dans l'autre dimension.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Document-int-) | Crée une destination explicite distante. |
| [FitBExplicitDestination](#FitBExplicitDestination-int-) | Crée une destination explicite distante. |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Page-) | Crée l'instance et l'initialise à l'aide d'un objet de page DOM. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [toString](#toString--) | Convertit l'état de l'objet en valeur chaîne. Exemple : "1 FitB". |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Document-int-}
Crée une destination explicite distante.

### FitBExplicitDestination {#FitBExplicitDestination-int-}
```
public FitBExplicitDestination(int pageNumber)
```

Crée une destination explicite distante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page de destination du document distant. |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Page-}
Crée l'instance et l'initialise à l'aide d'un objet de page DOM.

### toString {#toString--}
```
public String toString()
```

Convertit l'état de l'objet en valeur chaîne. Exemple : "1 FitB".

**Returns:**
Valeur chaîne représentant l'état de l'objet.
