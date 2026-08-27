---
title: "FitBHExplicitDestination"
linktitle: "FitBHExplicitDestination"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en explicit destination som visar sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och sidans innehåll förstoras precis."
type: docs
weight: 1530
url: /sv/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Representerar en explicit destination som visar sidan med den vertikala koordinaten top placerad vid fönstrets övre kant och sidans innehåll förstorat precis tillräckligt för att den hela bredden av dess omgivningsruta får plats i fönstret. Ett null-värde för top anger att det aktuella värdet för den parametern ska behållas oförändrat.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Skapar en fjärrexplicit destination. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-int-double-) | Skapar en fjärrexplicit destination. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Skapar instansen och initierar den med DOM-sidobjektet och top‑parametern. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTop](#getTop--) | Hämtar den vertikala koordinaten top placerad vid fönstrets övre kant. |
| [toString](#toString--) | Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 FitBH 100". |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
Skapar en fjärrexplicit destination.

### FitBHExplicitDestination {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```

Skapar en fjärrexplicit destination.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Destinationssidnumret för fjärrdokumentet. |
| övre |  | Den vertikala koordinaten top placerad vid fönstrets övre kant. |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
Skapar instansen och initierar den med DOM-sidobjektet och top‑parametern.

### getTop {#getTop--}
```
public double getTop()
```

Hämtar den vertikala koordinaten top placerad vid fönstrets övre kant.

**Returns:**
double-värde

### toString {#toString--}
```
public String toString()
```

Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 FitBH 100".

**Returns:**
Strängvärde som representerar objektets tillstånd.
