---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta i paragrafi di testo come oggetto di testo multilinea. </p> <hr> <pre> L'esempio dimostra come creare un oggetto paragrafo di testo e aggiungerlo alla pagina Pdf. Document doc."
type: docs
weight: 5200
url: /it/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> Rappresenta i paragrafi di testo come oggetto di testo multilinea. </p> <hr> <pre> L'esempio dimostra come creare un oggetto di paragrafo di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // crea il paragrafo di testo TextParagraph paragraph = new TextParagraph(); // imposta il rettangolo del paragrafo paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // imposta le opzioni di a capo delle parole paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // aggiunge le linee di stringa paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // aggiunge il paragrafo alla pagina Pdf con il TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // salva il documento Pdf doc.save(outFile); </pre>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextParagraph](#TextParagraph--) | Crea l'oggetto {@code TextParagraph}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | Aggiunge riga di testo |
| [appendLine](#appendLine-java.lang.String-float-) | Aggiunge riga di testo. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Aggiunge riga di testo con parametri di stato del testo. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Aggiunge riga di testo con parametri di stato del testo. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | Aggiunge riga di testo con parametri di stato del testo. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Aggiunge riga di testo con parametri di stato del testo. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Aggiunge riga di testo con parametri di stato del testo. |
| [beginEdit](#beginEdit--) | Inizia la modifica del TextParagraph. <p> Migliora le prestazioni del popolamento del TextParagraph. Qualsiasi calcolo del layout è sospeso fino a quando il metodo EndEdit non viene invocato. <p> Nota che l'invocazione del metodo non può essere annidata. </p> |
| [endEdit](#endEdit--) | Termina la modifica del TextParagraph. <p> Migliora le prestazioni del popolamento del TextParagraph. Qualsiasi calcolo del layout è sospeso fino a quando il metodo EndEdit non viene invocato. <p> Nota che l'invocazione del metodo non può essere annidata. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | Restituisce o imposta il valore di rientro delle righe successive. Se impostato a un valore diverso da zero, ha un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent. |
| [getFormattingOptions](#getFormattingOptions--) | Restituisce le opzioni di formattazione. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Restituisce l'allineamento orizzontale del testo all'interno del Rectangle del paragrph. HorizontalAlignment.None è uguale a HorizontalAlignment.Left. |
| [getHyphenSymbol](#getHyphenSymbol--) | Restituisce il simbolo di trattino utilizzato nel processo di sillabazione. Il simbolo di sillabazione è "-" per impostazione predefinita. Per eliminare il disegno del trattino (con la procedura di wrapping ancora attiva) impostare la stringa vuota string.Empty per HyphenSymbol. |
| [getMargin](#getMargin--) | Ottiene il riempimento. |
| [getPosition](#getPosition--) | Restituisce la posizione del paragrafo. |
| [getRectangle](#getRectangle--) | Restituisce il rettangolo del paragrafo. |
| [getRotation](#getRotation--) | Restituisce o imposta l'angolo di rotazione in gradi. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Restituisce il valore di rientro delle righe successive. |
| [getTextRectangle](#getTextRectangle--) | Restituisce il rettangolo del testo posizionato nel paragrafo. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> Restituisce l'allineamento verticale del testo all'interno del {@code Rectangle} del paragrph. </p> |
| [isJustify](#isJustify--) | Restituisce il valore che indica se il testo è giustificato. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Imposta il colore di sfondo per il paragrafo di testo. |
| [setBackgroundMode](#setBackgroundMode-int-) | Imposta la modalità di sfondo per il paragrafo di testo |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Restituisce o imposta il valore di rientro delle righe successive. Se impostato a un valore diverso da zero, ha un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Imposta le opzioni di formattazione. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta l'allineamento orizzontale del testo all'interno del Rectangle del paragrph. HorizontalAlignment.None è uguale a HorizontalAlignment.Left. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | Imposta il simbolo di trattino utilizzato nel processo di sillabazione. Il simbolo di sillabazione è "-" per impostazione predefinita. Per eliminare il disegno del trattino (con la procedura di wrapping ancora attiva) impostare la stringa vuota string.Empty per HyphenSymbol. |
| [setJustify](#setJustify-boolean-) | Imposta il valore che indica se il testo è giustificato. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Imposta il riempimento. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Imposta la rotazione del paragrafo. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | Imposta la modalità di compatibilità con il codice legacy |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Imposta la posizione del paragrafo. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Imposta il rettangolo del paragrafo. |
| [setRotation](#setRotation-double-) | Restituisce o imposta l'angolo di rotazione in gradi. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Imposta il valore di rientro delle righe successive. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Imposta l'allineamento verticale del testo all'interno del {@code Rectangle} del paragrph. VerticalAlignment.None è uguale a VerticalAlignment.Bottom. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

Crea l'oggetto {@code TextParagraph}.

### appendLine {#appendLine-java.lang.String-}
Aggiunge riga di testo

### appendLine {#appendLine-java.lang.String-float-}
Aggiunge riga di testo.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
Aggiunge riga di testo con parametri di stato del testo.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
Aggiunge riga di testo con parametri di stato del testo.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
Aggiunge riga di testo con parametri di stato del testo.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
Aggiunge riga di testo con parametri di stato del testo.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
Aggiunge riga di testo con parametri di stato del testo.

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

Inizia la modifica del TextParagraph. <p> Migliora le prestazioni del popolamento del TextParagraph. Qualsiasi calcolo del layout è sospeso fino a quando il metodo EndEdit non viene invocato. <p> Nota che l'invocazione del metodo non può essere annidata. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

Termina la modifica del TextParagraph. <p> Migliora le prestazioni del popolamento del TextParagraph. Qualsiasi calcolo del layout è sospeso fino a quando il metodo EndEdit non viene invocato. <p> Nota che l'invocazione del metodo non può essere annidata. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Restituisce o imposta il valore di rientro delle righe successive. Se impostato a un valore diverso da zero, ha un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent.

**Returns:**
valore float

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Restituisce le opzioni di formattazione.

**Returns:**
oggetto TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Restituisce l'allineamento orizzontale del testo all'interno del Rectangle del paragrph. HorizontalAlignment.None è uguale a HorizontalAlignment.Left.

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

Restituisce il simbolo di trattino utilizzato nel processo di sillabazione. Il simbolo di sillabazione è "-" per impostazione predefinita. Per eliminare il disegno del trattino (con la procedura di wrapping ancora attiva) impostare la stringa vuota string.Empty per HyphenSymbol.

**Returns:**
valore String

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Ottiene il riempimento.

**Returns:**
Valore MarginInfo

### getPosition {#getPosition--}
```
public Position getPosition()
```

Restituisce la posizione del paragrafo.

**Returns:**
Valore della posizione

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Restituisce il rettangolo del paragrafo.

**Returns:**
oggetto Rectangle

### getRotation {#getRotation--}
```
public double getRotation()
```

Restituisce o imposta l'angolo di rotazione in gradi.

**Returns:**
valore double

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Restituisce il valore di rientro delle righe successive.

**Returns:**
valore float

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

Restituisce il rettangolo del testo posizionato nel paragrafo.

**Returns:**
oggetto Rectangle

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> Restituisce l'allineamento verticale del testo all'interno del {@code Rectangle} del paragrph. </p>

**Returns:**
valore VerticalAlignment @see VerticalAlignment <hr> <p> VerticalAlignment.None è uguale a VerticalAlignment.Bottom. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Restituisce il valore che indica se il testo è giustificato.

**Returns:**
valore booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Imposta il colore di sfondo per il paragrafo di testo.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

Imposta la modalità di sfondo per il paragrafo di testo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Restituisce o imposta il valore di rientro delle righe successive. Se impostato a un valore diverso da zero, ha un vantaggio rispetto al valore FormattingOptions.SubsequentLinesIndent.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Imposta le opzioni di formattazione.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta l'allineamento orizzontale del testo all'interno del Rectangle del paragrph. HorizontalAlignment.None è uguale a HorizontalAlignment.Left.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
Imposta il simbolo di trattino utilizzato nel processo di sillabazione. Il simbolo di sillabazione è "-" per impostazione predefinita. Per eliminare il disegno del trattino (con la procedura di wrapping ancora attiva) impostare la stringa vuota string.Empty per HyphenSymbol.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Imposta il valore che indica se il testo è giustificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Imposta il riempimento.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Imposta la rotazione del paragrafo.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

Imposta la modalità di compatibilità con il codice legacy

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setPosition {#setPosition-com.aspose.pdf.Position-}
Imposta la posizione del paragrafo.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Imposta il rettangolo del paragrafo.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Restituisce o imposta l'angolo di rotazione in gradi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Imposta il valore di rientro delle righe successive.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Imposta l'allineamento verticale del testo all'interno del {@code Rectangle} del paragrph. VerticalAlignment.None è uguale a VerticalAlignment.Bottom.
