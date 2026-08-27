---
title: "Shape"
linktitle: "Shape"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la forma - l'oggetto grafico di base."
type: docs
weight: 130
url: /it/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

Rappresenta la forma - l'oggetto grafico di base.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Shape](#Shape--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se l'elemento si adatta alle dimensioni del contenitore specificate (inclusivo). |
| [getGraphInfo](#getGraphInfo--) | Ottiene l'oggetto che indica le informazioni del grafico, come colore, larghezza della linea, ecc. |
| [getText](#getText--) | Ottiene o imposta un testo per la shape |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Imposta l'oggetto che indica le informazioni del grafico, come colore, larghezza della linea, ecc. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | Ottiene o imposta un testo per la shape |

### Shape {#Shape--}
```
public Shape()
```



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

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Ottiene l'oggetto che indica le informazioni del grafico, come colore, larghezza della linea, ecc.

**Returns:**
oggetto che indica le informazioni del grafico.

### getText {#getText--}
```
public TextFragment getText()
```

Ottiene o imposta un testo per la shape

**Returns:**
Oggetto TextFragment

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Imposta l'oggetto che indica le informazioni del grafico, come colore, larghezza della linea, ecc.

### setText {#setText-com.aspose.pdf.TextFragment-}
Ottiene o imposta un testo per la shape
