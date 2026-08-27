---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein explizites Ziel dar, das die Seite anzeigt, wobei die horizontale Koordinate links am linken Rand des Fensters positioniert ist und der Seiteninhalt gerade vergrößert wird."
type: docs
weight: 1580
url: /de/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

Stellt ein explizites Ziel dar, das die Seite anzeigt, wobei die horizontale Koordinate links am linken Rand des Fensters positioniert ist und der Inhalt der Seite so weit vergrößert wird, dass die gesamte Höhe der Seite in das Fenster passt. Ein Nullwert für links gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | Erstellt die Instanz und initialisiert sie mit dem DOM‑Seitenobjekt und dem linken Parameter. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLeft](#getLeft--) | Ruft die horizontale Koordinate ab, die links am linken Rand des Fensters positioniert ist. |
| [toString](#toString--) | Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitV 100". |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
Erstellt ein entferntes explizites Ziel.

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

Erstellt ein entferntes explizites Ziel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Die Zielseitennummer des entfernten Dokuments. |
| links |  | Die horizontale Koordinate, die links am linken Rand des Fensters positioniert ist. |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
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

Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitV 100".

**Returns:**
Zeichenkettenwert, der den Objektzustand darstellt.
