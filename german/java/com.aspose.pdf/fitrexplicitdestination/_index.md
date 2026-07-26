---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein explizites Ziel dar, das die Seite mit ihrem Inhalt so vergrößert anzeigt, dass das durch die Koordinaten links, unten, rechts und angegebenen Rechteck passt."
type: docs
weight: 1570
url: /de/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

Stellt ein explizites Ziel dar, das die Seite mit ihrem Inhalt so vergrößert anzeigt, dass das durch die Koordinaten left, bottom, right und top definierte Rechteck vollständig sowohl horizontal als auch vertikal in das Fenster passt. Wenn die erforderlichen horizontalen und vertikalen Vergrößerungsfaktoren unterschiedlich sind, wird der kleinere der beiden verwendet, wobei das Rechteck in der anderen Dimension im Fenster zentriert wird. Ein Nullwert für einen der Parameter kann zu unvorhersehbarem Verhalten führen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Erstellt die Instanz und initialisiert sie anhand des DOM page object und sichtbarer Parameter. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBottom](#getBottom--) | Liefert die untere vertikale Koordinate des sichtbaren Rechtecks. |
| [getLeft](#getLeft--) | Liefert die linke horizontale Koordinate des sichtbaren Rechtecks. |
| [getRight](#getRight--) | Liefert die rechte horizontale Koordinate des sichtbaren Rechtecks. |
| [getTop](#getTop--) | Liefert die obere vertikale Koordinate des sichtbaren Rechtecks. |
| [toString](#toString--) | Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
Erstellt ein entferntes explizites Ziel.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

Erstellt ein entferntes explizites Ziel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Die Zielseitennummer des entfernten Dokuments. |
| links |  | Linke horizontale Koordinate des sichtbaren Rechtecks. |
| unten |  | Untere vertikale Koordinate des sichtbaren Rechtecks. |
| rechts |  | Rechte horizontale Koordinate des sichtbaren Rechtecks. |
| oben |  | Obere vertikale Koordinate des sichtbaren Rechtecks. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
Erstellt die Instanz und initialisiert sie anhand des DOM page object und sichtbarer Parameter.

### getBottom {#getBottom--}
```
public double getBottom()
```

Liefert die untere vertikale Koordinate des sichtbaren Rechtecks.

**Returns:**
double-Wert

### getLeft {#getLeft--}
```
public double getLeft()
```

Liefert die linke horizontale Koordinate des sichtbaren Rechtecks.

**Returns:**
double-Wert

### getRight {#getRight--}
```
public double getRight()
```

Liefert die rechte horizontale Koordinate des sichtbaren Rechtecks.

**Returns:**
double-Wert

### getTop {#getTop--}
```
public double getTop()
```

Liefert die obere vertikale Koordinate des sichtbaren Rechtecks.

**Returns:**
double-Wert

### toString {#toString--}
```
public String toString()
```

Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitR 100 200 300 400".

**Returns:**
Zeichenkettenwert, der den Objektzustand darstellt.
