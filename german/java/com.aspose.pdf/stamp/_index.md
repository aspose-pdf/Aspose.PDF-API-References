---
title: "Stamp"
linktitle: "Stamp"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Eine abstrakte Klasse für verschiedene Arten von Stempeln, die als Ableitungen vorkommen."
type: docs
weight: 4620
url: /de/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

Eine abstrakte Klasse für verschiedene Arten von Stempeln, die als Ableitungen vorkommen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Stamp](#Stamp--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | Ermittelt den unteren Rand des Stempels. |
| [getHeight](#getHeight--) | Ermittelt die gewünschte Höhe des Stempels auf der Seite. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Ermittelt die horizontale Ausrichtung des Stempels auf der Seite. |
| [getLeftMargin](#getLeftMargin--) | Ermittelt den linken Rand des Stempels. |
| [getOpacity](#getOpacity--) | Liefert einen Wert, der die Deckkraft des Stempels angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0. |
| [getOutlineOpacity](#getOutlineOpacity--) | Liefert einen Wert, der die Deckkraft der Stempelkontur angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0. |
| [getOutlineWidth](#getOutlineWidth--) | Liefert einen Wert für die Breite der Stempelkontur. Standardmäßig ist der Wert 1,0. |
| [getRightMargin](#getRightMargin--) | Liefert den rechten Rand des Stempels. |
| [getRotate](#getRotate--) | Liefert die Drehung des Stempelinhalts gemäß {@code Rotation}-Werten. Hinweis: Diese Eigenschaft dient zum Festlegen von Winkeln, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad). Um einen beliebigen Winkel festzulegen, verwenden Sie die Eigenschaft RotateAngle. Wenn der mit ArbitraryAngle festgelegte Winkel kein Vielfaches von 90 ist, gibt die Eigenschaft Rotate den Wert Rotation.None zurück. |
| [getRotateAngle](#getRotateAngle--) | Liefert den Rotationswinkel des Stempels in Grad. Diese Eigenschaft ermöglicht das Festlegen eines beliebigen Rotationswinkels. |
| [getStampId](#getStampId--) | Liefert die Stempel-ID. |
| [getTopMargin](#getTopMargin--) | Liefert den oberen Rand des Stempels. |
| [getVerticalAlignment](#getVerticalAlignment--) | Liefert die vertikale Ausrichtung des Stempels auf der Seite. |
| [getWidth](#getWidth--) | Liefert die gewünschte Breite des Stempels auf der Seite. |
| [getXIndent](#getXIndent--) | Liefert die horizontale Stempelkoordinate, beginnend von links. |
| [getYIndent](#getYIndent--) | Liefert die vertikale Stempelkoordinate, beginnend von unten. |
| [getZoom](#getZoom--) | Liefert den Zoomfaktor des Stempels. Ermöglicht das Skalieren des Stempels. Bitte beachten Sie, dass das Paar von Eigenschaften ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat festzulegen. Das Setzen dieser Eigenschaft ändert sowohl die Eigenschaften ZoomX als auch ZoomY. Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Eigenschaft Zoom den Wert von ZoomX zurück. |
| [getZoomX](#getZoomX--) | Liefert den horizontalen Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels. |
| [getZoomY](#getZoomY--) | Liefert den vertikalen Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels. |
| [isBackground](#isBackground--) | Liefert einen booleschen Wert, der angibt, ob der Inhalt als Hintergrund gestempelt wird. Wenn der Wert true ist, wird der Stempelinhalt unten platziert. Standardmäßig ist der Wert false, der Stempelinhalt wird oben platziert. |
| [put](#put-com.aspose.pdf.Page-) | Fügt einen Stempel auf der Seite hinzu. |
| [setBackground](#setBackground-boolean-) | Setzt einen booleschen Wert, der angibt, ob der Inhalt als Hintergrund gestempelt wird. Wenn der Wert true ist, wird der Stempelinhalt unten platziert. Standardmäßig ist der Wert false, der Stempelinhalt wird oben platziert. |
| [setBottomMargin](#setBottomMargin-double-) | Setzt den unteren Rand des Stempels. |
| [setHeight](#setHeight-double-) | Setzt die gewünschte Höhe des Stempels auf der Seite. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Setzt die horizontale Ausrichtung des Stempels auf der Seite. |
| [setLeftMargin](#setLeftMargin-double-) | Setzt den linken Rand des Stempels. |
| [setOpacity](#setOpacity-double-) | Setzt einen Wert, der die Deckkraft des Stempels angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | Setzt einen Wert, der die Deckkraft der Stempelkontur angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0. |
| [setOutlineWidth](#setOutlineWidth-double-) | Setzt einen Wert für die Breite der Stempelkontur. Standardmäßig ist der Wert 1,0. |
| [setRightMargin](#setRightMargin-double-) | Setzt den rechten Rand des Stempels. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Setzt die Drehung des Stempel-Inhalts gemäß {@code Rotation}-Werten. Hinweis. Diese Eigenschaft ist für Winkel, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad). Um einen beliebigen Winkel festzulegen, verwenden Sie die RotateAngle property. Wenn der durch ArbitraryAngle festgelegte Winkel kein Vielfaches von 90 ist, gibt die Rotate property Rotation.None zurück. |
| [setRotateAngle](#setRotateAngle-double-) | Setzt den Drehwinkel des Stempels in Grad. Diese Eigenschaft ermöglicht das Festlegen eines beliebigen Drehwinkels. |
| [setStampId](#setStampId-int-) | Setzt die Stempel-ID. |
| [setTopMargin](#setTopMargin-double-) | Setzt den oberen Rand des Stempels. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Setzt die vertikale Ausrichtung des Stempels auf der Seite. |
| [setWidth](#setWidth-double-) | Setzt die gewünschte Breite des Stempels auf der Seite. |
| [setXIndent](#setXIndent-double-) | Setzt die horizontale Stempelkoordinate, beginnend von links. |
| [setYIndent](#setYIndent-double-) | Setzt die vertikale Stempelkoordinate, beginnend vom unteren Rand. |
| [setZoom](#setZoom-double-) | Liefert den Zoomfaktor des Stempels. Ermöglicht das Skalieren des Stempels. Bitte beachten Sie, dass das Paar von Eigenschaften ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat festzulegen. Das Setzen dieser Eigenschaft ändert sowohl die Eigenschaften ZoomX als auch ZoomY. Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Eigenschaft Zoom den Wert von ZoomX zurück. |
| [setZoomX](#setZoomX-double-) | Setzt den horizontalen Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels. |
| [setZoomY](#setZoomY-double-) | Setzt den vertikalen Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Ermittelt den unteren Rand des Stempels.

**Returns:**
double-Wert

### getHeight {#getHeight--}
```
public double getHeight()
```

Ermittelt die gewünschte Höhe des Stempels auf der Seite.

**Returns:**
double-Wert

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Ermittelt die horizontale Ausrichtung des Stempels auf der Seite.

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Ermittelt den linken Rand des Stempels.

**Returns:**
double-Wert

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Liefert einen Wert, der die Deckkraft des Stempels angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0.

**Returns:**
double-Wert

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

Liefert einen Wert, der die Deckkraft der Stempelkontur angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0.

**Returns:**
double-Wert

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

Liefert einen Wert für die Breite der Stempelkontur. Standardmäßig ist der Wert 1,0.

**Returns:**
double-Wert

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Liefert den rechten Rand des Stempels.

**Returns:**
double-Wert

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Liefert die Drehung des Stempelinhalts gemäß {@code Rotation}-Werten. Hinweis: Diese Eigenschaft dient zum Festlegen von Winkeln, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad). Um einen beliebigen Winkel festzulegen, verwenden Sie die Eigenschaft RotateAngle. Wenn der mit ArbitraryAngle festgelegte Winkel kein Vielfaches von 90 ist, gibt die Eigenschaft Rotate den Wert Rotation.None zurück.

**Returns:**
Rotationswert @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

Liefert den Rotationswinkel des Stempels in Grad. Diese Eigenschaft ermöglicht das Festlegen eines beliebigen Rotationswinkels.

**Returns:**
double-Wert

### getStampId {#getStampId--}
```
public int getStampId()
```

Liefert die Stempel-ID.

**Returns:**
Kennung des Stempels.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Liefert den oberen Rand des Stempels.

**Returns:**
double-Wert

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Liefert die vertikale Ausrichtung des Stempels auf der Seite.

**Returns:**
VerticalAlignment-Wert @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Liefert die gewünschte Breite des Stempels auf der Seite.

**Returns:**
double-Wert

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Liefert die horizontale Stempelkoordinate, beginnend von links.

**Returns:**
double-Wert

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Liefert die vertikale Stempelkoordinate, beginnend von unten.

**Returns:**
double-Wert

### getZoom {#getZoom--}
```
public double getZoom()
```

Liefert den Zoomfaktor des Stempels. Ermöglicht das Skalieren des Stempels. Bitte beachten Sie, dass das Paar von Eigenschaften ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat festzulegen. Das Setzen dieser Eigenschaft ändert sowohl die Eigenschaften ZoomX als auch ZoomY. Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Eigenschaft Zoom den Wert von ZoomX zurück.

**Returns:**
double-Wert

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

Liefert den horizontalen Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels.

**Returns:**
double-Wert

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

Liefert den vertikalen Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels.

**Returns:**
double-Wert

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Liefert einen booleschen Wert, der angibt, ob der Inhalt als Hintergrund gestempelt wird. Wenn der Wert true ist, wird der Stempelinhalt unten platziert. Standardmäßig ist der Wert false, der Stempelinhalt wird oben platziert.

**Returns:**
boolescher Wert

### put {#put-com.aspose.pdf.Page-}
Fügt einen Stempel auf der Seite hinzu.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Setzt einen booleschen Wert, der angibt, ob der Inhalt als Hintergrund gestempelt wird. Wenn der Wert true ist, wird der Stempelinhalt unten platziert. Standardmäßig ist der Wert false, der Stempelinhalt wird oben platziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Setzt den unteren Rand des Stempels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Setzt die gewünschte Höhe des Stempels auf der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Setzt die horizontale Ausrichtung des Stempels auf der Seite.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Setzt den linken Rand des Stempels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Setzt einen Wert, der die Deckkraft des Stempels angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

Setzt einen Wert, der die Deckkraft der Stempelkontur angibt. Der Wert liegt zwischen 0,0 und 1,0. Standardmäßig ist der Wert 1,0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

Setzt einen Wert für die Breite der Stempelkontur. Standardmäßig ist der Wert 1,0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Setzt den rechten Rand des Stempels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Setzt die Drehung des Stempel-Inhalts gemäß {@code Rotation}-Werten. Hinweis. Diese Eigenschaft ist für Winkel, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad). Um einen beliebigen Winkel festzulegen, verwenden Sie die RotateAngle property. Wenn der durch ArbitraryAngle festgelegte Winkel kein Vielfaches von 90 ist, gibt die Rotate property Rotation.None zurück.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

Setzt den Drehwinkel des Stempels in Grad. Diese Eigenschaft ermöglicht das Festlegen eines beliebigen Drehwinkels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Drehwinkel |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Setzt die Stempel-ID.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Neuer Wert der Stamp ID. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Setzt den oberen Rand des Stempels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Setzt die vertikale Ausrichtung des Stempels auf der Seite.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Setzt die gewünschte Breite des Stempels auf der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Setzt die horizontale Stempelkoordinate, beginnend von links.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Setzt die vertikale Stempelkoordinate, beginnend vom unteren Rand.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

Liefert den Zoomfaktor des Stempels. Ermöglicht das Skalieren des Stempels. Bitte beachten Sie, dass das Paar von Eigenschaften ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat festzulegen. Das Setzen dieser Eigenschaft ändert sowohl die Eigenschaften ZoomX als auch ZoomY. Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Eigenschaft Zoom den Wert von ZoomX zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

Setzt den horizontalen Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

Setzt den vertikalen Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |
