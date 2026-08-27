---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta il livello di grigio per operazioni di tracciatura."
type: docs
weight: 650
url: /it/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

Classe che rappresenta il livello di grigio per operazioni di tracciatura.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | Inizializza l'operatore con il colore specificato. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getColor](#getColor--) | Restituisce il colore specificato dall'operatore. |
| [getGray](#getGray--) | Ottiene o imposta il livello del valore di grigio. |
| [setGray](#setGray-double-) | Ottiene o imposta il livello del valore di grigio. |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

Inizializza l'operatore con il colore specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| grigio |  | Il livello del valore di grigio. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getColor {#getColor--}
```
public Color getColor()
```

Restituisce il colore specificato dall'operatore.

**Returns:**
Colore specificato dall'operatore.

### getGray {#getGray--}
```
public final double getGray()
```

Ottiene o imposta il livello del valore di grigio.

**Returns:**
valore double

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Ottiene o imposta il livello del valore di grigio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.
