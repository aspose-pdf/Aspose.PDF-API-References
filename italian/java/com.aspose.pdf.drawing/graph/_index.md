---
title: "Graph"
linktitle: "Graph"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta il grafico - paragrafo generatore di grafica."
type: docs
weight: 70
url: /it/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

Rappresenta il grafico - paragrafo generatore di grafica.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Graph](#Graph--) | Solo per uso interno |
| [Graph](#Graph-double-double-) | Inizializza una nuova istanza della classe {@link Graph}. |
| [Graph](#Graph-float-float-) | Inizializza una nuova istanza della classe {@code Graph}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Clona il grafico. |
| [getBorder](#getBorder--) | Ottiene il bordo. |
| [getGraphInfo](#getGraphInfo--) | Ottiene un oggetto {@code GraphInfo} che indica le informazioni del grafico, come colore, larghezza della linea, ecc. |
| [getHeight](#getHeight--) | Ottiene il valore float che indica l'altezza del grafico. L'unità è point. In XML, l'unità predefinita è point, ma sono supportati anche cm e inch. Per esempio, GraphHeight=\"10cm\" o GraphHeight=\"5inch\". |
| [getLeft](#getLeft--) | Ottiene la coordinata sinistra della tabella. |
| [getShapes](#getShapes--) | Ottiene una collezione che indica tutte le forme nel grafico. |
| [getTitle](#getTitle--) | Ottiene il valore stringa che indica il titolo del grafico. |
| [getTop](#getTop--) | Ottiene la coordinata superiore della tabella. |
| [getWidth](#getWidth--) | Ottiene il valore float che indica la larghezza del grafico. L'unità è point. In XML, l'unità predefinita è point, ma sono supportati anche cm e inch. Per esempio, GraphWidth=\"10cm\" o GraphWidth=\"5inch\". |
| [isChangePosition](#isChangePosition--) | Ottiene se cambia la posizione corrente dopo l'elaborazione del paragrafo. (predefinito true) |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Imposta il bordo. |
| [setChangePosition](#setChangePosition-boolean-) | Imposta se cambia la posizione corrente dopo l'elaborazione del paragrafo. (predefinito true) |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Ottiene o imposta un oggetto {@code GraphInfo} che indica le informazioni del grafico, come colore, larghezza della linea, ecc. |
| [setHeight](#setHeight-double-) | Imposta il valore float che indica l'altezza del grafico. L'unità è point. In XML, l'unità predefinita è point, ma sono supportati anche cm e inch. Per esempio, GraphHeight=\"10cm\" o GraphHeight=\"5inch\". |
| [setLeft](#setLeft-double-) | Imposta la coordinata sinistra della tabella. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | Imposta una collezione che indica tutte le forme nel grafico. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Imposta il valore stringa che indica il titolo del grafico. |
| [setTop](#setTop-double-) | Imposta la coordinata superiore della tabella. |
| [setWidth](#setWidth-double-) | Imposta il valore float che indica la larghezza del grafico. L'unità è point. In XML, l'unità predefinita è point, ma sono supportati anche cm e inch. Per esempio, GraphWidth=\"10cm\" o GraphWidth=\"5inch\". |

### Graph {#Graph--}
```
public Graph()
```

Solo per uso interno

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

Inizializza una nuova istanza della classe {@link Graph}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | La larghezza del grafico. |
| altezza |  | L'altezza del grafico. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

Inizializza una nuova istanza della classe {@code Graph}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | La larghezza del grafico. |
| altezza |  | L'altezza del grafico. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona il grafico.

**Returns:**
L'oggetto clonato

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Ottiene il bordo.

**Returns:**
Elemento BorderInfo

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Ottiene un oggetto {@code GraphInfo} che indica le informazioni del grafico, come colore, larghezza della linea, ecc.

**Returns:**
Oggetto GraphInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Ottiene il valore float che indica l'altezza del grafico. L'unità è point. In XML, l'unità predefinita è point, ma sono supportati anche cm e inch. Per esempio, GraphHeight=\"10cm\" o GraphHeight=\"5inch\".

**Returns:**
valore che indica l'altezza del grafico.

### getLeft {#getLeft--}
```
public double getLeft()
```

Ottiene la coordinata sinistra della tabella.

**Returns:**
coordinata sinistra della tabella.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

Ottiene una collezione che indica tutte le forme nel grafico.

**Returns:**
BoundsCheckableList di Shapes.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Ottiene il valore stringa che indica il titolo del grafico.

**Returns:**
titolo del grafico.

### getTop {#getTop--}
```
public double getTop()
```

Ottiene la coordinata superiore della tabella.

**Returns:**
la coordinata superiore della tabella.

### getWidth {#getWidth--}
```
public double getWidth()
```

Ottiene il valore float che indica la larghezza del grafico. L'unità è point. In XML, l'unità predefinita è point, ma sono supportati anche cm e inch. Per esempio, GraphWidth=\"10cm\" o GraphWidth=\"5inch\".

**Returns:**
valore float che indica la larghezza del grafico.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

Ottiene se cambia la posizione corrente dopo l'elaborazione del paragrafo. (predefinito true)

**Returns:**
valore booleano

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Imposta il bordo.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

Imposta se cambia la posizione corrente dopo l'elaborazione del paragrafo. (predefinito true)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Ottiene o imposta un oggetto {@code GraphInfo} che indica le informazioni del grafico, come colore, larghezza della linea, ecc.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Imposta il valore float che indica l'altezza del grafico. L'unità è point. In XML, l'unità predefinita è point, ma sono supportati anche cm e inch. Per esempio, GraphHeight=\"10cm\" o GraphHeight=\"5inch\".

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | che indica l'altezza del grafico. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Imposta la coordinata sinistra della tabella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | coordinata sinistra della tabella. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
Imposta una collezione che indica tutte le forme nel grafico.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Imposta il valore stringa che indica il titolo del grafico.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Imposta la coordinata superiore della tabella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | la coordinata superiore della tabella. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Imposta il valore float che indica la larghezza del grafico. L'unità è point. In XML, l'unità predefinita è point, ma sono supportati anche cm e inch. Per esempio, GraphWidth=\"10cm\" o GraphWidth=\"5inch\".

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float che indica la larghezza del grafico. |
