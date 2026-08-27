---
title: "Row"
linktitle: "Row"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una riga della tabella."
type: docs
weight: 4330
url: /it/java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Row

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Row extends Object implements com.aspose.ms.System.ICloneable
```

Rappresenta una riga della tabella.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Row](#Row--) | Inizializza una nuova istanza della classe Row. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Clona la riga. |
| [getBackgroundColor](#getBackgroundColor--) | Ottiene il colore di sfondo. |
| [getBorder](#getBorder--) | Ottiene il bordo. |
| [getCells](#getCells--) | Ottiene il metodo getCells() della riga. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Restituisce il bordo predefinito della cella; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Ottiene il margine predefinito per la riga getCells() |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Ottiene o imposta lo stato di testo predefinito per la riga getCells() Ottiene lo stato di testo predefinito per la riga getCells() |
| [getFixedRowHeight](#getFixedRowHeight--) | Ottiene l'altezza fissa della riga - la riga può avere un'altezza fissa; |
| [getMinRowHeight](#getMinRowHeight--) | Ottiene l'altezza della riga; |
| [getVerticalAlignment](#getVerticalAlignment--) | Ottiene o imposta l'allineamento verticale. |
| [isInNewPage](#isInNewPage--) | Ottiene se la riga fissa è in una nuova pagina - la pagina con questa proprietà dovrebbe essere stampata nella pagina successiva Predefinito false; |
| [isRowBroken](#isRowBroken--) | Ottiene se la riga può essere interrotta tra due pagine |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Imposta il colore di sfondo. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Imposta il bordo. |
| [setCells](#setCells-com.aspose.pdf.Cells-) | Imposta il metodo getCells() della riga. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Imposta il bordo predefinito della cella; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Imposta il margine predefinito per la riga getCells() |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Imposta lo stato di testo predefinito per la riga getCells() |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Imposta l'altezza fissa della riga - la riga può avere un'altezza fissa; |
| [setInNewPage](#setInNewPage-boolean-) | Imposta se la riga può essere interrotta tra due pagine |
| [setMinRowHeight](#setMinRowHeight-double-) | Imposta l'altezza della riga; |
| [setRowBroken](#setRowBroken-boolean-) | Imposta se la riga può essere interrotta tra due pagine |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ottiene o imposta l'allineamento verticale. |

### Row {#Row--}
```
public Row()
```

Inizializza una nuova istanza della classe Row.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona la riga.

**Returns:**
L'oggetto clonato

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Ottiene il colore di sfondo.

**Returns:**
Valore colore

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Ottiene il bordo.

**Returns:**
Valore BorderInfo

### getCells {#getCells--}
```
public Cells getCells()
```

Ottiene il metodo getCells() della riga.

**Returns:**
Valore getCells()

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```

Restituisce il bordo predefinito della cella;

**Returns:**
Valore BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```

Ottiene il margine predefinito per la riga getCells()

**Returns:**
Valore MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Ottiene o imposta lo stato di testo predefinito per la riga getCells() Ottiene lo stato di testo predefinito per la riga getCells()

**Returns:**
Valore TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```

Ottiene l'altezza fissa della riga - la riga può avere un'altezza fissa;

**Returns:**
valore double

### getMinRowHeight {#getMinRowHeight--}
```
public double getMinRowHeight()
```

Ottiene l'altezza della riga;

**Returns:**
valore double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Ottiene o imposta l'allineamento verticale.

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Ottiene se la riga fissa è in una nuova pagina - la pagina con questa proprietà dovrebbe essere stampata nella pagina successiva Predefinito false;

**Returns:**
valore booleano

### isRowBroken {#isRowBroken--}
```
public boolean isRowBroken()
```

Ottiene se la riga può essere interrotta tra due pagine

**Returns:**
valore booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Imposta il colore di sfondo.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Imposta il bordo.

### setCells {#setCells-com.aspose.pdf.Cells-}
Imposta il metodo getCells() della riga.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Imposta il bordo predefinito della cella;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Imposta il margine predefinito per la riga getCells()

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Imposta lo stato di testo predefinito per la riga getCells()

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```

Imposta l'altezza fissa della riga - la riga può avere un'altezza fissa;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Imposta se la riga può essere interrotta tra due pagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMinRowHeight {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```

Imposta l'altezza della riga;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setRowBroken {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```

Imposta se la riga può essere interrotta tra due pagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ottiene o imposta l'allineamento verticale.
