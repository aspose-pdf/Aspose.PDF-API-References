---
title: "GraphicState"
linktitle: "GraphicState"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta lo stato grafico dell'attuale {@link GraphicElement}."
type: docs
weight: 40
url: /it/java/com.aspose.pdf.vector/graphicstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicState

```
public class GraphicState extends Object
```

Rappresenta lo stato grafico dell'attuale {@link GraphicElement}.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getClipsAndMatrices](#getClipsAndMatrices--) | Restituisce gli operatori che rappresentano clip e matrici di concatenazione. |
| [getColorsAndStyles](#getColorsAndStyles--) | Restituisce gli operatori che rappresentano spazi colore, colori e stili di linea. |
| [getMatrix](#getMatrix--) | Restituisce la matrice di trasformazione corrente. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Restituisce la matrice di trasformazione corrente. |

### getClipsAndMatrices {#getClipsAndMatrices--}
```
public final List < Operator > getClipsAndMatrices()
```

Restituisce gli operatori che rappresentano clip e matrici di concatenazione.

**Returns:**
Elenco di istanze Operator

### getColorsAndStyles {#getColorsAndStyles--}
```
public final com.aspose.ms.System.Collections.Generic.SortedDictionary< Byte , Operator > getColorsAndStyles()
```

Restituisce gli operatori che rappresentano spazi colore, colori e stili di linea.

**Returns:**
Istanza di SortedDictionary

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Restituisce la matrice di trasformazione corrente.

**Returns:**
Istanza della matrice

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Restituisce la matrice di trasformazione corrente.
