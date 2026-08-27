---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'elemento di struttura TR nella struttura logica della tabella."
type: docs
weight: 240
url: /it/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

Rappresenta l'elemento di struttura TR nella struttura logica della tabella.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | costruttore solo per uso interno |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createTD](#createTD--) | Crea {@link TableTHElement} e lo aggiunge alla tabella corrente. |
| [createTH](#createTH--) | Crea {@link TableTHElement} e lo aggiunge alla tabella corrente. |
| [getBackgroundColor](#getBackgroundColor--) | Ottiene o imposta il colore di sfondo della riga. |
| [getBorder](#getBorder--) | Ottiene o imposta il bordo della riga. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Ottiene il bordo predefinito della cella. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Ottiene o imposta il margine predefinito per le celle della riga. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Ottiene o imposta lo stato di testo predefinito per le celle della riga |
| [getFixedRowHeight](#getFixedRowHeight--) | Ottiene l'altezza fissa della riga - la riga può avere un'altezza fissa. |
| [getMinRowHeight](#getMinRowHeight--) | Ottiene l'altezza della riga. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ottiene o imposta l'allineamento verticale. |
| [isInNewPage](#isInNewPage--) | Ottiene se la riga fissa è in una nuova pagina - la pagina con questa proprietà dovrebbe essere stampata nella pagina successiva. Predefinito false. |
| [isRowBroken](#isRowBroken--) | Ottiene se la riga può essere interrotta tra due pagine. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Ottiene o imposta il colore di sfondo della riga. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Ottiene o imposta il bordo della riga. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Ottiene il bordo predefinito della cella. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Ottiene o imposta il margine predefinito per le celle della riga. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Ottiene o imposta lo stato di testo predefinito per le celle della riga |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Ottiene l'altezza fissa della riga - la riga può avere un'altezza fissa. |
| [setInNewPage](#setInNewPage-boolean-) | Ottiene se la riga fissa è in una nuova pagina - la pagina con questa proprietà dovrebbe essere stampata nella pagina successiva. Predefinito false. |
| [setMinRowHeight](#setMinRowHeight-double-) | Ottiene l'altezza della riga. |
| [setRowBroken](#setRowBroken-boolean-) | Ottiene se la riga può essere interrotta tra due pagine. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ottiene o imposta l'allineamento verticale. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
costruttore solo per uso interno

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

Crea {@link TableTHElement} e lo aggiunge alla tabella corrente.

**Returns:**
Elemento di struttura creato.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

Crea {@link TableTHElement} e lo aggiunge alla tabella corrente.

**Returns:**
Elemento di struttura creato.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Ottiene o imposta il colore di sfondo della riga.

**Returns:**
Istanza di Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Ottiene o imposta il bordo della riga.

**Returns:**
Istanza BorderInfo

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Ottiene il bordo predefinito della cella.

**Returns:**
Istanza BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Ottiene o imposta il margine predefinito per le celle della riga.

**Returns:**
Istanza MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Ottiene o imposta lo stato di testo predefinito per le celle della riga

**Returns:**
istanza TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

Ottiene l'altezza fissa della riga - la riga può avere un'altezza fissa.

**Returns:**
valore double

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

Ottiene l'altezza della riga.

**Returns:**
valore double

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Ottiene o imposta l'allineamento verticale.

**Returns:**
Elemento VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

Ottiene se la riga fissa è in una nuova pagina - la pagina con questa proprietà dovrebbe essere stampata nella pagina successiva. Predefinito false.

**Returns:**
valore booleano

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

Ottiene se la riga può essere interrotta tra due pagine.

**Returns:**
valore booleano

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Ottiene o imposta il colore di sfondo della riga.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Ottiene o imposta il bordo della riga.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Ottiene il bordo predefinito della cella.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Ottiene o imposta il margine predefinito per le celle della riga.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Ottiene o imposta lo stato di testo predefinito per le celle della riga

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

Ottiene l'altezza fissa della riga - la riga può avere un'altezza fissa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

Ottiene se la riga fissa è in una nuova pagina - la pagina con questa proprietà dovrebbe essere stampata nella pagina successiva. Predefinito false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

Ottiene l'altezza della riga.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

Ottiene se la riga può essere interrotta tra due pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ottiene o imposta l'allineamento verticale.
