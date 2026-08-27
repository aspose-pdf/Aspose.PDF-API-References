---
title: "TableElement"
linktitle: "TableElement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'elemento di struttura Table nella struttura logica."
type: docs
weight: 170
url: /it/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

Rappresenta l'elemento di struttura Table nella struttura logica.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | costruttore solo per uso interno |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Regola posizione. |
| [createTBody](#createTBody--) | Crea {@link TableTHeadElement} e lo aggiunge alla tabella corrente. |
| [createTFoot](#createTFoot--) | Crea {@link TableTFootElement} e lo aggiunge alla tabella corrente. |
| [createTHead](#createTHead--) | Crea {@link TableTHeadElement} e lo aggiunge alla tabella corrente. |
| [getAlignment](#getAlignment--) | Ottiene o imposta l'allineamento della tabella. |
| [getBackgroundColor](#getBackgroundColor--) | Ottiene o imposta il colore di sfondo della tabella. |
| [getBorder](#getBorder--) | Ottiene o imposta il bordo della tabella. |
| [getBroken](#getBroken--) | Ottiene o imposta la rottura verticale della tabella; |
| [getColumnAdjustment](#getColumnAdjustment--) | Ottiene o imposta la regolazione delle colonne della tabella. |
| [getColumnWidths](#getColumnWidths--) | Restituisce le larghezze delle colonne della tabella. |
| [getCornerStyle](#getCornerStyle--) | Ottiene o imposta gli stili degli angoli del bordo |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Ottiene il bordo predefinito della cella. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Ottiene o imposta il padding predefinito della cella. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Ottiene o imposta lo stato di testo predefinito della cella. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Ottiene o imposta la larghezza predefinita della colonna. |
| [getLeft](#getLeft--) | Ottiene o imposta la coordinata sinistra della tabella. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Ottiene o imposta il numero massimo di colonne per la tabella. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Ottiene il conteggio delle prime righe ripetute per più pagine. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Ottiene lo stile per le righe ripetute. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | Ottiene o imposta la coordinata superiore della tabella. |
| [isBordersIncluded](#isBordersIncluded--) | Ottiene o imposta il bordo incluso nelle larghezze delle colonne. |
| [isBroken](#isBroken--) | Ottiene o imposta se la tabella è interrotta - verrà troncata nella pagina successiva. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Ottiene o imposta l'allineamento della tabella. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Ottiene o imposta il colore di sfondo della tabella. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Ottiene o imposta il bordo della tabella. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Ottiene o imposta il bordo incluso nelle larghezze delle colonne. |
| [setBroken](#setBroken-boolean-) | Ottiene o imposta se la tabella è interrotta - verrà troncata nella pagina successiva. |
| [setBroken](#setBroken-int-) | Ottiene o imposta la rottura verticale della tabella; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Ottiene o imposta la regolazione delle colonne della tabella. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Restituisce le larghezze delle colonne della tabella. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Ottiene o imposta gli stili degli angoli del bordo |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Ottiene il bordo predefinito della cella. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Ottiene o imposta il padding predefinito della cella. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Ottiene o imposta lo stato di testo predefinito della cella. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Ottiene o imposta la larghezza predefinita della colonna. |
| [setLeft](#setLeft-float-) | Ottiene o imposta la coordinata sinistra della tabella. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Ottiene o imposta il numero massimo di colonne per la tabella. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Ottiene il conteggio delle prime righe ripetute per più pagine. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Ottiene lo stile per le righe ripetute. |
| [setTop](#setTop-float-) | Ottiene o imposta la coordinata superiore della tabella. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
costruttore solo per uso interno

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Regola posizione.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

Crea {@link TableTHeadElement} e lo aggiunge alla tabella corrente.

**Returns:**
Elemento di struttura creato.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

Crea {@link TableTFootElement} e lo aggiunge alla tabella corrente.

**Returns:**
Elemento di struttura creato.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

Crea {@link TableTHeadElement} e lo aggiunge alla tabella corrente.

**Returns:**
Elemento di struttura creato.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Ottiene o imposta l'allineamento della tabella.

**Returns:**
Elemento HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Ottiene o imposta il colore di sfondo della tabella.

**Returns:**
Istanza di Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Ottiene o imposta il bordo della tabella.

**Returns:**
Istanza BorderInfo

### getBroken {#getBroken--}
```
public final int getBroken()
```

Ottiene o imposta la rottura verticale della tabella;

**Returns:**
Elemento TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Ottiene o imposta la regolazione delle colonne della tabella.

**Returns:**
elemento ColumnAdjustment

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

Restituisce le larghezze delle colonne della tabella.

**Returns:**
valore String

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

Ottiene o imposta gli stili degli angoli del bordo

**Returns:**
elemento BorderCornerStyle

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

Ottiene o imposta il padding predefinito della cella.

**Returns:**
Istanza MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Ottiene o imposta lo stato di testo predefinito della cella.

**Returns:**
istanza TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Ottiene o imposta la larghezza predefinita della colonna.

**Returns:**
valore String

### getLeft {#getLeft--}
```
public final float getLeft()
```

Ottiene o imposta la coordinata sinistra della tabella.

**Returns:**
valore float

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Ottiene o imposta il numero massimo di colonne per la tabella.

**Returns:**
valore int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Ottiene il conteggio delle prime righe ripetute per più pagine.

**Returns:**
valore int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Ottiene lo stile per le righe ripetute.

**Returns:**
istanza TextState

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

Ottiene o imposta la coordinata superiore della tabella.

**Returns:**
valore float

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Ottiene o imposta il bordo incluso nelle larghezze delle colonne.

**Returns:**
valore booleano

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Ottiene o imposta se la tabella è interrotta - verrà troncata nella pagina successiva.

**Returns:**
valore booleano

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Ottiene o imposta l'allineamento della tabella.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Ottiene o imposta il colore di sfondo della tabella.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Ottiene o imposta il bordo della tabella.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Ottiene o imposta il bordo incluso nelle larghezze delle colonne.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Ottiene o imposta se la tabella è interrotta - verrà troncata nella pagina successiva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Ottiene o imposta la rottura verticale della tabella;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Ottiene o imposta la regolazione delle colonne della tabella.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Restituisce le larghezze delle colonne della tabella.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Ottiene o imposta gli stili degli angoli del bordo

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Ottiene il bordo predefinito della cella.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Ottiene o imposta il padding predefinito della cella.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Ottiene o imposta lo stato di testo predefinito della cella.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Ottiene o imposta la larghezza predefinita della colonna.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Ottiene o imposta la coordinata sinistra della tabella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Ottiene o imposta il numero massimo di colonne per la tabella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Ottiene il conteggio delle prime righe ripetute per più pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Ottiene lo stile per le righe ripetute.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Ottiene o imposta la coordinata superiore della tabella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |
