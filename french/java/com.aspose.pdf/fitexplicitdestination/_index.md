---
title: "FitExplicitDestination"
linktitle: "FitExplicitDestination"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour faire tenir la page entière dans la fenêtre, à la fois horizontalement et verticalement. Si le."
type: docs
weight: 1550
url: /fr/java/com.aspose.pdf/fitexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitExplicitDestination extends ExplicitDestination
```

Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que la page entière tienne dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs de zoom horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant la page dans la fenêtre dans l'autre dimension.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Document-int-) | Crée une destination explicite distante. |
| [FitExplicitDestination](#FitExplicitDestination-int-) | Crée une destination explicite distante. |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Page-) | Crée une destination explicite locale. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [toString](#toString--) | Convertit l'état de l'objet en valeur chaîne. Exemple : "1 Fit". |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Document-int-}
Crée une destination explicite distante.

### FitExplicitDestination {#FitExplicitDestination-int-}
```
public FitExplicitDestination(int pageNumber)
```

Crée une destination explicite distante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page de destination du document distant. |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Page-}
Crée une destination explicite locale.

### toString {#toString--}
```
public String toString()
```

Convertit l'état de l'objet en valeur chaîne. Exemple : "1 Fit".

**Returns:**
Valeur chaîne représentant l'état de l'objet.
