---
title: "SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore RG (imposta il colore RGB per gli operatori di tracciatura)."
type: docs
weight: 720
url: /it/java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColorStroke

```
public class SetRGBColorStroke extends SetColorOperator
```

Classe che rappresenta l'operatore RG (imposta il colore RGB per gli operatori di tracciatura).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetRGBColorStroke](#SetRGBColorStroke-java.awt.Color-) | Inizializza l'operatore con colore. |
| [SetRGBColorStroke](#SetRGBColorStroke-double-double-double-) | Costruttore per il programma di scrittura. |
| [SetRGBColorStroke](#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getB](#getB--) | Ottiene o imposta il componente blu. Valore: il livello di blu da 0.0 a 1.0 |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | Restituisce il colore specificato dall'operatore. |
| [getG](#getG--) | Ottiene o imposta il componente verde. Valore: il livello di verde da 0.0 a 1.0 |
| [getR](#getR--) | Ottiene o imposta il componente rosso. Valore: il livello di rosso da 0.0 a 1.0 |
| [setB](#setB-double-) | Ottiene o imposta il componente blu. Valore: il livello di blu da 0.0 a 1.0 |
| [setG](#setG-double-) | Ottiene o imposta il componente verde. Valore: il livello di verde da 0.0 a 1.0 |
| [setR](#setR-double-) | Ottiene o imposta il componente rosso. Valore: il livello di rosso da 0.0 a 1.0 |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### SetRGBColorStroke {#SetRGBColorStroke-java.awt.Color-}
Inizializza l'operatore con colore.

### SetRGBColorStroke {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```

Costruttore per il programma di scrittura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| r |  | Il livello di rosso da 0.0 a 1.0 |
| g |  | Il livello di verde da 0.0 a 1.0 |
| b |  | Il livello di blu da 0.0 a 1.0 |

### SetRGBColorStroke {#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getB {#getB--}
```
public final double getB()
```

Ottiene o imposta il componente blu. Valore: il livello di blu da 0.0 a 1.0

**Returns:**
valore realizzabile

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

### getColor {#getColor--}
```
public Color getColor()
```

Restituisce il colore specificato dall'operatore.

**Returns:**
Colore specificato dall'operatore.

### getG {#getG--}
```
public final double getG()
```

Ottiene o imposta il componente verde. Valore: il livello di verde da 0.0 a 1.0

**Returns:**
valore realizzabile

### getR {#getR--}
```
public final double getR()
```

Ottiene o imposta il componente rosso. Valore: il livello di rosso da 0.0 a 1.0

**Returns:**
valore realizzabile

### setB {#setB-double-}
```
public final void setB(double value)
```

Ottiene o imposta il componente blu. Valore: il livello di blu da 0.0 a 1.0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore realizzabile |

### setG {#setG-double-}
```
public final void setG(double value)
```

Ottiene o imposta il componente verde. Valore: il livello di verde da 0.0 a 1.0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore realizzabile |

### setR {#setR-double-}
```
public final void setR(double value)
```

Ottiene o imposta il componente rosso. Valore: il livello di rosso da 0.0 a 1.0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore realizzabile |

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.
