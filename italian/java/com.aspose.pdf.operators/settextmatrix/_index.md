---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore Tm (imposta la matrice del testo)."
type: docs
weight: 750
url: /it/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Classe che rappresenta l'operatore Tm (imposta la matrice del testo).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | Inizializza l'operatore. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | Inizializza l'operatore. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | Inizializza l'operatore tramite matrice. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getMatrix](#getMatrix--) | Argomento matrice dell'operatore. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argomento matrice dell'operatore. |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Inizializza l'operatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a |  | coefficiente A |
| b |  | coefficiente B |
| c |  | coefficiente C |
| d |  | coefficiente D |
| e |  | coefficiente E |
| f |  | coefficiente F |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
Inizializza l'operatore.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
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

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.
