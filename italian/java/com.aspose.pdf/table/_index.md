---
title: "Tabella"
linktitle: "Tabella"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una tabella che può essere aggiunta alla pagina."
type: docs
weight: 4790
url: /it/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

Rappresenta una tabella che può essere aggiunta alla pagina.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Table](#Table--) | Costruttore predefinito |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | / * / * Importa un array monodimensionale di dati nella tabella. L'importazione inserisce una cella per ogni elemento dell'array e / * inizia dalla riga e colonna definite nei parametri. Durante l'importazione, se si rileva che le righe necessarie / * sono ancora assenti (cioè la tabella di destinazione è troppo piccola per assorbire tutti i dati), le righe necessarie saranno create / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | Aggiungi operatori per il rettangolo. |
| [getAlignment](#getAlignment--) | Restituisce l'allineamento della tabella. |
| [getBackgroundColor](#getBackgroundColor--) | Restituisce il colore di sfondo della tabella |
| [getBorder](#getBorder--) | Ottiene il bordo. |
| [getBreakText](#getBreakText--) | Restituisce il testo di interruzione per la tabella |
| [getBroken](#getBroken--) | Ottiene o imposta la rottura verticale della tabella; |
| [getColumnAdjustment](#getColumnAdjustment--) | Restituisce la regolazione della colonna della tabella. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | Ottieni la larghezza della colonna |
| [getColumnWidths](#getColumnWidths--) | Restituisce le larghezze delle colonne della tabella. |
| [getCornerStyle](#getCornerStyle--) | Restituisce gli stili degli angoli del bordo |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Restituisce il bordo predefinito della cella; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Restituisce il padding predefinito della cella. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Restituisce lo stato del testo predefinito della cella. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Restituisce il bordo predefinito della cella; |
| [getHeight](#getHeight--) | Ottieni l'altezza. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | Ottieni l'altezza. |
| [getLeft](#getLeft--) | Restituisce la coordinata sinistra della tabella. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Ottiene o imposta il conteggio massimo di colonne per la tabella |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Restituisce il conteggio delle prime righe ripetute per più pagine |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Restituisce lo stile per le righe ripetute |
| [getRows](#getRows--) | Restituisce le righe della tabella. |
| [getTop](#getTop--) | Ottiene la coordinata superiore della tabella. |
| [getWidth](#getWidth--) | Ottieni la larghezza. |
| [isBordersIncluded](#isBordersIncluded--) | Ottiene il bordo incluso nelle larghezze delle colonne. |
| [isBroken](#isBroken--) | Ottiene se la tabella è interrotta - verrà troncata per la pagina successiva. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta l'allineamento della tabella. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Imposta il colore di sfondo della tabella |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Imposta il bordo. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Imposta il bordo incluso nelle larghezze delle colonne. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | Imposta il testo di interruzione per la tabella |
| [setBroken](#setBroken-boolean-) | Imposta la tabella come interrotta - verrà troncata per la pagina successiva. |
| [setBroken](#setBroken-int-) | Ottiene o imposta la rottura verticale della tabella; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Imposta la regolazione delle colonne della tabella. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | Imposta l'altezza. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Restituisce le larghezze delle colonne della tabella. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Ottiene o imposta gli stili degli angoli del bordo |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Restituisce il bordo predefinito della cella; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Imposta il padding predefinito della cella. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Imposta lo stato predefinito del testo della cella. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Restituisce il bordo predefinito della cella; |
| [setLeft](#setLeft-float-) | Imposta la coordinata sinistra della tabella. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Ottiene o imposta il conteggio massimo di colonne per la tabella |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Restituisce il conteggio delle prime righe ripetute per più pagine |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Restituisce lo stile per le righe ripetute |
| [setTop](#setTop-float-) | Imposta la coordinata superiore della tabella. |

### Table {#Table--}
```
public Table()
```

Costruttore predefinito

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * Importa un array monodimensionale di dati nella tabella. L'importazione inserisce una cella per ogni elemento dell'array e / * inizia dalla riga e colonna definite nei parametri. Durante l'importazione, se si rileva che le righe necessarie / * sono ancora assenti (cioè la tabella di destinazione è troppo piccola per assorbire tutti i dati), le righe necessarie saranno create / * / *

**Returns:**
L'oggetto clonato

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
Aggiungi operatori per il rettangolo.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Restituisce l'allineamento della tabella.

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Restituisce il colore di sfondo della tabella

**Returns:**
oggetto Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Ottiene il bordo.

**Returns:**
Oggetto BorderInfo

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

Restituisce il testo di interruzione per la tabella

**Returns:**
Oggetto TextFragment

### getBroken {#getBroken--}
```
public final int getBroken()
```

Ottiene o imposta la rottura verticale della tabella;

**Returns:**
Valore TableBroken @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Restituisce la regolazione della colonna della tabella.

**Returns:**
Valore ColumnAdjustment @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
Ottieni la larghezza della colonna

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

Restituisce gli stili degli angoli del bordo

**Returns:**
Valore BorderCornerStyle @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Restituisce il bordo predefinito della cella;

**Returns:**
Oggetto BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Restituisce il padding predefinito della cella.

**Returns:**
Oggetto MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Restituisce lo stato del testo predefinito della cella.

**Returns:**
Valore TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Restituisce il bordo predefinito della cella;

**Returns:**
Oggetto stringa

### getHeight {#getHeight--}
```
public double getHeight()
```

Ottieni l'altezza.

**Returns:**
L'altezza della tabella

### getHeight {#getHeight-com.aspose.pdf.Page-}
Ottieni l'altezza.

**Returns:**
L'altezza della tabella

### getLeft {#getLeft--}
```
public final float getLeft()
```

Restituisce la coordinata sinistra della tabella.

**Returns:**
valore float

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Ottiene o imposta il conteggio massimo di colonne per la tabella

**Returns:**
valore int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Restituisce il conteggio delle prime righe ripetute per più pagine

**Returns:**
valore int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Restituisce lo stile per le righe ripetute

**Returns:**
Oggetto TextState

### getRows {#getRows--}
```
public final Rows getRows()
```

Restituisce le righe della tabella.

**Returns:**
Oggetto Rows

### getTop {#getTop--}
```
public final float getTop()
```

Ottiene la coordinata superiore della tabella.

**Returns:**
valore float

### getWidth {#getWidth--}
```
public double getWidth()
```

Ottieni la larghezza.

**Returns:**
La larghezza della tabella

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Ottiene il bordo incluso nelle larghezze delle colonne.

**Returns:**
valore booleano

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Ottiene se la tabella è interrotta - verrà troncata per la pagina successiva.

**Returns:**
valore booleano

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta l'allineamento della tabella.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Imposta il colore di sfondo della tabella

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Imposta il bordo.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Imposta il bordo incluso nelle larghezze delle colonne.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
Imposta il testo di interruzione per la tabella

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Imposta la tabella come interrotta - verrà troncata per la pagina successiva.

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
| valore |  | Valore TableBroken @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Imposta la regolazione delle colonne della tabella.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
Imposta l'altezza.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Restituisce le larghezze delle colonne della tabella.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Ottiene o imposta gli stili degli angoli del bordo

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Restituisce il bordo predefinito della cella;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Imposta il padding predefinito della cella.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Imposta lo stato predefinito del testo della cella.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Restituisce il bordo predefinito della cella;

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Imposta la coordinata sinistra della tabella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Ottiene o imposta il conteggio massimo di colonne per la tabella

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Restituisce il conteggio delle prime righe ripetute per più pagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Restituisce lo stile per le righe ripetute

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Imposta la coordinata superiore della tabella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |
