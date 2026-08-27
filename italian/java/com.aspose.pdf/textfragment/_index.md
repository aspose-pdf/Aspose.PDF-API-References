---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta un frammento di testo PDF. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo font. // Open document."
type: docs
weight: 5110
url: /it/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> Rappresenta un frammento di testo PDF. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo font. // Apri documento Document doc = new Document("input.pdf"); // Trova il font che verrà usato per modificare il font del testo del documento Font font = FontRepository.findFont("Arial"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'absorber per la prima pagina doc.getPages().get(1).accept(absorber); // Modifica il testo e il font della prima occorrenza del testo absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Salva il documento doc.save("output.pdf"); </pre> <hr> <pre> In poche parole, l'oggetto {@code TextFragment} contiene un elenco di oggetti {@code TextSegment}. In dettaglio: Il testo del documento PDF in {@code com.aspose.pdf} è rappresentato da due oggetti di base: {@code TextFragment} e {@code TextSegment} Le differenze tra loro dipendono principalmente dal contesto. Consideriamo lo scenario seguente. L'utente cerca il testo "hello world" per operare su di esso, modificare le sue proprietà, visualizzarlo ecc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> La rappresentazione fisica del testo PDF è molto complessa. Il testo "hello world" può consistere in diversi segmenti di testo fisicamente indipendenti. Il modello di testo Aspose.Pdf stabilisce fondamentalmente che l'oggetto {@code TextFragment} fornisce un unico insieme di operazioni logiche su un insieme di oggetti {@code TextSegment} fisici che rappresentano la query dell'utente. Nello scenario di ricerca del testo, {@code TextFragment} è la rappresentazione logica del testo "hello world", e la collezione di oggetti {@code TextSegment} rappresenta tutti i segmenti fisici che costruiscono l'oggetto testo "hello world". Quindi, {@code TextFragment} è vicino alla rappresentazione logica del testo. E {@code TextSegment} è vicino alla rappresentazione fisica del testo. Ovviamente ogni oggetto {@code TextSegment} può avere il proprio font, colore e proprietà di posizionamento. {@code TextFragment} fornisce un modo semplice per modificare il testo con le sue proprietà: impostare il font, la dimensione del font, il colore del font ecc. Nel frattempo, gli oggetti {@code TextSegment} sono accessibili e gli utenti possono operare con gli oggetti {@code TextSegment} in modo indipendente. <p> Nota che la modifica delle proprietà di TextFragment può cambiare la collezione interna {@code Segments} perché TextFragment è un oggetto aggregato e può riorganizzare i segmenti interni o unirli in un unico segmento. Se il tuo requisito è lasciare invariata la collezione {@code Segments}, per favore modifica i segmenti interni individualmente. </p>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextFragment](#TextFragment--) | Inizializza una nuova istanza dell'oggetto {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-) | Inizializza una nuova istanza dell'oggetto {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Inizializza una nuova istanza dell'oggetto {@code TextFragment}. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | Inizializza una nuova istanza dell'oggetto {@code TextFragment}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clona il frammento con tutti i segmenti. |
| [deepClone](#deepClone--) | Clona il frammento. |
| [getBaselinePosition](#getBaselinePosition--) | Ottiene la posizione del testo, rappresentata con l'oggetto {@code TextFragment}. L'YIndent della struttura Position rappresenta la coordinata di base del frammento di testo. |
| [getEndNote](#getEndNote--) | Ottiene la nota di fine paragrafo (solo per la generazione PDF). |
| [getFootNote](#getFootNote--) | Ottiene la nota a piè di pagina del paragrafo (solo per la generazione PDF). |
| [getForm](#getForm--) | Ottiene l'oggetto modulo che contiene il TextFragment. Il valore può essere null nel caso in cui l'oggetto TextFragment non appartenga a un modulo. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Ottiene l'allineamento orizzontale del frammento di testo. |
| [getPage](#getPage--) | Ottiene la pagina che contiene il TextFragment. Il valore può essere null nel caso in cui l'oggetto TextFragment non appartenga a nessuna pagina. |
| [getPosition](#getPosition--) | <p> Ottiene la posizione del testo, rappresentata con l'oggetto {@code TextFragment}. </p> |
| [getRectangle](#getRectangle--) | Ottiene il rettangolo del TextFragment |
| [getReplaceOptions](#getReplaceOptions--) | Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con una versione più corta o più lunga. |
| [getSegments](#getSegments--) | <p> Ottiene i segmenti di testo per l'attuale {@code TextFragment}. </p> |
| [getText](#getText--) | <p> Ottiene l'oggetto testo {@code string} che l'oggetto {@code TextFragment} rappresenta. </p> |
| [getTextEditOptions](#getTextEditOptions--) | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il font. |
| [getTextState](#getTextState--) | <p> Ottiene o imposta lo stato del testo per il testo che l'oggetto {@code TextFragment} rappresenta. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | Ottiene l'allineamento verticale del frammento di testo. |
| [getWrapLinesCount](#getWrapLinesCount--) | Ottiene il conteggio delle linee di avvolgimento per questo paragrafo (solo per la generazione PDF). |
| [isolateTextSegments](#isolateTextSegments-int-int-) | Ottiene {@code TextSegment}(s) che rappresentano la parte specificata del testo {@code TextFragment}. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Imposta la posizione del testo, rappresentata con l'oggetto {@code TextFragment}. L'YIndent della struttura Position rappresenta la coordinata di base del frammento di testo. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | Imposta la nota di fine paragrafo (solo per la generazione PDF). |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | Imposta la nota a piè di pagina del paragrafo (solo per la generazione PDF). |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta l'allineamento orizzontale del frammento di testo. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Imposta il collegamento ipertestuale del frammento. |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> Imposta la posizione del testo, rappresentata con l'oggetto {@code TextFragment}. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Ottiene il rettangolo del TextFragment |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Rappresenta il metodo setSegments |
| [setText](#setText-java.lang.String-) | <p> Imposta l'oggetto di testo {@code string} che l'oggetto {@code TextFragment} rappresenta. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il font. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Imposta un allineamento verticale del frammento di testo. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | Imposta il conteggio delle righe di avvolgimento per questo paragrafo (solo per la generazione PDF) |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

Inizializza una nuova istanza dell'oggetto {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-}
Inizializza una nuova istanza dell'oggetto {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
Inizializza una nuova istanza dell'oggetto {@code TextFragment}.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
Inizializza una nuova istanza dell'oggetto {@code TextFragment}.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clona il frammento con tutti i segmenti.

**Returns:**
L'oggetto clonato

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona il frammento.

**Returns:**
L'oggetto clonato

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Ottiene la posizione del testo, rappresentata con l'oggetto {@code TextFragment}. L'YIndent della struttura Position rappresenta la coordinata di base del frammento di testo.

**Returns:**
Valore della posizione

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

Ottiene la nota di fine paragrafo (solo per la generazione PDF).

**Returns:**
Valore della nota

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

Ottiene la nota a piè di pagina del paragrafo (solo per la generazione PDF).

**Returns:**
Valore della nota

### getForm {#getForm--}
```
public XForm getForm()
```

Ottiene l'oggetto modulo che contiene il TextFragment. Il valore può essere null nel caso in cui l'oggetto TextFragment non appartenga a un modulo.

**Returns:**
Valore XForm

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Ottiene l'allineamento orizzontale del frammento di testo.

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

Ottiene la pagina che contiene il TextFragment. Il valore può essere null nel caso in cui l'oggetto TextFragment non appartenga a nessuna pagina.

**Returns:**
oggetto Page

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> Ottiene la posizione del testo, rappresentata con l'oggetto {@code TextFragment}. </p>

**Returns:**
Valore della posizione <hr> <pre> L'esempio dimostra come visualizzare il posizionamento di un testo, rappresentato dall'oggetto {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // View text and placement info of first text occurrence TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ottiene il rettangolo del TextFragment

**Returns:**
oggetto Rectangle

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con una versione più corta o più lunga.

**Returns:**
Istanza di TextReplaceOptions

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> Ottiene i segmenti di testo per l'attuale {@code TextFragment}. </p>

**Returns:**
Valore di TextSegmentCollection <hr> <pre> L'esempio dimostra come navigare tutti gli oggetti {@code TextSegment} all'interno dell'oggetto {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Navigate all text segments and out their text and placement info for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> In poche parole, gli oggetti {@code TextSegment} sono figli dell'oggetto {@code TextFragment}. Gli utenti avanzati possono accedere direttamente ai segmenti per eseguire scenari di modifica del testo più complessi. Per ulteriori dettagli, consultare la descrizione dell'oggetto {@code TextFragment}. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> Ottiene l'oggetto testo {@code string} che l'oggetto {@code TextFragment} rappresenta. </p>

**Returns:**
Valore di stringa <hr> <pre> L'esempio dimostra come cercare un testo e sostituire la prima occorrenza rappresentata dall'oggetto {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il font.

**Returns:**
Istanza di TextEditOptions

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> Ottiene o imposta lo stato del testo per il testo che l'oggetto {@code TextFragment} rappresenta. </p>

**Returns:**
Oggetto TextFragmentState <hr> <pre> L'esempio dimostra come modificare il colore del testo e la dimensione del carattere del testo con l'oggetto {@code TextState}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Fornisce un modo per modificare le seguenti proprietà del testo: Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Ottiene l'allineamento verticale del frammento di testo.

**Returns:**
Valore int @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

Ottiene il conteggio delle linee di avvolgimento per questo paragrafo (solo per la generazione PDF).

**Returns:**
valore int

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

Ottiene {@code TextSegment}(s) che rappresentano la parte specificata del testo {@code TextFragment}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex |  | Posizione nel testo da cui inizierà il nuovo {@code TextSegment}(s). |
| lunghezza |  | Lunghezza del testo che verrà isolato in {@code TextSegment}(s). |

**Returns:**
{@code TextSegmentCollection} contenente segmenti di testo che rappresentano una sottostringa di testo che inizia in una posizione specificata e ha una lunghezza definita.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Imposta la posizione del testo, rappresentata con l'oggetto {@code TextFragment}. L'YIndent della struttura Position rappresenta la coordinata di base del frammento di testo.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
Imposta la nota di fine paragrafo (solo per la generazione PDF).

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
Imposta la nota a piè di pagina del paragrafo (solo per la generazione PDF).

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta l'allineamento orizzontale del frammento di testo.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Imposta il collegamento ipertestuale del frammento.

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> Imposta la posizione del testo, rappresentata con l'oggetto {@code TextFragment}. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Ottiene il rettangolo del TextFragment

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
Rappresenta il metodo setSegments

### setText {#setText-java.lang.String-}
<p> Imposta l'oggetto di testo {@code string} che l'oggetto {@code TextFragment} rappresenta. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il font.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Imposta un allineamento verticale del frammento di testo.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

Imposta il conteggio delle righe di avvolgimento per questo paragrafo (solo per la generazione PDF)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
