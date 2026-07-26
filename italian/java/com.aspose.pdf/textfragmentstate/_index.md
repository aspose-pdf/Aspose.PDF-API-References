---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta lo stato di testo di un frammento di testo. </p> <hr> <pre> L'esempio dimostra come modificare il colore del testo e la dimensione del carattere del testo con l'oggetto {@code TextState}. // Apri. </pre>"
type: docs
weight: 5150
url: /it/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> Rappresenta lo stato di testo di un frammento di testo. </p> <hr> <pre> L'esempio dimostra come modificare il colore del testo e la dimensione del carattere del testo con l'oggetto {@code TextState}. // Apri documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'absorber per la prima pagina doc.getPages().get(1).accept(absorber); // Modifica il colore di primo piano della prima occorrenza di testo absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Modifica la dimensione del carattere della prima occorrenza di testo absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Salva il documento doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Fornisce un modo per modificare le seguenti proprietà del testo: font ({@code TextFragmentState.Font} property) dimensione del carattere ({@code TextFragmentState.FontSize} property) stile del carattere ({@code TextFragmentState.FontStyle} property) colore di primo piano ({@code TextFragmentState.ForegroundColor} property) colore di sfondo ({@code TextFragmentState.BackgroundColor} property) </p> <p> Nota che la modifica delle proprietà {@code TextFragmentState} può modificare la collezione interna {@code TextFragment.Segments} perché TextFragment è un oggetto aggregato e può riorganizzare i segmenti interni o unirli in un unico segmento. Se la tua esigenza è mantenere inalterata la collezione {@code TextFragment.Segments}, modifica i segmenti interni singolarmente. </p> @see TextFragmentAbsorber @see IDocument

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | Inizializza una nuova istanza dell'oggetto {@code TextFragmentState} con l'oggetto {@code TextFragment} specificato. Questa inizializzazione di {@code TextFragmentState} non è supportata. TextFragmentState è disponibile solo con la proprietà {@code TextFragment.TextState}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Applica le impostazioni da un altro textState </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Applica le impostazioni da un altro textState |
| [getBackgroundColor](#getBackgroundColor--) | Imposta il colore di sfondo del testo, rappresentato dall'oggetto {@code TextFragment} |
| [getCharacterSpacing](#getCharacterSpacing--) | Ottiene la spaziatura dei caratteri del testo, rappresentata dall'oggetto {@code TextFragment}. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del font. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del font. Il valore predefinito è Descender. Se il valore Descent del font è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri font. In questo caso, può essere selezionato CoordinateOrigin BaseLine per una migliore resa del testo. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | Ottiene se il flag di disegno del bordo del rettangolo di testo è impostato. |
| [getFont](#getFont--) | Ottiene il font del testo, rappresentato dall'oggetto {@code TextFragment} |
| [getFontSize](#getFontSize--) | Ottiene la dimensione del font del testo, rappresentata dall'oggetto {@code TextFragment} |
| [getFontStyle](#getFontStyle--) | Imposta lo stile del font del testo, rappresentato dall'oggetto {@code TextFragment} |
| [getForegroundColor](#getForegroundColor--) | Ottiene il colore di primo piano del testo, rappresentato dall'oggetto {@code TextFragment} |
| [getFormattingOptions](#getFormattingOptions--) | Ottiene o imposta le opzioni di formattazione. L'impostazione delle opzioni sarà efficace solo negli scenari di generatore. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Ottiene l'allineamento orizzontale del testo. </p> <hr> <p> HorizontalAlignment.None è uguale a HorizontalAlignment.Left. Nota che la proprietà TextFragmentState.VerticalAlignment funziona solo negli scenari di generazione di nuovi documenti. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Ottiene la scala orizzontale del testo, rappresentata dall'oggetto {@code TextFragment}. |
| [getLineSpacing](#getLineSpacing--) | <p> Ottiene l'interlinea del testo. </p> |
| [getRenderingMode](#getRenderingMode--) | Ottiene o imposta la modalità di rendering del testo. |
| [getRotation](#getRotation--) | Restituisce o imposta l'angolo di rotazione in gradi. |
| [getStrokingColor](#getStrokingColor--) | Ottiene o imposta le operazioni di contorno colore del rendering {@code TextFragment} (stroke text, rectangle border) |
| [getTabStops](#getTabStops--) | <p> Ottiene le tabulazioni per il testo. </p> <hr> <p> Nota che la proprietà Tabstops funziona solo negli scenari di generazione di nuovi documenti. Le tabulazioni possono essere aggiunte durante l'inizializzazione {@code TextFragment}. Le tabulazioni devono essere costruite prima del testo. </p> |
| [getTextHeight](#getTextHeight--) | Ottiene l'altezza del testo, rappresentata dall'oggetto {@code TextFragment} |
| [getWordSpacing](#getWordSpacing--) | Ottiene la spaziatura tra parole del testo. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | Verifica se la stringa di input può essere posizionata all'interno del rettangolo definito. |
| [isInvisible](#isInvisible--) | Ottiene l'invisibilità del testo. |
| [isStrikeOut](#isStrikeOut--) | Ottiene o imposta il barrato per il testo, rappresentato dall'oggetto {@link TextFragment} |
| [isSubscript](#isSubscript--) | Ottiene o imposta il pedice del testo, rappresentato dall'oggetto {@code TextFragment}. |
| [isSuperscript](#isSuperscript--) | Ottiene o imposta il apice del testo, rappresentato dall'oggetto {@code TextFragment}. |
| [isUnderline](#isUnderline--) | Ottiene o imposta la sottolineatura per il testo, rappresentata dall'oggetto {@link TextFragment} |
| [measureHeight](#measureHeight-char-) | Misura l'altezza del carattere. |
| [measureString](#measureString-java.lang.String-) | Misura la stringa. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Imposta il colore di sfondo del testo, rappresentato dall'oggetto TextFragment |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Imposta la spaziatura dei caratteri del testo, rappresentata dall'oggetto {@code TextFragment}. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del font. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del font. Il valore predefinito è Descender. Se il valore Descent del font è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri font. In questo caso, può essere selezionato CoordinateOrigin BaseLine per una migliore resa del testo. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | Imposta se il flag di disegno del bordo del rettangolo di testo è attivo. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Imposta il font del testo, rappresentato dall'oggetto {@code TextFragment} |
| [setFontSize](#setFontSize-float-) | Imposta la dimensione del font del testo, rappresentata dall'oggetto {@code TextFragment} |
| [setFontStyle](#setFontStyle-int-) | Imposta lo stile del font del testo, rappresentato dall'oggetto {@link TextFragment} |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Imposta il colore di primo piano del testo, rappresentato dall'oggetto {@code TextFragment} |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Ottiene o imposta le opzioni di formattazione. L'impostazione delle opzioni sarà efficace solo negli scenari di generatore. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Imposta l'allineamento orizzontale del testo. </p> <hr> <p> HorizontalAlignment.None è uguale a HorizontalAlignment.Left. Nota che la proprietà TextFragmentState.VerticalAlignment funziona solo in scenari di generazione di nuovi documenti. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Imposta la scala orizzontale del testo, rappresentata dall'oggetto {@code TextFragment}. |
| [setInvisible](#setInvisible-boolean-) | Imposta l'invisibilità del testo. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Imposta l'interlinea del testo. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Ottiene o imposta la modalità di rendering del testo. |
| [setRotation](#setRotation-double-) | Restituisce o imposta l'angolo di rotazione in gradi. |
| [setStrikeOut](#setStrikeOut-boolean-) | Imposta il barrato per il testo, rappresentato dall'oggetto {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Ottiene o imposta le operazioni di contorno colore del rendering {@code TextFragment} (stroke text, rectangle border) |
| [setSubscript](#setSubscript-boolean-) | Ottiene o imposta il pedice del testo, rappresentato dall'oggetto {@code TextFragment}. |
| [setSuperscript](#setSuperscript-boolean-) | Ottiene o imposta il apice del testo, rappresentato dall'oggetto {@code TextFragment}. |
| [setUnderline](#setUnderline-boolean-) | Imposta la sottolineatura per il testo, rappresentata dall'oggetto {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Imposta la spaziatura tra parole del testo. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
Inizializza una nuova istanza dell'oggetto {@code TextFragmentState} con l'oggetto {@code TextFragment} specificato. Questa inizializzazione di {@code TextFragmentState} non è supportata. TextFragmentState è disponibile solo con la proprietà {@code TextFragment.TextState}.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Applica le impostazioni da un altro textState </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
Applica le impostazioni da un altro textState

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Imposta il colore di sfondo del testo, rappresentato dall'oggetto {@code TextFragment}

**Returns:**
valore oggetto Color

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Ottiene la spaziatura dei caratteri del testo, rappresentata dall'oggetto {@code TextFragment}.

**Returns:**
valore float

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del font. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del font. Il valore predefinito è Descender. Se il valore Descent del font è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri font. In questo caso, può essere selezionato CoordinateOrigin BaseLine per una migliore resa del testo.

**Returns:**
elemento CoordinateOrigin

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

Ottiene se il flag di disegno del bordo del rettangolo di testo è impostato.

**Returns:**
valore booleano

### getFont {#getFont--}
```
public Font getFont()
```

Ottiene il font del testo, rappresentato dall'oggetto {@code TextFragment}

**Returns:**
Valore del font

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Ottiene la dimensione del font del testo, rappresentata dall'oggetto {@code TextFragment}

**Returns:**
valore float

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Imposta lo stile del font del testo, rappresentato dall'oggetto {@code TextFragment}

**Returns:**
elemento FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Ottiene il colore di primo piano del testo, rappresentato dall'oggetto {@code TextFragment}

**Returns:**
oggetto Color

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Ottiene o imposta le opzioni di formattazione. L'impostazione delle opzioni sarà efficace solo negli scenari di generatore.

**Returns:**
istanza TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Ottiene l'allineamento orizzontale del testo. </p> <hr> <p> HorizontalAlignment.None è uguale a HorizontalAlignment.Left. Nota che la proprietà TextFragmentState.VerticalAlignment funziona solo negli scenari di generazione di nuovi documenti. </p>

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Ottiene la scala orizzontale del testo, rappresentata dall'oggetto {@code TextFragment}.

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
elemento TextRenderingMode

### getRotation {#getRotation--}
```
public double getRotation()
```

Restituisce o imposta l'angolo di rotazione in gradi.

**Returns:**
valore double

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Ottiene o imposta le operazioni di contorno colore del rendering {@code TextFragment} (stroke text, rectangle border)

**Returns:**
Istanza di Color

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> Ottiene le tabulazioni per il testo. </p> <hr> <p> Nota che la proprietà Tabstops funziona solo negli scenari di generazione di nuovi documenti. Le tabulazioni possono essere aggiunte durante l'inizializzazione {@code TextFragment}. Le tabulazioni devono essere costruite prima del testo. </p>

**Returns:**
oggetto TabStops

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Ottiene l'altezza del testo, rappresentata dall'oggetto {@code TextFragment}

**Returns:**
valore float

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Ottiene la spaziatura tra parole del testo.

**Returns:**
valore float

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
Verifica se la stringa di input può essere posizionata all'interno del rettangolo definito.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Ottiene l'invisibilità del testo.

**Returns:**
valore booleano

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Ottiene o imposta il barrato per il testo, rappresentato dall'oggetto {@link TextFragment}

**Returns:**
valore booleano

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Ottiene o imposta il pedice del testo, rappresentato dall'oggetto {@code TextFragment}.

**Returns:**
valore booleano

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Ottiene o imposta il apice del testo, rappresentato dall'oggetto {@code TextFragment}.

**Returns:**
valore booleano

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Ottiene o imposta la sottolineatura per il testo, rappresentata dall'oggetto {@link TextFragment}

**Returns:**
valore booleano

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
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

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Imposta il colore di sfondo del testo, rappresentato dall'oggetto TextFragment

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Imposta la spaziatura dei caratteri del testo, rappresentata dall'oggetto {@code TextFragment}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Ottiene o imposta il CoordinateOrigin del testo. Se CoordinateOrigin è Descender, la coordinata Y del testo corrisponde al punto più basso del font. Se CoordinateOrigin è BaseLine, la coordinata Y del testo corrisponde alla linea di base del font. Il valore predefinito è Descender. Se il valore Descent del font è troppo grande, il testo può essere visualizzato più in alto rispetto ad altri font. In questo caso, può essere selezionato CoordinateOrigin BaseLine per una migliore resa del testo.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

Imposta se il flag di disegno del bordo del rettangolo di testo è attivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setFont {#setFont-com.aspose.pdf.Font-}
Imposta il font del testo, rappresentato dall'oggetto {@code TextFragment}

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Imposta la dimensione del font del testo, rappresentata dall'oggetto {@code TextFragment}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Imposta lo stile del font del testo, rappresentato dall'oggetto {@link TextFragment}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Imposta il colore di primo piano del testo, rappresentato dall'oggetto {@code TextFragment}

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Ottiene o imposta le opzioni di formattazione. L'impostazione delle opzioni sarà efficace solo negli scenari di generatore.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Imposta l'allineamento orizzontale del testo. </p> <hr> <p> HorizontalAlignment.None è uguale a HorizontalAlignment.Left. Nota che la proprietà TextFragmentState.VerticalAlignment funziona solo in scenari di generazione di nuovi documenti. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Imposta la scala orizzontale del testo, rappresentata dall'oggetto {@code TextFragment}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Imposta l'invisibilità del testo.

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

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Restituisce o imposta l'angolo di rotazione in gradi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

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
Ottiene o imposta le operazioni di contorno colore del rendering {@code TextFragment} (stroke text, rectangle border)

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Ottiene o imposta il pedice del testo, rappresentato dall'oggetto {@code TextFragment}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Ottiene o imposta il apice del testo, rappresentato dall'oggetto {@code TextFragment}.

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
