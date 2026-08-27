---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en explicit destination som visar sidan med dess innehåll förstorat precis tillräckligt för att passa rektangeln som specificeras av koordinaterna vänster, botten, höger och."
type: docs
weight: 1570
url: /sv/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

Representerar en explicit destination som visar sidan med dess innehåll förstorat precis tillräckligt för att rektangeln som anges av koordinaterna left, bottom, right och top får plats helt i fönstret både horisontellt och vertikalt. Om de erforderliga horisontella och vertikala förstoringfaktorerna är olika, använd den mindre av de två och centrera rektangeln i fönstret i den andra dimensionen. Ett null-värde för någon av parametrarna kan leda till oförutsägbart beteende.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Skapar en fjärrexplicit destination. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | Skapar en fjärrexplicit destination. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Skapar instansen och initierar den med DOM‑sidobjektet och synliga parametrar. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBottom](#getBottom--) | Hämtar den vertikala bottenkoordinaten för den synliga rektangeln. |
| [getLeft](#getLeft--) | Hämtar den horisontella vänsterkoordinaten för den synliga rektangeln. |
| [getRight](#getRight--) | Hämtar den horisontella högra koordinaten för den synliga rektangeln. |
| [getTop](#getTop--) | Hämtar den vertikala toppkoordinaten för den synliga rektangeln. |
| [toString](#toString--) | Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
Skapar en fjärrexplicit destination.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

Skapar en fjärrexplicit destination.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Destinationssidnumret för fjärrdokumentet. |
| vänster |  | Vänster horisontell koordinat för den synliga rektangeln. |
| nedre |  | Bottenvertikal koordinat för den synliga rektangeln. |
| höger |  | Höger horisontell koordinat för den synliga rektangeln. |
| övre |  | Toppvertikal koordinat för den synliga rektangeln. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
Skapar instansen och initierar den med DOM‑sidobjektet och synliga parametrar.

### getBottom {#getBottom--}
```
public double getBottom()
```

Hämtar den vertikala bottenkoordinaten för den synliga rektangeln.

**Returns:**
double-värde

### getLeft {#getLeft--}
```
public double getLeft()
```

Hämtar den horisontella vänsterkoordinaten för den synliga rektangeln.

**Returns:**
double-värde

### getRight {#getRight--}
```
public double getRight()
```

Hämtar den horisontella högra koordinaten för den synliga rektangeln.

**Returns:**
double-värde

### getTop {#getTop--}
```
public double getTop()
```

Hämtar den vertikala toppkoordinaten för den synliga rektangeln.

**Returns:**
double-värde

### toString {#toString--}
```
public String toString()
```

Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 FitR 100 200 300 400".

**Returns:**
Strängvärde som representerar objektets tillstånd.
