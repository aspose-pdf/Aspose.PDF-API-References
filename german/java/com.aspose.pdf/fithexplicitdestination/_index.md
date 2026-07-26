---
title: "FitHExplicitDestination"
linktitle: "FitHExplicitDestination"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein explizites Ziel dar, das die Seite anzeigt, wobei die vertikale Koordinate oben am oberen Rand des Fensters positioniert ist und der Seiteninhalt genau vergrößert wird."
type: docs
weight: 1560
url: /de/java/com.aspose.pdf/fithexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitHExplicitDestination extends ExplicitDestination
```

Stellt ein explizites Ziel dar, das die Seite mit der vertikalen Koordinate top am oberen Rand des Fensters positioniert und den Seiteninhalt so vergrößert, dass die gesamte Breite der Seite in das Fenster passt. Ein Nullwert für top gibt an, dass der aktuelle Wert dieses Parameters unverändert beibehalten wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Document-int-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitHExplicitDestination](#FitHExplicitDestination-int-double-) | Erstellt ein entferntes explizites Ziel. |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Page-double-) | Erstellt die Instanz und initialisiert sie mit dem DOM-Seitenobjekt und dem oberen Parameter. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTop](#getTop--) | Gibt die vertikale Koordinate oben zurück, die am oberen Rand des Fensters positioniert ist. |
| [toString](#toString--) | Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitH 100". |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Document-int-double-}
Erstellt ein entferntes explizites Ziel.

### FitHExplicitDestination {#FitHExplicitDestination-int-double-}
```
public FitHExplicitDestination(int pageNumber, double top)
```

Erstellt ein entferntes explizites Ziel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Die Zielseitennummer des entfernten Dokuments. |
| oben |  | Die vertikale Koordinate oben, positioniert am oberen Rand des Fensters. |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Page-double-}
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

Konvertiert den Objektzustand in einen Zeichenkettenwert. Beispiel: "1 FitH 100".

**Returns:**
Zeichenkettenwert, der den Objektzustand darstellt.
