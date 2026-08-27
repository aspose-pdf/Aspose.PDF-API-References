---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en behållarklass för grafiska element."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Representerar en behållarklass för grafiska element.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Instansierar en behållarklass för grafikelement. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Instansierar en behållarklass för grafikelement. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Instansierar en behållarklass för grafikelement. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Instansierar en behållarklass för grafikelement. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Instansierar en behållarklass för grafikelement. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | Beräknar avståndet mellan två behållare. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Jämför det aktuella SubPathContainer-objektet med ett annat SubPathContainer-objekt och returnerar ett heltal som indikerar om det aktuella objektet är mindre än, lika med eller större än det andra objektet. Objekt jämförs efter deras numeriska ID. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Beräknar avståndet mellan denna behållare och en annan behållare. |
| [getGraphElement](#getGraphElement--) | Hämtar det innehållna grafikelementet. |
| [getId](#getId--) | Hämtar Id för SubPathContainer. Id behövs för att underlätta felsökning och sortering av element under rendering. |
| [getRect](#getRect--) | Representerar en rektangel för det innehållna elementet. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Instansierar en behållarklass för grafikelement.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Instansierar en behållarklass för grafikelement.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Instansierar en behållarklass för grafikelement.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Instansierar en behållarklass för grafikelement.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Instansierar en behållarklass för grafikelement.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
Beräknar avståndet mellan två behållare.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Jämför det aktuella SubPathContainer-objektet med ett annat SubPathContainer-objekt och returnerar ett heltal som indikerar om det aktuella objektet är mindre än, lika med eller större än det andra objektet. Objekt jämförs efter deras numeriska ID.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Beräknar avståndet mellan denna behållare och en annan behållare.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

Hämtar det innehållna grafikelementet.

**Returns:**
GraphicElement-instans

### getId {#getId--}
```
public final int getId()
```

Hämtar Id för SubPathContainer. Id behövs för att underlätta felsökning och sortering av element under rendering.

**Returns:**
int‑värde

### getRect {#getRect--}
```
public final Rectangle getRect()
```

Representerar en rektangel för det innehållna elementet.

**Returns:**
Rektangelinstans

### toString {#toString--}
```
public String toString()
```

{@code }
