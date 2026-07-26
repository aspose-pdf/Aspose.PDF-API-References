---
title: "SetColorStroke"
linktitle: "SetColorStroke"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore SC (imposta il colore per gli operatori di colore di tracciatura)."
type: docs
weight: 600
url: /it/java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColorStroke

```
public class SetColorStroke extends BasicSetColorOperator
```

Classe che rappresenta l'operatore SC (imposta il colore per gli operatori di colore di tracciatura).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetColorStroke](#SetColorStroke--) | Inizializza l'operatore. |
| [SetColorStroke](#SetColorStroke-double-) | Imposta il colore per gli operatori di tracciatura per gli spazi colore DeviceGray, CalGray e Indexed. |
| [SetColorStroke](#SetColorStroke-double:A-) | Costruttore che consente di impostare i componenti del colore. |
| [SetColorStroke](#SetColorStroke-double-double-double-) | Imposta il colore per l'operatore di tracciatura per gli spazi colore DeviceRGB, CalRGB e Lab. |
| [SetColorStroke](#SetColorStroke-double-double-double-double-) | Imposta il colore per l'operatore di tracciatura per lo spazio colore CMYK. |
| [SetColorStroke](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-) | Inizializza l'operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getB](#getB--) | Ottiene o imposta il componente blu. Valore: il livello di blu da 0.0 a 1.0 |
| [getC](#getC--) | Ottiene o imposta il componente ciano. |
| [getColor](#getColor--) | Restituisce il colore specificato dall'operatore. |
| [getG](#getG--) | Ottiene o imposta il componente verde. Valore: il livello di verde da 0.0 a 1.0 |
| [getK](#getK--) | Ottiene o imposta il componente nero. |
| [getM](#getM--) | Ottiene o imposta il componente magenta. |
| [getR](#getR--) | Ottiene o imposta il componente rosso. Valore: il livello di rosso da 0.0 a 1.0 |
| [getY](#getY--) | Ottiene o imposta il componente giallo. |
| [setB](#setB-double-) | Ottiene o imposta il componente blu. Valore: il livello di blu da 0.0 a 1.0 |
| [setC](#setC-double-) | Ottiene o imposta il componente ciano. |
| [setG](#setG-double-) | Ottiene o imposta il componente verde. Valore: il livello di verde da 0.0 a 1.0 |
| [setK](#setK-double-) | Ottiene o imposta il componente nero. |
| [setM](#setM-double-) | Ottiene o imposta il componente magenta. |
| [setR](#setR-double-) | Ottiene o imposta il componente rosso. Valore: il livello di rosso da 0.0 a 1.0 |
| [setY](#setY-double-) | Ottiene o imposta il componente giallo. |

### SetColorStroke {#SetColorStroke--}
```
public SetColorStroke()
```

Inizializza l'operatore.

### SetColorStroke {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```

Imposta il colore per gli operatori di tracciatura per gli spazi colore DeviceGray, CalGray e Indexed.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g |  | Valore colore. |

### SetColorStroke {#SetColorStroke-double:A-}
```
public SetColorStroke(double[] color)
```

Costruttore che consente di impostare i componenti del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colore |  | Array di componenti del colore. |

### SetColorStroke {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```

Imposta il colore per l'operatore di tracciatura per gli spazi colore DeviceRGB, CalRGB e Lab.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| r |  | Componente rosso. |
| g |  | Componente verde. |
| b |  | Componente blu. |

### SetColorStroke {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```

Imposta il colore per l'operatore di tracciatura per lo spazio colore CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c |  | Componente ciano. |
| m |  | Componente magenta. |
| y |  | Componente giallo. |
| k |  | Componente nero. |

### SetColorStroke {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-}
Inizializza l'operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getB {#getB--}
```
public final double getB()
```

Ottiene o imposta il componente blu. Valore: il livello di blu da 0.0 a 1.0

**Returns:**
valore realizzabile

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

### getR {#getR--}
```
public final double getR()
```

Ottiene o imposta il componente rosso. Valore: il livello di rosso da 0.0 a 1.0

**Returns:**
valore realizzabile

### getY {#getY--}
```
public final double getY()
```

Ottiene o imposta il componente giallo.

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

### setC {#setC-double-}
```
public final void setC(double value)
```

Ottiene o imposta il componente ciano.

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
| valore |  | valore double |

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

### setR {#setR-double-}
```
public final void setR(double value)
```

Ottiene o imposta il componente rosso. Valore: il livello di rosso da 0.0 a 1.0

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
