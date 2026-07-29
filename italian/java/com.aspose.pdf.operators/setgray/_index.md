---
title: "SetGray"
linktitle: "SetGray"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Imposta il livello di grigio per operazioni non di tracciatura."
type: docs
weight: 640
url: /it/java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

Imposta il livello di grigio per operazioni non di tracciatura.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetGray](#SetGray-double-) | Costruttore per il programma di scrittura. |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getColor](#getColor--) | Restituisce il colore specificato dall'operatore. |
| [getGray](#getGray--) | Ottiene o imposta il livello del valore di grigio. |
| [setGray](#setGray-double-) | Ottiene o imposta il livello del valore di grigio. |
| [toString](#toString--) | Restituisce la rappresentazione stringa dell'operatore. |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

Costruttore per il programma di scrittura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| grigio |  | Il livello del valore di grigio. |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
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

Restituisce la rappresentazione stringa dell'operatore.

**Returns:**
Rappresentazione stringa dell'operatore.
