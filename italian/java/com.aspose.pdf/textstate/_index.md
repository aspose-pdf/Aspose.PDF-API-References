---
title: "TextState"
linktitle: "TextState"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta lo stato di un testo"
type: docs
weight: 5340
url: /it/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

Rappresenta lo stato di un testo

## Campi

| Campo | Descrizione |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | Valore predefinito della tabulazione nelle larghezze del carattere spazio del font predefinito. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextState](#TextState--) | Crea un oggetto text state. |
| [TextState](#TextState-java.awt.Color-) | Crea un oggetto text state. |
| [TextState](#TextState-java.awt.Color-double-) | Crea un oggetto text state. |
| [TextState](#TextState-double-) | Crea un oggetto text state con specifica della dimensione del font. |
| [TextState](#TextState-java.lang.String-) | Crea un oggetto text state. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | Crea un oggetto text state. |
| [TextState](#TextState-java.lang.String-double-) | Crea un oggetto text state. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Applica le impostazioni da un altro textState </p> <hr> <p> Verranno copiate solo le proprietà che sono state modificate esplicitamente. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Calcola la dimensione del font per il rettangolo. |
| [getBackgroundColor](#getBackgroundColor--) | <p> Ottiene il colore di sfondo del testo. </p> <hr> <p> Nota che il valore non è conservato come caratteristica del testo all'interno del documento. Il getter della proprietà BackgroundColor funziona per un oggetto nel caso sia stato impostato esplicitamente in precedenza con il setter BackgroundColor per quell'oggetto. La proprietà è utilizzata dal runtime nel contesto del processo di generazione/modifica corrente. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | Ottiene la spaziatura dei caratteri del testo. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del font. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del font. Il valore predefinito è Descender. Se il valore Descent del font è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri font. In questo caso, può essere selezionato CoordinateOrigin BaseLine per una migliore resa del testo. |
| [getFont](#getFont--) | Ottiene il font del testo. |
| [getfontSize](#getfontSize--) | Rappresenta il metodo getfontSize |
| [getFontSize](#getFontSize--) | Ottiene la dimensione del carattere del testo. |
| [getFontStyle](#getFontStyle--) | Imposta lo stile del carattere del testo. |
| [getForegroundColor](#getForegroundColor--) | Ottiene il colore di primo piano del testo. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Ottiene l'allineamento orizzontale del testo. </p> <hr> <p> HorizontalAlignment.None è uguale a HorizontalAlignment.Left. Nota che la proprietà TextState.HorizontalAlignment funziona solo in scenari di generazione di nuovi documenti. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Ottiene la scala orizzontale del testo. |
| [getLineSpacing](#getLineSpacing--) | <p> Ottiene l'interlinea del testo. </p> |
| [getRenderingMode](#getRenderingMode--) | Ottiene o imposta la modalità di rendering del testo. |
| [getStrokingColor](#getStrokingColor--) | Ottiene o imposta il colore di primo piano del testo. |
| [getTabTag](#getTabTag--) | <p> Puoi inserire questo tag nel testo per dichiarare la tabulazione. </p> <hr> <p> Ha effetto solo in combinazione con {@code TabStops}. </p> |
| [getTextHeight](#getTextHeight--) | Ottiene l'altezza del testo. |
| [getWordSpacing](#getWordSpacing--) | Ottiene la spaziatura tra parole del testo. |
| [isInvisible](#isInvisible--) | Ottiene l'invisibilità del testo. Questo riflette fondamentalmente lo stato {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), eccetto alcuni casi speciali (come il ritaglio). |
| [isStrikeOut](#isStrikeOut--) | Ottiene il barrato del testo, rappresentato dall'oggetto {@code TextFragment} |
| [isSubscript](#isSubscript--) | Ottiene o imposta il pedice del testo. |
| [isSuperscript](#isSuperscript--) | Ottiene il apice del testo. |
| [isUnderline](#isUnderline--) | Ottiene la sottolineatura del testo, rappresentata dall'oggetto {@code TextFragment} |
| [measureHeight](#measureHeight-char-) | Misura l'altezza del carattere. |
| [measureString](#measureString-java.lang.String-) | Misura la stringa. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> Misura la stringa. </p> <hr> <p> insideLine indica che la stringa non termina. Nel caso in cui venga misurata solo una parte dell'intera stringa, insideLine dovrebbe essere true. Nel caso in cui venga misurata l'intera stringa, insideLine dovrebbe essere false. In altre parole: se insideLine = true vengono considerate solo le larghezze dei caratteri. Nessuna trasformazione aggiuntiva viene considerata se insideLine = false. La fine della stringa è gestita correttamente - la trasformazione in corsivo è presa in considerazione. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Imposta il colore di sfondo del testo. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Imposta la spaziatura dei caratteri del testo. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del font. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del font. Il valore predefinito è Descender. Se il valore Descent del font è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri font. In questo caso, può essere selezionato CoordinateOrigin BaseLine per una migliore resa del testo. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Ottiene il font del testo. |
| [setFontSize](#setFontSize-float-) | Imposta la dimensione del carattere del testo. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | Imposta la dimensione del carattere del testo wish suppressed update. |
| [setFontStyle](#setFontStyle-int-) | Imposta lo stile del carattere del testo. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Ottiene il carattere del testo wish suppressed update. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Imposta il colore di primo piano del testo. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Imposta l'allineamento orizzontale per il testo. </p> <hr> <p> HorizontalAlignment.None è uguale a HorizontalAlignment.Left. Nota che la proprietà TextState.HorizontalAlignment funziona solo in scenari di generazione di nuovi documenti. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Imposta la scala orizzontale del testo. |
| [setInvisible](#setInvisible-boolean-) | Imposta l'invisibilità del testo. Questo riflette sostanzialmente lo stato {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), tranne alcuni casi speciali (come il ritaglio). |
| [setLineSpacing](#setLineSpacing-float-) | <p> Imposta l'interlinea del testo. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Ottiene o imposta la modalità di rendering del testo. |
| [setStrikeOut](#setStrikeOut-boolean-) | Imposta il barrato per il testo, rappresentato dall'oggetto {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Ottiene o imposta il colore di primo piano del testo. |
| [setSubscript](#setSubscript-boolean-) | Ottiene o imposta il pedice del testo. |
| [setSuperscript](#setSuperscript-boolean-) | Imposta il apice del testo. |
| [setUnderline](#setUnderline-boolean-) | Imposta la sottolineatura per il testo, rappresentata dall'oggetto {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Imposta la spaziatura tra parole del testo. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

Valore predefinito della tabulazione nelle larghezze del carattere spazio del font predefinito.

### TextState {#TextState--}
```
public TextState()
```

Crea un oggetto text state.

### TextState {#TextState-java.awt.Color-}
Crea un oggetto text state.

### TextState {#TextState-java.awt.Color-double-}
Crea un oggetto text state.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

Crea un oggetto text state con specifica della dimensione del font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontSize |  | Dimensione del carattere. |

### TextState {#TextState-java.lang.String-}
Crea un oggetto text state.

### TextState {#TextState-java.lang.String-boolean-boolean-}
Crea un oggetto text state.

### TextState {#TextState-java.lang.String-double-}
Crea un oggetto text state.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Applica le impostazioni da un altro textState </p> <hr> <p> Verranno copiate solo le proprietà che sono state modificate esplicitamente. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
Calcola la dimensione del font per il rettangolo.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> Ottiene il colore di sfondo del testo. </p> <hr> <p> Nota che il valore non è conservato come caratteristica del testo all'interno del documento. Il getter della proprietà BackgroundColor funziona per un oggetto nel caso sia stato impostato esplicitamente in precedenza con il setter BackgroundColor per quell'oggetto. La proprietà è utilizzata dal runtime nel contesto del processo di generazione/modifica corrente. </p>

**Returns:**
Valore colore

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Ottiene la spaziatura dei caratteri del testo.

**Returns:**
valore float

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del font. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del font. Il valore predefinito è Descender. Se il valore Descent del font è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri font. In questo caso, può essere selezionato CoordinateOrigin BaseLine per una migliore resa del testo.

**Returns:**
elemento CoordinateOrigin

### getFont {#getFont--}
```
public Font getFont()
```

Ottiene il font del testo.

**Returns:**
oggetto Font

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

Rappresenta il metodo getfontSize

**Returns:**
valore float

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Ottiene la dimensione del carattere del testo.

**Returns:**
valore float

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Imposta lo stile del carattere del testo.

**Returns:**
elemento FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Ottiene il colore di primo piano del testo.

**Returns:**
Valore colore

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Ottiene l'allineamento orizzontale del testo. </p> <hr> <p> HorizontalAlignment.None è uguale a HorizontalAlignment.Left. Nota che la proprietà TextState.HorizontalAlignment funziona solo in scenari di generazione di nuovi documenti. </p>

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Ottiene la scala orizzontale del testo.

**Returns:**
valore float

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> Ottiene l'interlinea del testo. </p>

**Returns:**
valore float <hr> <p> Nota che il valore non è conservato come caratteristica del testo all'interno del documento. Il getter della proprietà LineSpacing funziona per un oggetto nel caso sia stato impostato esplicitamente in precedenza con il setter LineSpacing per quell'oggetto. La proprietà è utilizzata dal runtime nel contesto del processo corrente di generazione/modifica. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

Ottiene o imposta la modalità di rendering del testo.

**Returns:**
elemento TextRenderingMode @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Ottiene o imposta il colore di primo piano del testo.

**Returns:**
Istanza di Color

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> Puoi inserire questo tag nel testo per dichiarare la tabulazione. </p> <hr> <p> Ha effetto solo in combinazione con {@code TabStops}. </p>

**Returns:**
valore stringa "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Ottiene l'altezza del testo.

**Returns:**
valore float

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Ottiene la spaziatura tra parole del testo.

**Returns:**
valore float

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Ottiene l'invisibilità del testo. Questo riflette fondamentalmente lo stato {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), eccetto alcuni casi speciali (come il ritaglio).

**Returns:**
valore booleano

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Ottiene il barrato del testo, rappresentato dall'oggetto {@code TextFragment}

**Returns:**
valore booleano

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Ottiene o imposta il pedice del testo.

**Returns:**
valore booleano

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Ottiene il apice del testo.

**Returns:**
valore booleano

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Ottiene la sottolineatura del testo, rappresentata dall'oggetto {@code TextFragment}

**Returns:**
valore booleano

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
```

Misura l'altezza del carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| carattere |  | Carattere da misurare. |

**Returns:**
Altezza del carattere se è possibile ottenerla dal font; altrimenti 0.

### measureString {#measureString-java.lang.String-}
Misura la stringa.

### measureString {#measureString-java.lang.String-boolean-}
<p> Misura la stringa. </p> <hr> <p> insideLine indica che la stringa non termina. Nel caso in cui venga misurata solo una parte dell'intera stringa, insideLine dovrebbe essere true. Nel caso in cui venga misurata l'intera stringa, insideLine dovrebbe essere false. In altre parole: se insideLine = true vengono considerate solo le larghezze dei caratteri. Nessuna trasformazione aggiuntiva viene considerata se insideLine = false. La fine della stringa è gestita correttamente - la trasformazione in corsivo è presa in considerazione. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Imposta il colore di sfondo del testo.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Imposta la spaziatura dei caratteri del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del font. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del font. Il valore predefinito è Descender. Se il valore Descent del font è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri font. In questo caso, può essere selezionato CoordinateOrigin BaseLine per una migliore resa del testo.

### setFont {#setFont-com.aspose.pdf.Font-}
Ottiene il font del testo.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Imposta la dimensione del carattere del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

Imposta la dimensione del carattere del testo wish suppressed update.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Imposta lo stile del carattere del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore FontStyles @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
Ottiene il carattere del testo wish suppressed update.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Imposta il colore di primo piano del testo.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Imposta l'allineamento orizzontale per il testo. </p> <hr> <p> HorizontalAlignment.None è uguale a HorizontalAlignment.Left. Nota che la proprietà TextState.HorizontalAlignment funziona solo in scenari di generazione di nuovi documenti. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Imposta la scala orizzontale del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Imposta l'invisibilità del testo. Questo riflette sostanzialmente lo stato {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), tranne alcuni casi speciali (come il ritaglio).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> Imposta l'interlinea del testo. </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float <hr> <p> Nota che il valore non è conservato come caratteristica del testo all'interno del documento. Il getter della proprietà LineSpacing funziona per un oggetto nel caso sia stato impostato esplicitamente in precedenza con il setter LineSpacing per quell'oggetto. La proprietà è utilizzata dal runtime nel contesto del processo corrente di generazione/modifica. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
Ottiene o imposta la modalità di rendering del testo.

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

Imposta il barrato per il testo, rappresentato dall'oggetto {@code TextFragment}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
Ottiene o imposta il colore di primo piano del testo.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Ottiene o imposta il pedice del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Imposta il apice del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

Imposta la sottolineatura per il testo, rappresentata dall'oggetto {@code TextFragment}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

Imposta la spaziatura tra parole del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |
