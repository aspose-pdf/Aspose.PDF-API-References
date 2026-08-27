---
title: "Stamp"
linktitle: "Stamp"
second_title: "Aspose.PDF för Java API-referens"
description: "En abstrakt klass för olika typer av stämplar som kommer som underklasser."
type: docs
weight: 4620
url: /sv/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

En abstrakt klass för olika typer av stämplar som kommer som underklasser.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Stamp](#Stamp--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | Hämtar bottenmarginal för stamp. |
| [getHeight](#getHeight--) | Hämtar önskad höjd för stamp på sidan. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Hämtar horisontell justering för stamp på sidan. |
| [getLeftMargin](#getLeftMargin--) | Hämtar vänstermarginal för stamp. |
| [getOpacity](#getOpacity--) | Hämtar ett värde som indikerar stampens opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [getOutlineOpacity](#getOutlineOpacity--) | Hämtar ett värde som indikerar stampens konturopacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [getOutlineWidth](#getOutlineWidth--) | Hämtar ett värde för stampens konturbredd. Som standard är värdet 1.0. |
| [getRightMargin](#getRightMargin--) | Hämtar högermarginalen för stämpeln. |
| [getRotate](#getRotate--) | Hämtar rotationen för stämpelns innehåll enligt {@code Rotation}-värden. Obs. Denna egenskap är för angivna vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ange en godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90, returnerar Rotate-egenskapen Rotation.None. |
| [getRotateAngle](#getRotateAngle--) | Hämtar rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ange en godtycklig rotationsvinkel. |
| [getStampId](#getStampId--) | Hämtar stämpelns ID. |
| [getTopMargin](#getTopMargin--) | Hämtar övre marginalen för stämpeln. |
| [getVerticalAlignment](#getVerticalAlignment--) | Hämtar vertikal justering av stämpeln på sidan. |
| [getWidth](#getWidth--) | Hämtar önskad bredd för stämpeln på sidan. |
| [getXIndent](#getXIndent--) | Hämtar horisontell stämpelkoordinat, räknat från vänster. |
| [getYIndent](#getYIndent--) | Hämtar vertikal stämpelkoordinat, räknat från botten. |
| [getZoom](#getZoom--) | Hämtar zoomfaktorn för stämpeln. Tillåter att skala stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ange zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. Om ZoomX och ZoomY är olika, returnerar Zoom-egenskapen ZoomX-värdet. |
| [getZoomX](#getZoomX--) | Hämtar horisontell zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt. |
| [getZoomY](#getZoomY--) | Hämtar vertikal zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt. |
| [isBackground](#isBackground--) | Hämtar ett booleskt värde som indikerar att innehållet är stämplat som bakgrund. Om värdet är true, placeras stämpelns innehåll längst ner. Som standard är värdet false, och stämpelns innehåll placeras högst upp. |
| [put](#put-com.aspose.pdf.Page-) | Lägger till stämpel på sidan. |
| [setBackground](#setBackground-boolean-) | Ställer in ett booleskt värde som indikerar att innehållet är stämplat som bakgrund. Om värdet är true, placeras stämpelns innehåll längst ner. Som standard är värdet false, och stämpelns innehåll placeras högst upp. |
| [setBottomMargin](#setBottomMargin-double-) | Ställer in bottenmarginalen för stämpeln. |
| [setHeight](#setHeight-double-) | Ställer in önskad höjd för stämpeln på sidan. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Ställer in horisontell justering av stämpeln på sidan. |
| [setLeftMargin](#setLeftMargin-double-) | Ställer in vänstermarginalen för stämpeln. |
| [setOpacity](#setOpacity-double-) | Ställer in ett värde för att ange stämpelns opacitet. Värdet är mellan 0,0 och 1,0. Som standard är värdet 1,0. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | Ställer in ett värde för att ange stämpelns konturopacitet. Värdet är mellan 0,0 och 1,0. Som standard är värdet 1,0. |
| [setOutlineWidth](#setOutlineWidth-double-) | Ställer in ett värde för stämpelns konturbredd. Som standard är värdet 1,0. |
| [setRightMargin](#setRightMargin-double-) | Ställer in högermarginalen för stämpeln. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Ställer in rotationen för stämpelns innehåll enligt {@code Rotation}-värden. Obs. Denna egenskap är för angivna vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ange en godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90, returnerar Rotate-egenskapen Rotation.None. |
| [setRotateAngle](#setRotateAngle-double-) | Ställer in rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ange en godtycklig rotationsvinkel. |
| [setStampId](#setStampId-int-) | Ställer in stämpelns ID. |
| [setTopMargin](#setTopMargin-double-) | Ställer in övre marginal för stämpeln. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ställer in vertikal justering av stämpeln på sidan. |
| [setWidth](#setWidth-double-) | Ställer in önskad bredd på stämpeln på sidan. |
| [setXIndent](#setXIndent-double-) | Ange horisontell stämpelkoordinat, med början från vänster. |
| [setYIndent](#setYIndent-double-) | Ange vertikal stämpelkoordinat, med början från botten. |
| [setZoom](#setZoom-double-) | Hämtar zoomfaktorn för stämpeln. Tillåter att skala stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ange zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. Om ZoomX och ZoomY är olika, returnerar Zoom-egenskapen ZoomX-värdet. |
| [setZoomX](#setZoomX-double-) | Ställer in horisontellt zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt. |
| [setZoomY](#setZoomY-double-) | Ställer in vertikalt zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Hämtar bottenmarginal för stamp.

**Returns:**
double-värde

### getHeight {#getHeight--}
```
public double getHeight()
```

Hämtar önskad höjd för stamp på sidan.

**Returns:**
double-värde

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Hämtar horisontell justering för stamp på sidan.

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Hämtar vänstermarginal för stamp.

**Returns:**
double-värde

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Hämtar ett värde som indikerar stampens opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0.

**Returns:**
double-värde

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

Hämtar ett värde som indikerar stampens konturopacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0.

**Returns:**
double-värde

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

Hämtar ett värde för stampens konturbredd. Som standard är värdet 1.0.

**Returns:**
double-värde

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Hämtar högermarginalen för stämpeln.

**Returns:**
double-värde

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Hämtar rotationen för stämpelns innehåll enligt {@code Rotation}-värden. Obs. Denna egenskap är för angivna vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ange en godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90, returnerar Rotate-egenskapen Rotation.None.

**Returns:**
Rotationsvärde @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

Hämtar rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ange en godtycklig rotationsvinkel.

**Returns:**
double-värde

### getStampId {#getStampId--}
```
public int getStampId()
```

Hämtar stämpelns ID.

**Returns:**
Identifierare för stämpeln.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Hämtar övre marginalen för stämpeln.

**Returns:**
double-värde

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Hämtar vertikal justering av stämpeln på sidan.

**Returns:**
VerticalAlignment-värde @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar önskad bredd för stämpeln på sidan.

**Returns:**
double-värde

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Hämtar horisontell stämpelkoordinat, räknat från vänster.

**Returns:**
double-värde

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Hämtar vertikal stämpelkoordinat, räknat från botten.

**Returns:**
double-värde

### getZoom {#getZoom--}
```
public double getZoom()
```

Hämtar zoomfaktorn för stämpeln. Tillåter att skala stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ange zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. Om ZoomX och ZoomY är olika, returnerar Zoom-egenskapen ZoomX-värdet.

**Returns:**
double-värde

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

Hämtar horisontell zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt.

**Returns:**
double-värde

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

Hämtar vertikal zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt.

**Returns:**
double-värde

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Hämtar ett booleskt värde som indikerar att innehållet är stämplat som bakgrund. Om värdet är true, placeras stämpelns innehåll längst ner. Som standard är värdet false, och stämpelns innehåll placeras högst upp.

**Returns:**
booleskt värde

### put {#put-com.aspose.pdf.Page-}
Lägger till stämpel på sidan.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Ställer in ett booleskt värde som indikerar att innehållet är stämplat som bakgrund. Om värdet är true, placeras stämpelns innehåll längst ner. Som standard är värdet false, och stämpelns innehåll placeras högst upp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Ställer in bottenmarginalen för stämpeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Ställer in önskad höjd för stämpeln på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Ställer in horisontell justering av stämpeln på sidan.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Ställer in vänstermarginalen för stämpeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Ställer in ett värde för att ange stämpelns opacitet. Värdet är mellan 0,0 och 1,0. Som standard är värdet 1,0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

Ställer in ett värde för att ange stämpelns konturopacitet. Värdet är mellan 0,0 och 1,0. Som standard är värdet 1,0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

Ställer in ett värde för stämpelns konturbredd. Som standard är värdet 1,0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Ställer in högermarginalen för stämpeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Ställer in rotationen för stämpelns innehåll enligt {@code Rotation}-värden. Obs. Denna egenskap är för angivna vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ange en godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90, returnerar Rotate-egenskapen Rotation.None.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

Ställer in rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ange en godtycklig rotationsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | rotera vinkel |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Ställer in stämpelns ID.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Nytt värde för stämpel-ID. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Ställer in övre marginal för stämpeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ställer in vertikal justering av stämpeln på sidan.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ställer in önskad bredd på stämpeln på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Ange horisontell stämpelkoordinat, med början från vänster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Ange vertikal stämpelkoordinat, med början från botten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

Hämtar zoomfaktorn för stämpeln. Tillåter att skala stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ange zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. Om ZoomX och ZoomY är olika, returnerar Zoom-egenskapen ZoomX-värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

Ställer in horisontellt zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

Ställer in vertikalt zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |
