---
title: "IconFit"
linktitle: "IconFit"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Descrive come l'icona dell'annotazione widget deve essere visualizzata all'interno del suo rettangolo di annotazione."
type: docs
weight: 2210
url: /it/java/com.aspose.pdf/iconfit/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IconFit

```
public final class IconFit extends Object
```

Descrive come l'icona dell'annotazione widget deve essere visualizzata all'interno del suo rettangolo di annotazione.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLeftoverBottom](#getLeftoverBottom--) | Ottiene lo spazio da allocare nella parte inferiore dell'icona. |
| [getLeftoverLeft](#getLeftoverLeft--) | Ottiene lo spazio da allocare a sinistra dell'icona. |
| [getScalingMode](#getScalingMode--) | Il tipo di scala da utilizzare. |
| [getScalingReason](#getScalingReason--) | Ottiene il motivo di ridimensionamento. |
| [isSpreadOnBorder](#isSpreadOnBorder--) | Se true, indica che l'aspetto del pulsante deve essere scalato per adattarsi completamente ai limiti dell'annotazione senza considerare lo spessore della linea del bordo. |
| [nameToScalingMode](#nameToScalingMode-java.lang.String-) | Converte il nome della modalità di scaling in un oggetto ScalingMode. |
| [nameToScalingReason](#nameToScalingReason-java.lang.String-) | Converte il nome del motivo di scaling in un oggetto ScalingReason. |
| [scalingModeToName](#scalingModeToName-int-) | Converte l'oggetto della modalità di scaling in nome. |
| [scalingReasonToName](#scalingReasonToName-int-) | Converte l'oggetto del motivo di scaling in nome. |
| [setLeftoverBottom](#setLeftoverBottom-double-) | Imposta lo spazio da allocare nella parte inferiore dell'icona. |
| [setLeftoverLeft](#setLeftoverLeft-double-) | Imposta lo spazio da allocare a sinistra dell'icona. |
| [setScalingMode](#setScalingMode-int-) | Il tipo di scala da utilizzare. |
| [setScalingReason](#setScalingReason-int-) | Imposta il motivo di scaling. |
| [setSpreadOnBorder](#setSpreadOnBorder-boolean-) | Se true, indica che l'aspetto del pulsante deve essere scalato per adattarsi completamente ai limiti dell'annotazione senza considerare lo spessore della linea del bordo. |

### getLeftoverBottom {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```

Ottiene lo spazio da allocare nella parte inferiore dell'icona.

**Returns:**
spazio da allocare nella parte inferiore

### getLeftoverLeft {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```

Ottiene lo spazio da allocare a sinistra dell'icona.

**Returns:**
spazio da allocare a sinistra dell'icona.

### getScalingMode {#getScalingMode--}
```
public int getScalingMode()
```

Il tipo di scala da utilizzare.

**Returns:**
Valore ScalingMode @see ScalingMode

### getScalingReason {#getScalingReason--}
```
public int getScalingReason()
```

Ottiene il motivo di ridimensionamento.

**Returns:**
Valore ScalingReason @see ScalingReason

### isSpreadOnBorder {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```

Se true, indica che l'aspetto del pulsante deve essere scalato per adattarsi completamente ai limiti dell'annotazione senza considerare lo spessore della linea del bordo.

**Returns:**
valore booleano

### nameToScalingMode {#nameToScalingMode-java.lang.String-}
Converte il nome della modalità di scaling in un oggetto ScalingMode.

### nameToScalingReason {#nameToScalingReason-java.lang.String-}
Converte il nome del motivo di scaling in un oggetto ScalingReason.

### scalingModeToName {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```

Converte l'oggetto della modalità di scaling in nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modalità |  | Oggetto della modalità di scaling. |

**Returns:**
Nome della modalità di scaling.

### scalingReasonToName {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```

Converte l'oggetto del motivo di scaling in nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| motivo |  | Oggetto motivo di scaling da convertire. |

**Returns:**
Nome del motivo di scaling.

### setLeftoverBottom {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```

Imposta lo spazio da allocare nella parte inferiore dell'icona.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | spazio da allocare nella parte inferiore |

### setLeftoverLeft {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```

Imposta lo spazio da allocare a sinistra dell'icona.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | spazio da allocare a sinistra dell'icona. |

### setScalingMode {#setScalingMode-int-}
```
public void setScalingMode(int value)
```

Il tipo di scala da utilizzare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore ScalingMode @see ScalingMode |

### setScalingReason {#setScalingReason-int-}
```
public void setScalingReason(int value)
```

Imposta il motivo di scaling.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore ScalingReason @see ScalingReason |

### setSpreadOnBorder {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```

Se true, indica che l'aspetto del pulsante deve essere scalato per adattarsi completamente ai limiti dell'annotazione senza considerare lo spessore della linea del bordo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
