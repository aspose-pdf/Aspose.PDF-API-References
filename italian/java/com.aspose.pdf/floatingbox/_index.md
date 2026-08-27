---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un FloatingBox in un documento PDF. FloatingBox è posizionato in modo personalizzato."
type: docs
weight: 1610
url: /it/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

Rappresenta un FloatingBox in un documento PDF. FloatingBox è posizionato in modo personalizzato.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FloatingBox](#FloatingBox--) | Inizializza una nuova istanza della classe {@code FloatingBox}. |
| [FloatingBox](#FloatingBox-float-float-) | Inizializza una nuova istanza della classe {@code FloatingBox} con larghezza e altezza specificate. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Clona un nuovo oggetto {@code FloatingBox}. I paragrafi nella floating box non sono clonati. |
| [getBackgroundColor](#getBackgroundColor--) | Restituisce un oggetto che indica il colore di sfondo della casella fluttuante. |
| [getBackgroundImage](#getBackgroundImage--) | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene compilata durante la lettura del documento). |
| [getBorder](#getBorder--) | Restituisce un oggetto che indica le informazioni del bordo della casella fluttuante. |
| [getColumnInfo](#getColumnInfo--) | Restituisce le informazioni di una colonna. |
| [getHeight](#getHeight--) | Restituisce un valore float che indica l'altezza della casella fluttuante. |
| [getLeft](#getLeft--) | Restituisce la coordinata sinistra della tabella. |
| [getPadding](#getPadding--) | Restituisce un oggetto che indica il padding della casella fluttuante. |
| [getParagraphs](#getParagraphs--) | Restituisce una collezione che indica tutti i paragrafi nella cella. |
| [getPositioningMode](#getPositioningMode--) | Specifica la variante per determinare la posizione del FloatingBox nella pagina. |
| [getTop](#getTop--) | Ottiene la coordinata superiore della tabella. |
| [getWidth](#getWidth--) | Restituisce un valore float che indica la larghezza della casella fluttuante. |
| [isNeedRepeating](#isNeedRepeating--) | Restituisce un valore booleano che indica se il paragrafo deve essere ripetuto nella pagina successiva. Il valore predefinito è true. L'attributo è valido solo quando sia il paragrafo stesso sia l'oggetto a cui fa riferimento ReferenceParagraphID sono entrambi inclusi in RepeatingRows. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Imposta un oggetto che indica il colore di sfondo della casella fluttuante. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene compilata durante la lettura del documento). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Imposta un oggetto che indica le informazioni del bordo della casella fluttuante. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Imposta le informazioni di una colonna. |
| [setHeight](#setHeight-double-) | Imposta un valore float che indica l'altezza della casella fluttuante. |
| [setLeft](#setLeft-double-) | Imposta la coordinata sinistra della tabella. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | Imposta un valore booleano che indica se il paragrafo deve essere ripetuto nella pagina successiva. Il valore predefinito è true. L'attributo è valido solo quando sia il paragrafo stesso sia l'oggetto a cui fa riferimento ReferenceParagraphID sono entrambi inclusi in RepeatingRows. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | Imposta un oggetto che indica il padding della casella fluttuante. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Imposta una collezione che indica tutti i paragrafi nella cella. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | Specifica la variante per determinare la posizione del FloatingBox nella pagina. |
| [setTop](#setTop-double-) | Imposta la coordinata superiore della tabella. |
| [setWidth](#setWidth-double-) | Imposta un valore float che indica la larghezza della casella fluttuante. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

Inizializza una nuova istanza della classe {@code FloatingBox}.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

Inizializza una nuova istanza della classe {@code FloatingBox} con larghezza e altezza specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | La larghezza della casella. |
| altezza |  | L'altezza della casella. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona un nuovo oggetto {@code FloatingBox}. I paragrafi nella floating box non sono clonati.

**Returns:**
Il nuovo oggetto {@code FloatingBox}.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Restituisce un oggetto che indica il colore di sfondo della casella fluttuante.

**Returns:**
oggetto che indica il colore di sfondo.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene compilata durante la lettura del documento).

**Returns:**
Istanza immagine

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Restituisce un oggetto che indica le informazioni del bordo della casella fluttuante.

**Returns:**
oggetto che indica le informazioni del bordo.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

Restituisce le informazioni di una colonna.

**Returns:**
oggetto ColumnInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Restituisce un valore float che indica l'altezza della casella fluttuante.

**Returns:**
valore che indica l'altezza.

### getLeft {#getLeft--}
```
public double getLeft()
```

Restituisce la coordinata sinistra della tabella.

**Returns:**
coordinata sinistra della tabella.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

Restituisce un oggetto che indica il padding della casella fluttuante.

**Returns:**
oggetto che indica il padding.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Restituisce una collezione che indica tutti i paragrafi nella cella.

**Returns:**
collezione che indica tutti i paragrafi.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

Specifica la variante per determinare la posizione del FloatingBox nella pagina.

**Returns:**
elemento ParagraphPositioningMode

### getTop {#getTop--}
```
public double getTop()
```

Ottiene la coordinata superiore della tabella.

**Returns:**
coordinata superiore della tabella.

### getWidth {#getWidth--}
```
public double getWidth()
```

Restituisce un valore float che indica la larghezza della casella fluttuante.

**Returns:**
valore double

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

Restituisce un valore booleano che indica se il paragrafo deve essere ripetuto nella pagina successiva. Il valore predefinito è true. L'attributo è valido solo quando sia il paragrafo stesso sia l'oggetto a cui fa riferimento ReferenceParagraphID sono entrambi inclusi in RepeatingRows.

**Returns:**
valore booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Imposta un oggetto che indica il colore di sfondo della casella fluttuante.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene compilata durante la lettura del documento).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Imposta un oggetto che indica le informazioni del bordo della casella fluttuante.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Imposta le informazioni di una colonna.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Imposta un valore float che indica l'altezza della casella fluttuante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore che indica l'altezza. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Imposta la coordinata sinistra della tabella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | coordinata sinistra della tabella. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

Imposta un valore booleano che indica se il paragrafo deve essere ripetuto nella pagina successiva. Il valore predefinito è true. L'attributo è valido solo quando sia il paragrafo stesso sia l'oggetto a cui fa riferimento ReferenceParagraphID sono entrambi inclusi in RepeatingRows.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
Imposta un oggetto che indica il padding della casella fluttuante.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Imposta una collezione che indica tutti i paragrafi nella cella.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
Specifica la variante per determinare la posizione del FloatingBox nella pagina.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Imposta la coordinata superiore della tabella.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | coordinata superiore della tabella. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Imposta un valore float che indica la larghezza della casella fluttuante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |
