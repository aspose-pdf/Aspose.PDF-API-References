---
title: "FitBVExplicitDestination"
linktitle: "FitBVExplicitDestination"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein explizites Ziel dar, das die Seite anzeigt, wobei die horizontale Koordinate links am linken Rand des Fensters positioniert ist und der Seiteninhalt gerade vergrößert wird."
type: docs
weight: 1540
url: /de/java/com.aspose.pdf/fitbvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBVExplicitDestination extends ExplicitDestination
```

Stellt ein explizites Ziel dar, das die Seite mit der horizontalen Koordinate left am linken Rand des Fensters positioniert und den Seiteninhalt so vergrößert, dass die gesamte Höhe ihres Begrenzungsrahmens in das Fenster passt. Ein Nullwert für left gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-int-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Page-double-) | Erstellt die Instanz und initialisiert sie mit dem DOM‑Seitenobjekt und dem linken Parameter. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLeft](#getLeft--) | Ruft die horizontale Koordinate ab, die links am linken Rand des Fensters positioniert ist. |
| [toString](#toString--) | Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitBV 100". |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-}
Erstellt ein entferntes explizites Ziel.

### FitBVExplicitDestination {#FitBVExplicitDestination-int-double-}
```
public FitBVExplicitDestination(int pageNumber, double left)
```

Erstellt ein entferntes explizites Ziel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Die Zielseitennummer des entfernten Dokuments. |
| links |  | Die horizontale Koordinate, die links am linken Rand des Fensters positioniert ist. |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Page-double-}
Erstellt die Instanz und initialisiert sie mit dem DOM‑Seitenobjekt und dem linken Parameter.

### getLeft {#getLeft--}
```
public double getLeft()
```

Ruft die horizontale Koordinate ab, die links am linken Rand des Fensters positioniert ist.

**Returns:**
double-Wert

### toString {#toString--}
```
public String toString()
```

Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitBV 100".

**Returns:**
Zeichenkettenwert, der den Objektzustand darstellt.
