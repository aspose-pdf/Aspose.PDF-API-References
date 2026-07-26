---
title: "SetCMYKColorStroke"
linktitle: "SetCMYKColorStroke"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore K (imposta il colore CMYK per le operazioni di tracciatura)."
type: docs
weight: 540
url: /it/java/com.aspose.pdf.operators/setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColorStroke

```
public class SetCMYKColorStroke extends SetColorOperator
```

Classe che rappresenta l'operatore K (imposta il colore CMYK per le operazioni di tracciatura).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetCMYKColorStroke](#SetCMYKColorStroke-double-double-double-double-) | Inizializza l'operatore. |
| [SetCMYKColorStroke](#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getC](#getC--) | Ottiene o imposta il componente ciano. |
| [getColor](#getColor--) | Restituisce il colore RGB |
| [getK](#getK--) | Ottiene o imposta il componente nero. |
| [getM](#getM--) | Ottiene o imposta il componente magenta. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Ottiene o imposta il componente giallo. |
| [setC](#setC-double-) | Ottiene o imposta il componente ciano. |
| [setK](#setK-double-) | Ottiene o imposta il componente nero. |
| [setM](#setM-double-) | Ottiene o imposta il componente magenta. |
| [setY](#setY-double-) | Ottiene o imposta il componente giallo. |

### SetCMYKColorStroke {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
```

Inizializza l'operatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c |  | Il livello di ciano da 0.0 a 1.0 |
| m |  | Il livello di magenta da 0.0 a 1.0 |
| y |  | Il livello di giallo da 0.0 a 1.0 |
| k |  | Il livello di nero da 0.0 a 1.0 |

### SetCMYKColorStroke {#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getC {#getC--}
```
public final double getC()
```

Ottiene o imposta il componente ciano.

**Returns:**
valore realizzabile

### getColor {#getColor--}
```
public Color getColor()
```

Restituisce il colore RGB

**Returns:**
Colore specificato dall'operatore.

### getK {#getK--}
```
public final double getK()
```

Ottiene o imposta il componente nero.

**Returns:**
valore realizzabile

### getM {#getM--}
```
public final double getM()
```

Ottiene o imposta il componente magenta.

**Returns:**
valore realizzabile

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

Ottiene o imposta il componente giallo.

**Returns:**
valore realizzabile

### setC {#setC-double-}
```
public final void setC(double value)
```

Ottiene o imposta il componente ciano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore realizzabile |

### setK {#setK-double-}
```
public final void setK(double value)
```

Ottiene o imposta il componente nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore realizzabile |

### setM {#setM-double-}
```
public final void setM(double value)
```

Ottiene o imposta il componente magenta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore realizzabile |

### setY {#setY-double-}
```
public final void setY(double value)
```

Ottiene o imposta il componente giallo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore realizzabile |
