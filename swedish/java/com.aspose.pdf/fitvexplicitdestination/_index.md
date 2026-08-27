---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en explicit destination som visar sidan med den horisontella koordinaten vänster placerad vid fönstrets vänstra kant och sidans innehåll förstorad precis."
type: docs
weight: 1580
url: /sv/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

Representerar en explicit destination som visar sidan med den horisontella koordinaten left placerad vid fönstrets vänstra kant och sidans innehåll förstorat precis tillräckligt för att hela sidans höjd får plats i fönstret. Ett null-värde för left anger att det aktuella värdet för den parametern ska behållas oförändrat.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | Skapar en fjärrexplicit destination. |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | Skapar en fjärrexplicit destination. |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | Skapar instansen och initierar den med DOM‑sidobjektet och vänster‑parametern. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLeft](#getLeft--) | Hämtar den horisontella koordinaten vänster placerad vid fönstrets vänstra kant. |
| [toString](#toString--) | Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 FitV 100". |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
Skapar en fjärrexplicit destination.

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

Skapar en fjärrexplicit destination.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Destinationssidnumret för fjärrdokumentet. |
| vänster |  | Den horisontella koordinaten vänster placerad vid fönstrets vänstra kant. |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
Skapar instansen och initierar den med DOM‑sidobjektet och vänster‑parametern.

### getLeft {#getLeft--}
```
public double getLeft()
```

Hämtar den horisontella koordinaten vänster placerad vid fönstrets vänstra kant.

**Returns:**
double-värde

### toString {#toString--}
```
public String toString()
```

Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 FitV 100".

**Returns:**
Strängvärde som representerar objektets tillstånd.
