---
title: "Line"
linktitle: "Line"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una linea."
type: docs
weight: 90
url: /it/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

Rappresenta una linea.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Line](#Line--) | Solo per uso interno |
| [Line](#Line-float:A-) | Inizializza una nuova istanza della classe {@code Line}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se l'elemento si adatta alle dimensioni del contenitore specificate (inclusivo). |
| [getPositionArray](#getPositionArray--) | Ottiene l'oggetto che indica l'array di posizione. L'array è composto dalle coordinate di ciascun punto di controllo della linea, direttamente. |
| [setPositionArray](#setPositionArray-float:A-) | Imposta l'oggetto che indica l'array di posizione. L'array è composto dalle coordinate di ciascun punto di controllo della linea, direttamente. |

### Line {#Line--}
```
public Line()
```

Solo per uso interno

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

Inizializza una nuova istanza della classe {@code Line}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| positionArray |  | L'array di posizione della linea. |

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

Ottiene l'oggetto che indica l'array di posizione. L'array è composto dalle coordinate di ciascun punto di controllo della linea, direttamente.

**Returns:**
che indica l'array di posizione.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Imposta l'oggetto che indica l'array di posizione. L'array è composto dalle coordinate di ciascun punto di controllo della linea, direttamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | che indica l'array di posizione. |
