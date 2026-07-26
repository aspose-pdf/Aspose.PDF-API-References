---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta un segmento di testo PDF. </p> <hr> <pre> L'esempio dimostra come cambiare il colore del testo e la dimensione del font del testo con l'oggetto {@code TextState} di {@code"
type: docs
weight: 5300
url: /it/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Rappresenta un segmento di testo PDF. </p> <hr> <pre> L'esempio dimostra come cambiare il colore del testo e la dimensione del font del testo con l'oggetto {@code TextState} dell'oggetto {@code TextSegment}. // Apri documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'absorber per la prima pagina doc.getPages().get(1).accept(absorber); // Cambia il colore di primo piano del primo segmento di testo della prima occorrenza absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Cambia la dimensione del font del primo segmento di testo della prima occorrenza absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Salva il documento doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> In poche parole, gli oggetti {@code TextSegment} sono figli dell'oggetto {@code TextFragment}. In dettaglio: Il testo di un documento PDF in {@code Aspose.Pdf} è rappresentato da due oggetti di base: {@code TextFragment} e {@code TextSegment} Le differenze tra loro dipendono principalmente dal contesto. Consideriamo lo scenario seguente. L'utente cerca il testo "hello world" per operare su di esso, modificarne le proprietà, visualizzarlo, ecc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> La rappresentazione fisica del testo PDF è molto complessa. Il testo "hello world" può consistere in diversi segmenti di testo fisicamente indipendenti. Il modello di testo Aspose.PDF stabilisce fondamentalmente che l'oggetto {@code TextFragment} fornisce un unico set di operazioni logiche sui set di oggetti {@code TextSegment} fisici che rappresentano la query dell'utente. In uno scenario di ricerca del testo, {@code TextFragment} è la rappresentazione logica del testo "hello world", e la collezione di oggetti {@code TextSegment} rappresenta tutti i segmenti fisici che costruiscono l'oggetto testo "hello world". Quindi, {@code TextFragment} è vicino alla rappresentazione logica del testo. E {@code TextSegment} è vicino alla rappresentazione fisica del testo. Ovviamente ogni oggetto {@code TextSegment} può avere il proprio font, colore e proprietà di posizionamento. {@code TextFragment} fornisce un modo semplice per modificare il testo con le sue proprietà: impostare il font, impostare la dimensione del font, impostare il colore del font, ecc. Nel frattempo, gli oggetti {@code TextSegment} sono accessibili e gli utenti possono operare con gli oggetti {@code TextSegment} in modo indipendente. </p>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> Crea l'oggetto TextSegment. </p> <hr> <pre> L'esempio dimostra come creare un oggetto frammento di testo, aggiungere un segmento di testo alla collezione di frammenti di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> Crea l'oggetto TextSegment. </p> <hr> <pre> L'esempio dimostra come creare un oggetto frammento di testo, aggiungere un segmento di testo alla collezione di frammenti di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | Ottiene la posizione del testo, rappresentata con l'oggetto {@code TextSegment}. L'YIndent della struttura Position rappresenta la coordinata di base del segmento di testo. |
| [getCharacters](#getCharacters--) | Ottiene la collezione di oggetti CharInfo che rappresentano le informazioni sui caratteri nel segmento di testo. |
| [getEndCharIndex](#getEndCharIndex--) | Ottiene l'indice del carattere finale del segmento corrente nell'operatore di visualizzazione del testo (Tj, TJ). |
| [getHyperlink](#getHyperlink--) | Ottiene o imposta il collegamento ipertestuale del segmento (per il generatore PDF). |
| [getPosition](#getPosition--) | Ottiene la posizione del testo, rappresentata con l'oggetto {@code TextSegment}. |
| [getRectangle](#getRectangle--) | Ottiene il rettangolo del TextSegment |
| [getStartCharIndex](#getStartCharIndex--) | Ottiene l'indice del carattere iniziale del segmento corrente nell'operatore di visualizzazione del testo (Tj, TJ). |
| [getText](#getText--) | Ottiene l'oggetto testo {@code string} che l'oggetto {@code TextSegment} rappresenta. |
| [getTextEditOptions](#getTextEditOptions--) | Ottiene le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [getTextState](#getTextState--) | <p> Ottiene o imposta lo stato del testo per il testo che l'oggetto {@code TextSegment} rappresenta. </p> <hr> <p> Fornisce un modo per modificare le seguenti proprietà del testo: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Imposta la posizione del testo, rappresentata con l'oggetto {@code TextSegment}. L'YIndent della struttura Position rappresenta la coordinata di base del segmento di testo. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Ottiene o imposta il collegamento ipertestuale del segmento (per il generatore PDF). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Imposta la posizione del testo, rappresentata con l'oggetto {@code TextSegment}. |
| [setText](#setText-java.lang.String-) | Imposta l'oggetto testo {@code string} che l'oggetto {@code TextSegment} rappresenta. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> Imposta lo stato del testo per il testo che l'oggetto {@code TextSegment} rappresenta. </p> <hr> <p> Fornisce un modo per modificare le seguenti proprietà del testo: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | Imposta l'oggetto testo {@code string} che l'oggetto {@code TextSegment} rappresenta con aggiornamento sopresso. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> Crea l'oggetto TextSegment. </p> <hr> <pre> L'esempio dimostra come creare un oggetto frammento di testo, aggiungere un segmento di testo alla collezione di frammenti di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> Crea l'oggetto TextSegment. </p> <hr> <pre> L'esempio dimostra come creare un oggetto frammento di testo, aggiungere un segmento di testo alla collezione di frammenti di testo e aggiungerlo alla pagina Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Ottiene la posizione del testo, rappresentata con l'oggetto {@code TextSegment}. L'YIndent della struttura Position rappresenta la coordinata di base del segmento di testo.

**Returns:**
Valore della posizione

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

Ottiene la collezione di oggetti CharInfo che rappresentano le informazioni sui caratteri nel segmento di testo.

**Returns:**
oggetto CharInfoCollection

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

Ottiene l'indice del carattere finale del segmento corrente nell'operatore di visualizzazione del testo (Tj, TJ).

**Returns:**
valore int

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

Ottiene o imposta il collegamento ipertestuale del segmento (per il generatore PDF).

**Returns:**
oggetto Hyperlink

### getPosition {#getPosition--}
```
public Position getPosition()
```

Ottiene la posizione del testo, rappresentata con l'oggetto {@code TextSegment}.

**Returns:**
Valore della posizione

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ottiene il rettangolo del TextSegment

**Returns:**
oggetto Rectangle

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

Ottiene l'indice del carattere iniziale del segmento corrente nell'operatore di visualizzazione del testo (Tj, TJ).

**Returns:**
valore int

### getText {#getText--}
```
public String getText()
```

Ottiene l'oggetto testo {@code string} che l'oggetto {@code TextSegment} rappresenta.

**Returns:**
valore String

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Ottiene le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere.

**Returns:**
valore TextEditOptions

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> Ottiene o imposta lo stato del testo per il testo che l'oggetto {@code TextSegment} rappresenta. </p> <hr> <p> Fornisce un modo per modificare le seguenti proprietà del testo: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
Valore TextState

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Imposta la posizione del testo, rappresentata con l'oggetto {@code TextSegment}. L'YIndent della struttura Position rappresenta la coordinata di base del segmento di testo.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Ottiene o imposta il collegamento ipertestuale del segmento (per il generatore PDF).

### setPosition {#setPosition-com.aspose.pdf.Position-}
Imposta la posizione del testo, rappresentata con l'oggetto {@code TextSegment}.

### setText {#setText-java.lang.String-}
Imposta l'oggetto testo {@code string} che l'oggetto {@code TextSegment} rappresenta.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> Imposta lo stato del testo per il testo che l'oggetto {@code TextSegment} rappresenta. </p> <hr> <p> Fornisce un modo per modificare le seguenti proprietà del testo: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
Imposta l'oggetto testo {@code string} che l'oggetto {@code TextSegment} rappresenta con aggiornamento sopresso.
