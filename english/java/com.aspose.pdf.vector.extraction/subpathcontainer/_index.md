---
title: SubPathContainer
linktitle: SubPathContainer
second_title: Aspose.PDF for Java API Reference
description: Represents a container class for graphic elements.
type: docs
weight: 10
url: /java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Represents a container class for graphic elements.

## Constructors

| Constructor | Description |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Instantiates a container class for graphic elements. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Instantiates a container class for graphic elements. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Instantiates a container class for graphic elements. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Instantiates a container class for graphic elements. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Instantiates a container class for graphic elements. |

## Methods

| Method | Description |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calculates the distance between two containers. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Compares the current SubPathContainer object with another SubPathContainer object and returns an integer that indicates whether the current object is less than, equal to, or greater than the other object. Objects are compared by their numeric ID. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calculates the distance between this container and other container. |
| [getGraphElement](#getGraphElement--) | Gets contained graphic element. |
| [getId](#getId--) | Gets the Id of the SubPathContainer. Id is required for ease of debugging and sorting of elements during rendering. |
| [getRect](#getRect--) | Represents a rectangle of contained element. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Instantiates a container class for graphic elements.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Instantiates a container class for graphic elements.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Instantiates a container class for graphic elements.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Instantiates a container class for graphic elements.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Instantiates a container class for graphic elements.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calculates the distance between two containers.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Compares the current SubPathContainer object with another SubPathContainer object and returns an integer that indicates whether the current object is less than, equal to, or greater than the other object. Objects are compared by their numeric ID.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calculates the distance between this container and other container.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

Gets contained graphic element.

**Returns:**
GraphicElement instance

### getId {#getId--}
```
public final int getId()
```

Gets the Id of the SubPathContainer. Id is required for ease of debugging and sorting of elements during rendering.

**Returns:**
int value

### getRect {#getRect--}
```
public final Rectangle getRect()
```

Represents a rectangle of contained element.

**Returns:**
Rectangle instance

### toString {#toString--}
```
public String toString()
```

{@code }
