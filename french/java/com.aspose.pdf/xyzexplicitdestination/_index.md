---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente la destination explicite qui affiche la page avec les coordonnées (gauche, haut) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page."
type: docs
weight: 5800
url: /fr/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> Représente une destination explicite qui affiche la page avec les coordonnées (gauche, haut) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur zoom. Une valeur nulle pour l'un des paramètres gauche, haut ou zoom indique que la valeur actuelle de ce paramètre doit être conservée inchangée. Une valeur de zoom de 0 a la même signification qu'une valeur nulle. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Crée une destination explicite distante. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | Crée une destination explicite distante. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Crée l'instance et l'initialise à partir de l'objet de page DOM et des paramètres visibles. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Crée une destination vers l'emplacement spécifié de la page en tenant compte de la rotation de la page si nécessaire. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Crée une destination vers la page spécifiée. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Crée une destination vers le coin supérieur gauche de la page spécifiée. |
| [getLeft](#getLeft--) | Obtient la coordonnée horizontale gauche du coin supérieur gauche de la fenêtre. |
| [getTop](#getTop--) | Obtient la coordonnée verticale supérieure du coin supérieur gauche de la fenêtre. |
| [getZoom](#getZoom--) | Obtient le facteur de zoom. |
| [toString](#toString--) | Convertit l'état de l'objet en valeur chaîne. Exemple : "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
Crée une destination explicite distante.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

Crée une destination explicite distante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page de destination du document distant. |
| gauche |  | Coordonnée horizontale gauche du coin supérieur gauche de la fenêtre. |
| haut |  | Coordonnée verticale supérieure du coin supérieur gauche de la fenêtre. |
| zoom |  | Facteur de zoom. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
Crée l'instance et l'initialise à partir de l'objet de page DOM et des paramètres visibles.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
Crée une destination vers l'emplacement spécifié de la page en tenant compte de la rotation de la page si nécessaire.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
Crée une destination vers la page spécifiée.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
Crée une destination vers le coin supérieur gauche de la page spécifiée.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtient la coordonnée horizontale gauche du coin supérieur gauche de la fenêtre.

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

Obtient la coordonnée verticale supérieure du coin supérieur gauche de la fenêtre.

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

Obtient le facteur de zoom.

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

Convertit l'état de l'objet en valeur chaîne. Exemple : "1 XYZ 100 200 3".

**Returns:**
Valeur chaîne représentant l'état de l'objet.
