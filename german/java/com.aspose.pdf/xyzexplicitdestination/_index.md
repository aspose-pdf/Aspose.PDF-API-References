---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt ein explizites Ziel dar, das die Seite mit den Koordinaten (left, top) an der oberen linken Ecke des Fensters und den Inhalt der Seite anzeigt."
type: docs
weight: 5800
url: /de/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> Stellt ein explizites Ziel dar, das die Seite mit den Koordinaten (left, top) an der oberen linken Ecke des Fensters anzeigt und den Seiteninhalt um den Zoom‑Faktor vergrößert. Ein Nullwert für einen der Parameter left, top oder zoom gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird. Ein Zoom‑Wert von 0 hat die gleiche Bedeutung wie ein Nullwert. </p> <hr> <p> Document doc = new Document(\"example.pdf\"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Erstellt ein entferntes explizites Ziel. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | Erstellt ein entferntes explizites Ziel. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Erstellt die Instanz und initialisiert sie anhand des DOM page object und sichtbarer Parameter. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Erstelle ein Ziel für den angegebenen Ort der Seite unter Berücksichtigung der Seitendrehung, falls erforderlich. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Erstelle ein Ziel für die angegebene Seite. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Erstelle ein Ziel für die obere linke Ecke der angegebenen Seite. |
| [getLeft](#getLeft--) | Liefert die linke horizontale Koordinate der oberen linken Ecke des Fensters. |
| [getTop](#getTop--) | Liefert die obere vertikale Koordinate der oberen linken Ecke des Fensters. |
| [getZoom](#getZoom--) | Liefert den Zoomfaktor. |
| [toString](#toString--) | Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
Erstellt ein entferntes explizites Ziel.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

Erstellt ein entferntes explizites Ziel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Die Zielseitennummer des entfernten Dokuments. |
| links |  | Linke horizontale Koordinate der oberen linken Ecke des Fensters. |
| oben |  | Obere vertikale Koordinate der oberen linken Ecke des Fensters. |
| zoom |  | Zoomfaktor. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
Erstellt die Instanz und initialisiert sie anhand des DOM page object und sichtbarer Parameter.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
Erstelle ein Ziel für den angegebenen Ort der Seite unter Berücksichtigung der Seitendrehung, falls erforderlich.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
Erstelle ein Ziel für die angegebene Seite.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
Erstelle ein Ziel für die obere linke Ecke der angegebenen Seite.

### getLeft {#getLeft--}
```
public double getLeft()
```

Liefert die linke horizontale Koordinate der oberen linken Ecke des Fensters.

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

Liefert die obere vertikale Koordinate der oberen linken Ecke des Fensters.

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

Liefert den Zoomfaktor.

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 XYZ 100 200 3".

**Returns:**
Zeichenkettenwert, der den Objektzustand darstellt.
