---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe rappresenta il bordo per gli elementi grafici."
type: docs
weight: 370
url: /it/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

Questa classe rappresenta il bordo per gli elementi grafici.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BorderInfo](#BorderInfo--) | Inizializza una nuova istanza della classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-) | Inizializza una nuova istanza della classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | Inizializza una nuova istanza della classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-) | Inizializza una nuova istanza della classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | Inizializza una nuova istanza della classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | Inizializza una nuova istanza della classe {@code BorderInfo}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Clona un nuovo oggetto BorderInfo. |
| [getBottom](#getBottom--) | Ottiene l'oggetto che indica il bordo inferiore. |
| [getLeft](#getLeft--) | Ottiene l'oggetto {@code GraphInfo} che indica il lato sinistro del bordo. |
| [getRight](#getRight--) | Ottiene l'oggetto {@code GraphInfo} che indica il lato destro del bordo. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | Ottiene il raggio arrotondato del bordo. |
| [getTop](#getTop--) | Ottiene l'oggetto {@code GraphInfo} che indica il bordo superiore. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | Imposta l'oggetto che indica il bordo inferiore. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | Imposta l'oggetto {@code GraphInfo} che indica il lato sinistro del bordo. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | Imposta l'oggetto {@code GraphInfo} che indica il lato destro del bordo. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | Imposta il raggio arrotondato del bordo. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | Imposta l'oggetto {@code GraphInfo} che indica il bordo superiore. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

Inizializza una nuova istanza della classe {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

Inizializza una nuova istanza della classe {@code BorderInfo}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| borderSide |  | Indica le informazioni dei lati del bordo. Per esempio: (BorderSide.Left \ | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
Inizializza una nuova istanza della classe {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

Inizializza una nuova istanza della classe {@code BorderInfo}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| borderSide |  | Indica le informazioni dei lati del bordo. Per esempio: (BorderSide.Left \ | BorderSide.Top). |
| borderWidth |  | La larghezza del bordo. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
Inizializza una nuova istanza della classe {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
Inizializza una nuova istanza della classe {@code BorderInfo}.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona un nuovo oggetto BorderInfo.

**Returns:**
Il nuovo oggetto BorderInfo.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

Ottiene l'oggetto che indica il bordo inferiore.

**Returns:**
inferiore

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

Ottiene l'oggetto {@code GraphInfo} che indica il lato sinistro del bordo.

**Returns:**
oggetto che indica il lato sinistro del bordo.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

Ottiene l'oggetto {@code GraphInfo} che indica il lato destro del bordo.

**Returns:**
oggetto che indica il lato destro del bordo.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

Ottiene il raggio arrotondato del bordo.

**Returns:**
valore

### getTop {#getTop--}
```
public GraphInfo getTop()
```

Ottiene l'oggetto {@code GraphInfo} che indica il bordo superiore.

**Returns:**
oggetto che indica il bordo superiore

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
Imposta l'oggetto che indica il bordo inferiore.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
Imposta l'oggetto {@code GraphInfo} che indica il lato sinistro del bordo.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
Imposta l'oggetto {@code GraphInfo} che indica il lato destro del bordo.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

Imposta il raggio arrotondato del bordo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
Imposta l'oggetto {@code GraphInfo} che indica il bordo superiore.
