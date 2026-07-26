---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe contenitore per elementi grafici."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Rappresenta una classe contenitore per elementi grafici.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Istanzia una classe contenitore per elementi grafici. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Istanzia una classe contenitore per elementi grafici. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Istanzia una classe contenitore per elementi grafici. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Istanzia una classe contenitore per elementi grafici. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Istanzia una classe contenitore per elementi grafici. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calcola la distanza tra due contenitori. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Confronta l'oggetto SubPathContainer corrente con un altro oggetto SubPathContainer e restituisce un intero che indica se l'oggetto corrente è minore, uguale o maggiore dell'altro oggetto. Gli oggetti sono confrontati in base al loro ID numerico. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calcola la distanza tra questo contenitore e l'altro contenitore. |
| [getGraphElement](#getGraphElement--) | Restituisce l'elemento grafico contenuto. |
| [getId](#getId--) | Restituisce l'Id del SubPathContainer. L'Id è necessario per facilitare il debug e l'ordinamento degli elementi durante il rendering. |
| [getRect](#getRect--) | Rappresenta un rettangolo dell'elemento contenuto. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Istanzia una classe contenitore per elementi grafici.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Istanzia una classe contenitore per elementi grafici.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Istanzia una classe contenitore per elementi grafici.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Istanzia una classe contenitore per elementi grafici.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Istanzia una classe contenitore per elementi grafici.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calcola la distanza tra due contenitori.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Confronta l'oggetto SubPathContainer corrente con un altro oggetto SubPathContainer e restituisce un intero che indica se l'oggetto corrente è minore, uguale o maggiore dell'altro oggetto. Gli oggetti sono confrontati in base al loro ID numerico.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calcola la distanza tra questo contenitore e l'altro contenitore.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

Restituisce l'elemento grafico contenuto.

**Returns:**
Istanza di GraphicElement

### getId {#getId--}
```
public final int getId()
```

Restituisce l'Id del SubPathContainer. L'Id è necessario per facilitare il debug e l'ordinamento degli elementi durante il rendering.

**Returns:**
valore int

### getRect {#getRect--}
```
public final Rectangle getRect()
```

Rappresenta un rettangolo dell'elemento contenuto.

**Returns:**
Istanza Rectangle

### toString {#toString--}
```
public String toString()
```

{@code }
