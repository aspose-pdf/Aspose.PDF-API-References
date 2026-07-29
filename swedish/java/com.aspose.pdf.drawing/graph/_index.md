---
title: "Graph"
linktitle: "Graph"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar graf - grafikgeneratorparagraf."
type: docs
weight: 70
url: /sv/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

Representerar graf - grafikgeneratorparagraf.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Graph](#Graph--) | Endast för intern användning |
| [Graph](#Graph-double-double-) | Initierar en ny instans av {@link Graph} klass. |
| [Graph](#Graph-float-float-) | Initierar en ny instans av {@code Graph} klass. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Klona grafen. |
| [getBorder](#getBorder--) | Hämtar kanten. |
| [getGraphInfo](#getGraphInfo--) | Hämtar ett {@code GraphInfo} objekt som indikerar grafinformation, såsom färg, linjebredd, etc. |
| [getHeight](#getHeight--) | Hämtar ett flyttal som indikerar grafens höjd. Enheten är punkt. I XML är standardenheten punkt, men cm och tum stöds också. Till exempel,GraphHeight=\"10cm\" eller GraphHeight=\"5inch\". |
| [getLeft](#getLeft--) | Hämtar tabellens vänstra koordinat. |
| [getShapes](#getShapes--) | Hämtar en samling som indikerar alla former i grafen. |
| [getTitle](#getTitle--) | Hämtar strängvärde som indikerar grafens titel. |
| [getTop](#getTop--) | Hämtar tabellens övre koordinat. |
| [getWidth](#getWidth--) | Hämtar ett flyttal som indikerar grafens bredd. Enheten är punkt. I XML är standardenheten punkt, men cm och tum stöds också. Till exempel,GraphWidth=\"10cm\" eller GraphWidth=\"5inch\". |
| [isChangePosition](#isChangePosition--) | Hämtar ändring av aktuell position efter bearbetning av stycke. (standard true) |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Anger kanten. |
| [setChangePosition](#setChangePosition-boolean-) | Ställer in att ändra aktuell position efter bearbetning av stycke.(standard true) |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Hämtar eller anger ett {@code GraphInfo}-objekt som indikerar diagraminformation, såsom färg, linjebredd, etc. |
| [setHeight](#setHeight-double-) | Ställer in flyttal som indikerar diagramhöjden. Enheten är punkt. I XML är standardenheten punkt, men cm och tum stöds också. Till exempel,GraphHeight="10cm" eller GraphHeight="5inch". |
| [setLeft](#setLeft-double-) | Ställer in tabellens vänstra koordinat. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | Ställer in en samling som indikerar alla former i diagrammet. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Ställer in strängvärde som indikerar diagrammets titel. |
| [setTop](#setTop-double-) | Ställer in tabellens övre koordinat. |
| [setWidth](#setWidth-double-) | Ställer in flyttal som indikerar diagrambredden. Enheten är punkt. I XML är standardenheten punkt, men cm och tum stöds också. Till exempel,GraphWidth="10cm" eller GraphWidth="5inch". |

### Graph {#Graph--}
```
public Graph()
```

Endast för intern användning

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

Initierar en ny instans av {@link Graph} klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Diagrammets bredd. |
| höjd |  | Diagrammets höjd. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

Initierar en ny instans av {@code Graph} klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Diagrammets bredd. |
| höjd |  | Diagrammets höjd. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klona grafen.

**Returns:**
Det klonade objektet

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Hämtar kanten.

**Returns:**
BorderInfo-element

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Hämtar ett {@code GraphInfo} objekt som indikerar grafinformation, såsom färg, linjebredd, etc.

**Returns:**
GraphInfo-objekt

### getHeight {#getHeight--}
```
public double getHeight()
```

Hämtar ett flyttal som indikerar grafens höjd. Enheten är punkt. I XML är standardenheten punkt, men cm och tum stöds också. Till exempel,GraphHeight=\"10cm\" eller GraphHeight=\"5inch\".

**Returns:**
värde som indikerar diagramhöjden.

### getLeft {#getLeft--}
```
public double getLeft()
```

Hämtar tabellens vänstra koordinat.

**Returns:**
tabellens vänstra koordinat.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

Hämtar en samling som indikerar alla former i grafen.

**Returns:**
BoundsCheckableList av Shapes.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Hämtar strängvärde som indikerar grafens titel.

**Returns:**
diagrammets titel.

### getTop {#getTop--}
```
public double getTop()
```

Hämtar tabellens övre koordinat.

**Returns:**
tabellens övre koordinat.

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar ett flyttal som indikerar grafens bredd. Enheten är punkt. I XML är standardenheten punkt, men cm och tum stöds också. Till exempel,GraphWidth=\"10cm\" eller GraphWidth=\"5inch\".

**Returns:**
flyttal som indikerar diagrambredden.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

Hämtar ändring av aktuell position efter bearbetning av stycke. (standard true)

**Returns:**
booleskt värde

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Anger kanten.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

Ställer in att ändra aktuell position efter bearbetning av stycke.(standard true)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Hämtar eller anger ett {@code GraphInfo}-objekt som indikerar diagraminformation, såsom färg, linjebredd, etc.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Ställer in flyttal som indikerar diagramhöjden. Enheten är punkt. I XML är standardenheten punkt, men cm och tum stöds också. Till exempel,GraphHeight="10cm" eller GraphHeight="5inch".

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som indikerar diagramhöjden. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Ställer in tabellens vänstra koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | tabellens vänstra koordinat. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
Ställer in en samling som indikerar alla former i diagrammet.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Ställer in strängvärde som indikerar diagrammets titel.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Ställer in tabellens övre koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | tabellens övre koordinat. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ställer in flyttal som indikerar diagrambredden. Enheten är punkt. I XML är standardenheten punkt, men cm och tum stöds också. Till exempel,GraphWidth="10cm" eller GraphWidth="5inch".

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttal som indikerar diagrambredden. |
