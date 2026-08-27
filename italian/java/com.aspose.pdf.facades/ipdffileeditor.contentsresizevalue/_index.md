---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Valore del margine o della dimensione del contenuto specificato in percentuale delle unità di spazio predefinite. Questa classe è utilizzata in ContentsResizeParameters."
type: docs
weight: 310
url: /it/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Valore del margine o della dimensione del contenuto specificato in percentuale delle unità di spazio predefinite. Questa classe è utilizzata in ContentsResizeParameters.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [auto](#auto--) | Inizializza il valore calcolato automaticamente. |
| [getValue](#getValue--) | Ottiene il valore specificato. Usa la proprietà Unit per ottenere le unità del valore. |
| [isPercent](#isPercent--) | Restituisce true se il valore è espresso in percentuale; False se il valore è espresso nelle unità predefinite. |
| [percents](#percents-double-) | Inizializza il valore in percentuale. |
| [setPercentValue](#setPercentValue-double-) | Imposta il valore in percentuale rispetto alle dimensioni della pagina. |
| [setUnitValue](#setUnitValue-double-) | Imposta il valore nelle unità di spazio predefinite. |
| [units](#units-double-) | Inizializza il valore nelle unità di spazio predefinite. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Inizializza il valore calcolato automaticamente.

**Returns:**
Nuova istanza di valore.

### getValue {#getValue--}
```
public final double getValue()
```

Ottiene il valore specificato. Usa la proprietà Unit per ottenere le unità del valore.

**Returns:**
valore double

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Restituisce true se il valore è espresso in percentuale; False se il valore è espresso nelle unità predefinite.

**Returns:**
valore booleano

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Inizializza il valore in percentuale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore in percentuale. |

**Returns:**
Nuova istanza di valore.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Imposta il valore in percentuale rispetto alle dimensioni della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Imposta il valore nelle unità di spazio predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Inizializza il valore nelle unità di spazio predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore in unità. |

**Returns:**
Nuova istanza di valore.
