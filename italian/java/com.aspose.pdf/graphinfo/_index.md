---
title: "GraphInfo"
linktitle: "GraphInfo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le informazioni grafiche."
type: docs
weight: 1840
url: /it/java/com.aspose.pdf/graphinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.GraphInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class GraphInfo extends Object implements com.aspose.ms.System.ICloneable
```

Rappresenta le informazioni grafiche.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GraphInfo](#GraphInfo--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Clona le informazioni grafiche. |
| [getColor](#getColor--) | Restituisce un oggetto {@code Color} che indica il colore del grafico. |
| [getDashArray](#getDashArray--) | Restituisce un array di trattini. |
| [getDashPhase](#getDashPhase--) | Restituisce una fase di trattino. |
| [getFillColor](#getFillColor--) | Restituisce un oggetto {@code Color} che indica il colore di riempimento del grafico. |
| [getLineWidth](#getLineWidth--) | Restituisce un valore float che indica lo spessore della linea del grafico. |
| [getRotationAngle](#getRotationAngle--) | Restituisce un valore float che indica l'angolo di rotazione del sistema di coordinate durante la trasformazione di un sistema di coordinate. |
| [getScalingRateX](#getScalingRateX--) | Restituisce un valore float che indica il fattore di scala della coordinata x durante la trasformazione di un sistema di coordinate. |
| [getScalingRateY](#getScalingRateY--) | Restituisce un valore float che indica il fattore di scala della coordinata y durante la trasformazione di un sistema di coordinate. |
| [getSkewAngleX](#getSkewAngleX--) | Restituisce un valore float che indica l'angolo di inclinazione della coordinata x durante la trasformazione di un sistema di coordinate. |
| [getSkewAngleY](#getSkewAngleY--) | Restituisce un valore float che indica l'angolo di inclinazione della coordinata y durante la trasformazione di un sistema di coordinate. |
| [getX](#getX--) | Recupera la coordinata X di un bordo verticale quando si utilizza TableAbsorber e restituisce "-1" per un bordo orizzontale. |
| [getY](#getY--) | Recupera la coordinata Y di un bordo orizzontale quando si utilizza TableAbsorber e restituisce "-1" per un bordo verticale. |
| [isDoubled](#isDoubled--) | Restituisce se il bordo è raddoppiato. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Imposta un oggetto {@code Color} che indica il colore del grafico. |
| [setDashArray](#setDashArray-int:A-) | Imposta un array di dash. |
| [setDashPhase](#setDashPhase-int-) | Imposta una fase di dash. |
| [setDoubled](#setDoubled-boolean-) | Imposta se il bordo è raddoppiato. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Imposta un oggetto {@code Color} che indica il colore di riempimento del grafico. |
| [setLineWidth](#setLineWidth-float-) | Imposta un valore float che indica lo spessore della linea del grafico. |
| [setRotationAngle](#setRotationAngle-double-) | Imposta un valore float che indica l'angolo di rotazione del sistema di coordinate durante la trasformazione di un sistema di coordinate. |
| [setScalingRateX](#setScalingRateX-double-) | Imposta un valore float che indica il fattore di scala della coordinata x durante la trasformazione di un sistema di coordinate. |
| [setScalingRateY](#setScalingRateY-double-) | Imposta un valore float che indica il fattore di scala della coordinata y durante la trasformazione di un sistema di coordinate. |
| [setSkewAngleX](#setSkewAngleX-double-) | Imposta un valore float che indica l'angolo di inclinazione della coordinata x durante la trasformazione di un sistema di coordinate. |
| [setSkewAngleY](#setSkewAngleY-double-) | Imposta un valore float che indica l'angolo di inclinazione della coordinata y durante la trasformazione di un sistema di coordinate. |

### GraphInfo {#GraphInfo--}
```
public GraphInfo()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona le informazioni grafiche.

**Returns:**
L'oggetto clonato

### getColor {#getColor--}
```
public Color getColor()
```

Restituisce un oggetto {@code Color} che indica il colore del grafico.

**Returns:**
oggetto che indica il colore

### getDashArray {#getDashArray--}
```
public int[] getDashArray()
```

Restituisce un array di trattini.

**Returns:**
array di dash

### getDashPhase {#getDashPhase--}
```
public int getDashPhase()
```

Restituisce una fase di trattino.

**Returns:**
fase di dash.

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Restituisce un oggetto {@code Color} che indica il colore di riempimento del grafico.

**Returns:**
oggetto che indica il colore di riempimento

### getLineWidth {#getLineWidth--}
```
public float getLineWidth()
```

Restituisce un valore float che indica lo spessore della linea del grafico.

**Returns:**
valore che indica lo spessore della linea.

### getRotationAngle {#getRotationAngle--}
```
public double getRotationAngle()
```

Restituisce un valore float che indica l'angolo di rotazione del sistema di coordinate durante la trasformazione di un sistema di coordinate.

**Returns:**
valore double

### getScalingRateX {#getScalingRateX--}
```
public double getScalingRateX()
```

Restituisce un valore float che indica il fattore di scala della coordinata x durante la trasformazione di un sistema di coordinate.

**Returns:**
valore double

### getScalingRateY {#getScalingRateY--}
```
public double getScalingRateY()
```

Restituisce un valore float che indica il fattore di scala della coordinata y durante la trasformazione di un sistema di coordinate.

**Returns:**
valore double

### getSkewAngleX {#getSkewAngleX--}
```
public double getSkewAngleX()
```

Restituisce un valore float che indica l'angolo di inclinazione della coordinata x durante la trasformazione di un sistema di coordinate.

**Returns:**
valore double

### getSkewAngleY {#getSkewAngleY--}
```
public double getSkewAngleY()
```

Restituisce un valore float che indica l'angolo di inclinazione della coordinata y durante la trasformazione di un sistema di coordinate.

**Returns:**
valore double

### getX {#getX--}
```
public final double getX()
```

Recupera la coordinata X di un bordo verticale quando si utilizza TableAbsorber e restituisce "-1" per un bordo orizzontale.

**Returns:**
valore double

### getY {#getY--}
```
public final double getY()
```

Recupera la coordinata Y di un bordo orizzontale quando si utilizza TableAbsorber e restituisce "-1" per un bordo verticale.

**Returns:**
valore double

### isDoubled {#isDoubled--}
```
public boolean isDoubled()
```

Restituisce se il bordo è raddoppiato.

**Returns:**
valore booleano

### setColor {#setColor-com.aspose.pdf.Color-}
Imposta un oggetto {@code Color} che indica il colore del grafico.

### setDashArray {#setDashArray-int:A-}
```
public void setDashArray(int[] value)
```

Imposta un array di dash.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | array di dash |

### setDashPhase {#setDashPhase-int-}
```
public void setDashPhase(int value)
```

Imposta una fase di dash.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | fase di dash. |

### setDoubled {#setDoubled-boolean-}
```
public void setDoubled(boolean value)
```

Imposta se il bordo è raddoppiato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Imposta un oggetto {@code Color} che indica il colore di riempimento del grafico.

### setLineWidth {#setLineWidth-float-}
```
public void setLineWidth(float value)
```

Imposta un valore float che indica lo spessore della linea del grafico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore che indica lo spessore della linea. |

### setRotationAngle {#setRotationAngle-double-}
```
public void setRotationAngle(double value)
```

Imposta un valore float che indica l'angolo di rotazione del sistema di coordinate durante la trasformazione di un sistema di coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setScalingRateX {#setScalingRateX-double-}
```
public void setScalingRateX(double value)
```

Imposta un valore float che indica il fattore di scala della coordinata x durante la trasformazione di un sistema di coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setScalingRateY {#setScalingRateY-double-}
```
public void setScalingRateY(double value)
```

Imposta un valore float che indica il fattore di scala della coordinata y durante la trasformazione di un sistema di coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setSkewAngleX {#setSkewAngleX-double-}
```
public void setSkewAngleX(double value)
```

Imposta un valore float che indica l'angolo di inclinazione della coordinata x durante la trasformazione di un sistema di coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setSkewAngleY {#setSkewAngleY-double-}
```
public void setSkewAngleY(double value)
```

Imposta un valore float che indica l'angolo di inclinazione della coordinata y durante la trasformazione di un sistema di coordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |
