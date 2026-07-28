---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar en explicit destination som visar sidan med koordinaterna (vänster, topp) placerade i fönstrets övre vänstra hörn och sidans innehåll."
type: docs
weight: 5800
url: /sv/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> Representerar explicit destination som visar sidan med koordinaterna (left, top) placerade i fönstrets övre vänstra hörn och sidans innehåll förstorad med zoomfaktorn. Ett null‑värde för någon av parametrarna left, top eller zoom anger att det aktuella värdet för den parametern ska behållas oförändrat. Ett zoomvärde på 0 har samma betydelse som ett null‑värde. </p> <hr> <p> Document doc = new Document(\"example.pdf\"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Skapar en fjärrexplicit destination. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | Skapar en fjärrexplicit destination. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Skapar instansen och initierar den med DOM‑sidobjektet och synliga parametrar. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Skapa destination till angiven plats på sidan med hänsyn till sidrotation om det krävs. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Skapa destination till angiven sida. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Skapa destination till övre vänstra hörnet på den angivna sidan. |
| [getLeft](#getLeft--) | Hämtar vänster horisontell koordinat för fönstrets övre vänstra hörn. |
| [getTop](#getTop--) | Hämtar övre vertikala koordinat för fönstrets övre vänstra hörn. |
| [getZoom](#getZoom--) | Hämtar zoomfaktor. |
| [toString](#toString--) | Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
Skapar en fjärrexplicit destination.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

Skapar en fjärrexplicit destination.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Destinationssidnumret för fjärrdokumentet. |
| vänster |  | Vänster horisontell koordinat för fönstrets övre vänstra hörn. |
| övre |  | Övre vertikala koordinaten för fönstrets övre vänstra hörn. |
| zoom |  | Zoomfaktor. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
Skapar instansen och initierar den med DOM‑sidobjektet och synliga parametrar.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
Skapa destination till angiven plats på sidan med hänsyn till sidrotation om det krävs.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
Skapa destination till angiven sida.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
Skapa destination till övre vänstra hörnet på den angivna sidan.

### getLeft {#getLeft--}
```
public double getLeft()
```

Hämtar vänster horisontell koordinat för fönstrets övre vänstra hörn.

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

Hämtar övre vertikala koordinat för fönstrets övre vänstra hörn.

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

Hämtar zoomfaktor.

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

Konverterar objektets tillstånd till ett strängvärde. Exempel: "1 XYZ 100 200 3".

**Returns:**
Strängvärde som representerar objektets tillstånd.
