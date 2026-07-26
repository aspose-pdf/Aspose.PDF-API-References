---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore cm (concatena la matrice alla matrice di trasformazione corrente)."
type: docs
weight: 140
url: /it/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

Classe che rappresenta l'operatore cm (concatena la matrice alla matrice di trasformazione corrente).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | Costruttore per la classe operatore. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | Costruttore per la classe operatore. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Inizializza l'operatore tramite matrice. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getMatrix](#getMatrix--) | Argomento matrice dell'operatore. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argomento matrice dell'operatore. |
| [toCommand](#toCommand--) | Solo per uso interno! |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

Costruttore per la classe operatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a |  | coefficiente A |
| b |  | coefficiente B |
| c |  | coefficiente C |
| d |  | coefficiente D |
| e |  | coefficiente E |
| f |  | coefficiente F |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
Costruttore per la classe operatore.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
Inizializza l'operatore tramite matrice.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Argomento matrice dell'operatore.

**Returns:**
Oggetto Matrix

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Argomento matrice dell'operatore.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Solo per uso interno!

**Returns:**
ICommand valore oggetto ICommand

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale della rappresentazione
