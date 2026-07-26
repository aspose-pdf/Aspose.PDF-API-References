---
title: "Graph"
linktitle: "Graph"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Graph – Grafik‑Generator‑Absatz dar."
type: docs
weight: 70
url: /de/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

Stellt Graph – Grafik‑Generator‑Absatz dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Graph](#Graph--) | Nur für den internen Gebrauch |
| [Graph](#Graph-double-double-) | Initialisiert eine neue Instanz der {@link Graph} Klasse. |
| [Graph](#Graph-float-float-) | Initialisiert eine neue Instanz der {@code Graph} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | Kopiere das Diagramm. |
| [getBorder](#getBorder--) | Erhält den Rand. |
| [getGraphInfo](#getGraphInfo--) | Erhält ein {@code GraphInfo} Objekt, das die Diagramminformationen angibt, wie Farbe, Linienbreite usw. |
| [getHeight](#getHeight--) | Erhält einen Float‑Wert, der die Diagrammhöhe angibt. Die Einheit ist Punkt. In XML ist die Standard‑Einheit Punkt, aber cm und Zoll werden ebenfalls unterstützt. Zum Beispiel,GraphHeight="10cm" oder GraphHeight="5inch". |
| [getLeft](#getLeft--) | Erhält die linke Tabellenkoordinate. |
| [getShapes](#getShapes--) | Erhält eine Sammlung, die alle Formen im Diagramm angibt. |
| [getTitle](#getTitle--) | Erhält einen String‑Wert, der den Titel des Diagramms angibt. |
| [getTop](#getTop--) | Erhält die obere Tabellenkoordinate. |
| [getWidth](#getWidth--) | Erhält einen Float‑Wert, der die Diagrammbreite angibt. Die Einheit ist Punkt. In XML ist die Standard‑Einheit Punkt, aber cm und Zoll werden ebenfalls unterstützt. Zum Beispiel,GraphWidth="10cm" oder GraphWidth="5inch". |
| [isChangePosition](#isChangePosition--) | Ermittelt die Änderung der aktuellen Position nach dem Verarbeiten des Absatzes. (Standard: true) |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Setzt den Rand. |
| [setChangePosition](#setChangePosition-boolean-) | Setzt die Änderung der aktuellen Position nach dem Verarbeiten des Absatzes. (Standard: true) |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Ermittelt oder setzt ein {@code GraphInfo}-Objekt, das die Diagramminformationen angibt, wie Farbe, Linienbreite usw. |
| [setHeight](#setHeight-double-) | Setzt den Fließkommawert, der die Diagrammhöhe angibt. Die Einheit ist Punkt. In XML ist die Standardeinheit Punkt, aber cm und Zoll werden ebenfalls unterstützt. Zum Beispiel GraphHeight=\"10cm\" oder GraphHeight=\"5inch\". |
| [setLeft](#setLeft-double-) | Setzt die linke Tabellenkoordinate. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | Setzt eine Sammlung, die alle Formen im Diagramm angibt. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Setzt den Zeichenkettenwert, der den Titel des Diagramms angibt. |
| [setTop](#setTop-double-) | Setzt die obere Tabellenkoordinate. |
| [setWidth](#setWidth-double-) | Setzt den Fließkommawert, der die Diagrammbreite angibt. Die Einheit ist Punkt. In XML ist die Standardeinheit Punkt, aber cm und Zoll werden ebenfalls unterstützt. Zum Beispiel GraphWidth=\"10cm\" oder GraphWidth=\"5inch\". |

### Graph {#Graph--}
```
public Graph()
```

Nur für den internen Gebrauch

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

Initialisiert eine neue Instanz der {@link Graph} Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Die Breite des Diagramms. |
| Höhe |  | Die Höhe des Diagramms. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

Initialisiert eine neue Instanz der {@code Graph} Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Die Breite des Diagramms. |
| Höhe |  | Die Höhe des Diagramms. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Kopiere das Diagramm.

**Returns:**
Das geklonte Objekt

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Erhält den Rand.

**Returns:**
BorderInfo-Element

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Erhält ein {@code GraphInfo} Objekt, das die Diagramminformationen angibt, wie Farbe, Linienbreite usw.

**Returns:**
GraphInfo-Objekt

### getHeight {#getHeight--}
```
public double getHeight()
```

Erhält einen Float‑Wert, der die Diagrammhöhe angibt. Die Einheit ist Punkt. In XML ist die Standard‑Einheit Punkt, aber cm und Zoll werden ebenfalls unterstützt. Zum Beispiel,GraphHeight="10cm" oder GraphHeight="5inch".

**Returns:**
Wert, der die Diagrammhöhe angibt.

### getLeft {#getLeft--}
```
public double getLeft()
```

Erhält die linke Tabellenkoordinate.

**Returns:**
Tabellenlinkskoordinate.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

Erhält eine Sammlung, die alle Formen im Diagramm angibt.

**Returns:**
BoundsCheckableList von Shapes.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Erhält einen String‑Wert, der den Titel des Diagramms angibt.

**Returns:**
Titel des Diagramms.

### getTop {#getTop--}
```
public double getTop()
```

Erhält die obere Tabellenkoordinate.

**Returns:**
die obere Tabellenkoordinate.

### getWidth {#getWidth--}
```
public double getWidth()
```

Erhält einen Float‑Wert, der die Diagrammbreite angibt. Die Einheit ist Punkt. In XML ist die Standard‑Einheit Punkt, aber cm und Zoll werden ebenfalls unterstützt. Zum Beispiel,GraphWidth="10cm" oder GraphWidth="5inch".

**Returns:**
Fließkommawert, der die Diagrammbreite angibt.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

Ermittelt die Änderung der aktuellen Position nach dem Verarbeiten des Absatzes. (Standard: true)

**Returns:**
boolescher Wert

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Setzt den Rand.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

Setzt die Änderung der aktuellen Position nach dem Verarbeiten des Absatzes. (Standard: true)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Ermittelt oder setzt ein {@code GraphInfo}-Objekt, das die Diagramminformationen angibt, wie Farbe, Linienbreite usw.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Setzt den Fließkommawert, der die Diagrammhöhe angibt. Die Einheit ist Punkt. In XML ist die Standardeinheit Punkt, aber cm und Zoll werden ebenfalls unterstützt. Zum Beispiel GraphHeight=\"10cm\" oder GraphHeight=\"5inch\".

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | der die Diagrammhöhe angibt. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Setzt die linke Tabellenkoordinate.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Tabellenlinkskoordinate. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
Setzt eine Sammlung, die alle Formen im Diagramm angibt.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Setzt den Zeichenkettenwert, der den Titel des Diagramms angibt.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Setzt die obere Tabellenkoordinate.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | die obere Tabellenkoordinate. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Setzt den Fließkommawert, der die Diagrammbreite angibt. Die Einheit ist Punkt. In XML ist die Standardeinheit Punkt, aber cm und Zoll werden ebenfalls unterstützt. Zum Beispiel GraphWidth=\"10cm\" oder GraphWidth=\"5inch\".

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Fließkommawert, der die Diagrammbreite angibt. |
