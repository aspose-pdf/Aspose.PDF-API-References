---
title: "Cell"
linktitle: "Cell"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una cella della riga della tabella."
type: docs
weight: 510
url: /it/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

Rappresenta una cella della riga della tabella.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Cell](#Cell--) | Inizializza una nuova istanza della classe Cell. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Inizializza una nuova istanza della classe Cell. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Clona la cella. |
| [getAlignment](#getAlignment--) | Ottiene l'allineamento. |
| [getBackgroundColor](#getBackgroundColor--) | Ottiene il colore di sfondo. |
| [getBackgroundImage](#getBackgroundImage--) | Ottiene o imposta l'immagine di sfondo |
| [getBackgroundImageFile](#getBackgroundImageFile--) | Ottiene il file dell'immagine di sfondo. |
| [getBorder](#getBorder--) | Ottiene il bordo. |
| [getColSpan](#getColSpan--) | Ottiene o imposta l'estensione della colonna. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Restituisce lo stato del testo predefinito della cella. |
| [getMargin](#getMargin--) | Ottiene il riempimento. |
| [getParagraphs](#getParagraphs--) | Ottiene il testo formattato della cella. |
| [getRowSpan](#getRowSpan--) | Ottiene l'estensione della riga. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ottiene l'allineamento verticale. |
| [getWidth](#getWidth--) | Ottiene la larghezza della colonna. |
| [isNoBorder](#isNoBorder--) | Ottiene se la cella ha bordo. |
| [isOverrideByFragment](#isOverrideByFragment--) | Imposta la proprietà TextState della cella è sovrascritta dalla proprietà TextState di TextFragment. |
| [isWordWrapped](#isWordWrapped--) | Ottiene il testo avvolto a capo della cella. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta l'allineamento. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Ottiene o imposta il colore di sfondo. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Ottiene o imposta l'immagine di sfondo |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | Imposta il file dell'immagine di sfondo. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Imposta il bordo. |
| [setColSpan](#setColSpan-int-) | Imposta l'estensione della colonna. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Imposta lo stato predefinito del testo della cella. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Imposta il riempimento. |
| [setNoBorder](#setNoBorder-boolean-) | Imposta se la cella ha bordo. |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | Imposta la proprietà TextState della cella è sovrascritta dalla proprietà TextState di TextFragment. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Imposta il testo formattato della cella. |
| [setRowSpan](#setRowSpan-int-) | Imposta l'estensione della riga. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Imposta l'allineamento verticale. |
| [setWidth](#setWidth-double-) | Imposta la larghezza della colonna. |
| [setWordWrapped](#setWordWrapped-boolean-) | Imposta il testo avvolto a capo della cella. |

### Cell {#Cell--}
```
public Cell()
```

Inizializza una nuova istanza della classe Cell.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Inizializza una nuova istanza della classe Cell.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona la cella.

**Returns:**
L'oggetto clonato

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

Ottiene l'allineamento.

**Returns:**
Elemento HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Ottiene il colore di sfondo.

**Returns:**
oggetto Color

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Ottiene o imposta l'immagine di sfondo

**Returns:**
Istanza immagine

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

Ottiene il file dell'immagine di sfondo.

**Returns:**
Valore stringa @deprecated La proprietà è stata espansa, si prega di usare BackgroundImage

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Ottiene il bordo.

**Returns:**
Oggetto BorderInfo

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

Ottiene o imposta l'estensione della colonna.

**Returns:**
valore int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Restituisce lo stato del testo predefinito della cella.

**Returns:**
Oggetto TextState

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Ottiene il riempimento.

**Returns:**
Oggetto MarginInfo

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Ottiene il testo formattato della cella.

**Returns:**
Oggetto Paragraphs

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

Ottiene l'estensione della riga.

**Returns:**
valore int

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Ottiene l'allineamento verticale.

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Ottiene la larghezza della colonna.

**Returns:**
valore double

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

Ottiene se la cella ha bordo.

**Returns:**
valore booleano

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

Imposta la proprietà TextState della cella è sovrascritta dalla proprietà TextState di TextFragment.

**Returns:**
valore booleano

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

Ottiene il testo avvolto a capo della cella.

**Returns:**
valore booleano

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta l'allineamento.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Ottiene o imposta il colore di sfondo.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Ottiene o imposta l'immagine di sfondo

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
Imposta il file dell'immagine di sfondo.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Imposta il bordo.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

Imposta l'estensione della colonna.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Imposta lo stato predefinito del testo della cella.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Imposta il riempimento.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

Imposta se la cella ha bordo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

Imposta la proprietà TextState della cella è sovrascritta dalla proprietà TextState di TextFragment.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Imposta il testo formattato della cella.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

Imposta l'estensione della riga.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Imposta l'allineamento verticale.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Imposta la larghezza della colonna.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

Imposta il testo avvolto a capo della cella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
