---
title: "Curve"
linktitle: "Curve"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una curva Bézier."
type: docs
weight: 30
url: /it/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

Rappresenta una curva Bézier.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Curve](#Curve--) | Solo per uso interno |
| [Curve](#Curve-float:A-) | Inizializza una nuova istanza della classe {@code Curve}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se l'elemento si adatta alle dimensioni del contenitore specificate (inclusivo). |
| [getPositionArray](#getPositionArray--) | Ottiene un array di posizioni float. |
| [setPositionArray](#setPositionArray-float:A-) | Imposta un array di posizioni float. |

### Curve {#Curve--}
```
public Curve()
```

Solo per uso interno

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

Inizializza una nuova istanza della classe {@code Curve}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| positionArray |  | L'array di posizioni dei punti di controllo della curva. Dovrebbero esserci quattro punti di controllo, quindi la lunghezza dell'array dovrebbe essere otto. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Verifica se l'elemento si adatta alle dimensioni del contenitore specificate (inclusivo).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Vero se si adatta; altrimenti, falso.

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

Ottiene un array di posizioni float.

**Returns:**
float[] array

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Imposta un array di posizioni float.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | float[] array |
