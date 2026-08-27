---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Containerklasse für grafische Elemente dar."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Stellt eine Containerklasse für grafische Elemente dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Instanziert eine Containerklasse für Grafik-Elemente. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Instanziert eine Containerklasse für Grafik-Elemente. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Instanziert eine Containerklasse für Grafik-Elemente. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Instanziert eine Containerklasse für Grafik-Elemente. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Instanziert eine Containerklasse für Grafik-Elemente. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | Berechnet den Abstand zwischen zwei Containern. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Vergleicht das aktuelle SubPathContainer-Objekt mit einem anderen SubPathContainer-Objekt und gibt einen Integer zurück, der angibt, ob das aktuelle Objekt kleiner, gleich oder größer als das andere Objekt ist. Objekte werden anhand ihrer numerischen ID verglichen. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Berechnet den Abstand zwischen diesem Container und einem anderen Container. |
| [getGraphElement](#getGraphElement--) | Ruft das enthaltene Grafik-Element ab. |
| [getId](#getId--) | Ruft die Id des SubPathContainer ab. Die Id wird für einfaches Debugging und das Sortieren von Elementen während des Renderns benötigt. |
| [getRect](#getRect--) | Stellt ein Rechteck des enthaltenen Elements dar. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Instanziert eine Containerklasse für Grafik-Elemente.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Instanziert eine Containerklasse für Grafik-Elemente.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Instanziert eine Containerklasse für Grafik-Elemente.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Instanziert eine Containerklasse für Grafik-Elemente.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Instanziert eine Containerklasse für Grafik-Elemente.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
Berechnet den Abstand zwischen zwei Containern.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Vergleicht das aktuelle SubPathContainer-Objekt mit einem anderen SubPathContainer-Objekt und gibt einen Integer zurück, der angibt, ob das aktuelle Objekt kleiner, gleich oder größer als das andere Objekt ist. Objekte werden anhand ihrer numerischen ID verglichen.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Berechnet den Abstand zwischen diesem Container und einem anderen Container.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

Ruft das enthaltene Grafik-Element ab.

**Returns:**
GraphicElement-Instanz

### getId {#getId--}
```
public final int getId()
```

Ruft die Id des SubPathContainer ab. Die Id wird für einfaches Debugging und das Sortieren von Elementen während des Renderns benötigt.

**Returns:**
int-Wert

### getRect {#getRect--}
```
public final Rectangle getRect()
```

Stellt ein Rechteck des enthaltenen Elements dar.

**Returns:**
Rechteck-Instanz

### toString {#toString--}
```
public String toString()
```

{@code }
