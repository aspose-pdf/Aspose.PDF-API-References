---
title: "FitBHExplicitDestination"
linktitle: "FitBHExplicitDestination"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein explizites Ziel dar, das die Seite anzeigt, wobei die vertikale Koordinate oben am oberen Rand des Fensters positioniert ist und der Seiteninhalt genau vergrößert wird."
type: docs
weight: 1530
url: /de/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Stellt ein explizites Ziel dar, das die Seite mit der vertikalen Koordinate top am oberen Rand des Fensters positioniert und den Seiteninhalt so vergrößert, dass die gesamte Breite ihres Begrenzungsrahmens in das Fenster passt. Ein Nullwert für top gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-int-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Erstellt die Instanz und initialisiert sie mit dem DOM-Seitenobjekt und dem oberen Parameter. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTop](#getTop--) | Gibt die vertikale Koordinate oben zurück, die am oberen Rand des Fensters positioniert ist. |
| [toString](#toString--) | Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitBH 100". |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
Erstellt ein entferntes explizites Ziel.

### FitBHExplicitDestination {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```

Erstellt ein entferntes explizites Ziel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Die Zielseitennummer des entfernten Dokuments. |
| oben |  | Die vertikale Koordinate oben, positioniert am oberen Rand des Fensters. |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
Erstellt die Instanz und initialisiert sie mit dem DOM-Seitenobjekt und dem oberen Parameter.

### getTop {#getTop--}
```
public double getTop()
```

Gibt die vertikale Koordinate oben zurück, die am oberen Rand des Fensters positioniert ist.

**Returns:**
double-Wert

### toString {#toString--}
```
public String toString()
```

Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitBH 100".

**Returns:**
Zeichenkettenwert, der den Objektzustand darstellt.
