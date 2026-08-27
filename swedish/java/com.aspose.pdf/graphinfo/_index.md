---
title: "GraphInfo"
linktitle: "GraphInfo"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar grafikinformation."
type: docs
weight: 1840
url: /sv/java/com.aspose.pdf/graphinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.GraphInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class GraphInfo extends Object implements com.aspose.ms.System.ICloneable
```

Representerar grafikinformation.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GraphInfo](#GraphInfo--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Klona grafikinformationen. |
| [getColor](#getColor--) | Hämtar ett {@code Color} objekt som anger färgen på grafen. |
| [getDashArray](#getDashArray--) | Hämtar en streckarray. |
| [getDashPhase](#getDashPhase--) | Hämtar en streckfas. |
| [getFillColor](#getFillColor--) | Hämtar ett {@code Color} objekt som anger fyllningsfärgen på grafen. |
| [getLineWidth](#getLineWidth--) | Hämtar ett flyttal som anger linjebredden på grafen. |
| [getRotationAngle](#getRotationAngle--) | Hämtar ett flyttal som anger rotationsvinkeln för koordinatsystemet vid transformation av ett koordinatsystem. |
| [getScalingRateX](#getScalingRateX--) | Hämtar ett flyttal som anger skalningsfaktorn för x-koordinaten vid transformation av ett koordinatsystem. |
| [getScalingRateY](#getScalingRateY--) | Hämtar ett flyttal som anger skalningsfaktorn för y-koordinaten vid transformation av ett koordinatsystem. |
| [getSkewAngleX](#getSkewAngleX--) | Hämtar ett flyttal som anger skevningsvinkeln för x-koordinaten vid transformation av ett koordinatsystem. |
| [getSkewAngleY](#getSkewAngleY--) | Hämtar ett flyttal som anger skevningsvinkeln för y-koordinaten vid transformation av ett koordinatsystem. |
| [getX](#getX--) | Hämta X-koordinaten för en vertikal kant när TableAbsorber används, och returnera "-1" för en horisontell kant. |
| [getY](#getY--) | Hämta Y-koordinaten för en horisontell kant när TableAbsorber används, och returnera "-1" för en vertikal kant. |
| [isDoubled](#isDoubled--) | Hämtar om kanten är dubblerad. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Ställer in ett {@code Color} objekt som anger färgen på grafen. |
| [setDashArray](#setDashArray-int:A-) | Ställer in en streckarray. |
| [setDashPhase](#setDashPhase-int-) | Ställer in en streckfas. |
| [setDoubled](#setDoubled-boolean-) | Ställer in om kanten är dubblerad. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Ställer in ett {@code Color} objekt som indikerar fyllningsfärgen för grafen. |
| [setLineWidth](#setLineWidth-float-) | Ställer in ett flyttal som indikerar linjebredden för grafen. |
| [setRotationAngle](#setRotationAngle-double-) | Ställer in ett flyttal som indikerar rotationsvinkeln för koordinatsystemet när ett koordinatsystem transformeras. |
| [setScalingRateX](#setScalingRateX-double-) | Ställer in ett flyttal som indikerar skalningsfaktorn för x-koordinaten när ett koordinatsystem transformeras. |
| [setScalingRateY](#setScalingRateY-double-) | Ställer in ett flyttal som indikerar skalningsfaktorn för y-koordinaten när ett koordinatsystem transformeras. |
| [setSkewAngleX](#setSkewAngleX-double-) | Ställer in ett flyttal som indikerar skevvinkeln för x-koordinaten när ett koordinatsystem transformeras. |
| [setSkewAngleY](#setSkewAngleY-double-) | Ställer in ett flyttal som indikerar skevvinkeln för y-koordinaten när ett koordinatsystem transformeras. |

### GraphInfo {#GraphInfo--}
```
public GraphInfo()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Klona grafikinformationen.

**Returns:**
Det klonade objektet

### getColor {#getColor--}
```
public Color getColor()
```

Hämtar ett {@code Color} objekt som anger färgen på grafen.

**Returns:**
objekt som indikerar färgen

### getDashArray {#getDashArray--}
```
public int[] getDashArray()
```

Hämtar en streckarray.

**Returns:**
streckarray

### getDashPhase {#getDashPhase--}
```
public int getDashPhase()
```

Hämtar en streckfas.

**Returns:**
streckfas.

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Hämtar ett {@code Color} objekt som anger fyllningsfärgen på grafen.

**Returns:**
objekt som indikerar fyllningsfärgen

### getLineWidth {#getLineWidth--}
```
public float getLineWidth()
```

Hämtar ett flyttal som anger linjebredden på grafen.

**Returns:**
värde som indikerar linjebredden.

### getRotationAngle {#getRotationAngle--}
```
public double getRotationAngle()
```

Hämtar ett flyttal som anger rotationsvinkeln för koordinatsystemet vid transformation av ett koordinatsystem.

**Returns:**
double-värde

### getScalingRateX {#getScalingRateX--}
```
public double getScalingRateX()
```

Hämtar ett flyttal som anger skalningsfaktorn för x-koordinaten vid transformation av ett koordinatsystem.

**Returns:**
double-värde

### getScalingRateY {#getScalingRateY--}
```
public double getScalingRateY()
```

Hämtar ett flyttal som anger skalningsfaktorn för y-koordinaten vid transformation av ett koordinatsystem.

**Returns:**
double-värde

### getSkewAngleX {#getSkewAngleX--}
```
public double getSkewAngleX()
```

Hämtar ett flyttal som anger skevningsvinkeln för x-koordinaten vid transformation av ett koordinatsystem.

**Returns:**
double-värde

### getSkewAngleY {#getSkewAngleY--}
```
public double getSkewAngleY()
```

Hämtar ett flyttal som anger skevningsvinkeln för y-koordinaten vid transformation av ett koordinatsystem.

**Returns:**
double-värde

### getX {#getX--}
```
public final double getX()
```

Hämta X-koordinaten för en vertikal kant när TableAbsorber används, och returnera "-1" för en horisontell kant.

**Returns:**
double-värde

### getY {#getY--}
```
public final double getY()
```

Hämta Y-koordinaten för en horisontell kant när TableAbsorber används, och returnera "-1" för en vertikal kant.

**Returns:**
double-värde

### isDoubled {#isDoubled--}
```
public boolean isDoubled()
```

Hämtar om kanten är dubblerad.

**Returns:**
booleskt värde

### setColor {#setColor-com.aspose.pdf.Color-}
Ställer in ett {@code Color} objekt som anger färgen på grafen.

### setDashArray {#setDashArray-int:A-}
```
public void setDashArray(int[] value)
```

Ställer in en streckarray.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | streckarray |

### setDashPhase {#setDashPhase-int-}
```
public void setDashPhase(int value)
```

Ställer in en streckfas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | streckfas. |

### setDoubled {#setDoubled-boolean-}
```
public void setDoubled(boolean value)
```

Ställer in om kanten är dubblerad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Ställer in ett {@code Color} objekt som indikerar fyllningsfärgen för grafen.

### setLineWidth {#setLineWidth-float-}
```
public void setLineWidth(float value)
```

Ställer in ett flyttal som indikerar linjebredden för grafen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | värde som indikerar linjebredden. |

### setRotationAngle {#setRotationAngle-double-}
```
public void setRotationAngle(double value)
```

Ställer in ett flyttal som indikerar rotationsvinkeln för koordinatsystemet när ett koordinatsystem transformeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setScalingRateX {#setScalingRateX-double-}
```
public void setScalingRateX(double value)
```

Ställer in ett flyttal som indikerar skalningsfaktorn för x-koordinaten när ett koordinatsystem transformeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setScalingRateY {#setScalingRateY-double-}
```
public void setScalingRateY(double value)
```

Ställer in ett flyttal som indikerar skalningsfaktorn för y-koordinaten när ett koordinatsystem transformeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setSkewAngleX {#setSkewAngleX-double-}
```
public void setSkewAngleX(double value)
```

Ställer in ett flyttal som indikerar skevvinkeln för x-koordinaten när ett koordinatsystem transformeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setSkewAngleY {#setSkewAngleY-double-}
```
public void setSkewAngleY(double value)
```

Ställer in ett flyttal som indikerar skevvinkeln för y-koordinaten när ett koordinatsystem transformeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |
