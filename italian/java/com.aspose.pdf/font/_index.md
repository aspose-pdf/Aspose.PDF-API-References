---
title: "Font"
linktitle: "Font"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta l'oggetto font. </p> <hr> <pre> L'esempio dimostra come cercare testo nella prima pagina e cambiare il font della prima occorrenza trovata. // Open document Document doc."
type: docs
weight: 1650
url: /it/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> Rappresenta l'oggetto font. </p> <hr> <pre> L'esempio dimostra come cercare testo nella prima pagina e cambiare il font della prima occorrenza trovata. // Apri documento Document doc = new Document("input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Crea il font e contrassegnalo per l'incorporamento Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Cambia il font della prima occorrenza di testo absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Salva il documento doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | Determina se il font contiene i caratteri specificati |
| [getActualFontName](#getActualFontName--) | <p> Ottiene il nome reale del font dell'oggetto {@code Font} se è inizializzato. Anche quando il font è sostituito o ha un nome interno per il pdf. O stringa vuota se il font non è inizializzato. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | Misura il punto di ascensione massimo. |
| [getBaseFont](#getBaseFont--) | Ottiene il valore BaseFont dell'oggetto font PDF. Conosciuto anche come nome PostScript del font. |
| [getDecodedFontName](#getDecodedFontName--) | A volte i font PDF (di solito font cinesi/giapponesi/coreani) possono avere un nome di font specifico. Questo nome è il valore della proprietà PDF del font \"BaseFont\" e a volte questa proprietà può essere rappresentata in forma esadecimale. Se si legge questo nome direttamente può apparire in forma non leggibile. Per ottenere una forma leggibile è necessario decodificare il nome del font secondo le regole specifiche per quel font. Questa proprietà restituisce il nome del font decodificato, quindi usala nei casi in cui ti imbatti in un {@code FontName} non leggibile. Se la proprietà {@code FontName} ha una forma leggibile, questa proprietà sarà la stessa di {@code FontName}, così puoi usare questa proprietà in tutti i casi in cui devi ottenere il nome del font in una forma leggibile. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | Misura il punto di discesa massimo. |
| [getFontName](#getFontName--) | <p> Ottiene il nome del font dell'oggetto {@code Font}. </p> |
| [getFontOptions](#getFontOptions--) | Proprietà utili per regolare il comportamento dei Font |
| [getIFont](#getIFont--) | <p> Oggetto font di sistema. </p> <hr> <p> Solo per uso interno </p> |
| [getIPdfFont](#getIPdfFont--) | <p> Oggetto font PDF. </p> <hr> <p> Solo per uso interno </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | Lo scopo di questo metodo è restituire la descrizione dell'errore se un tentativo di incorporare il font è fallito. Se non ci sono errori restituisce una stringa vuota. |
| [getType](#getType--) | Il nome del tipo di font |
| [isAccessible](#isAccessible--) | <p> Ottiene un'indicazione se il font è presente (installato) nel sistema. </p> |
| [isEmbedded](#isEmbedded--) | <p> Ottiene un valore che indica se il font è incorporato. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> Ottiene un valore che indica se il font è un subset. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato </p> <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | Misura la stringa. |
| [save](#save-java.io.OutputStream-) | Salva il font nello stream. Nota che il font viene salvato in formato TTF intermedio destinato ad essere usato solo in una copia convertita del documento originale. Il file del font non è destinato a essere usato al di fuori del contesto del documento originale. |
| [setEmbedded](#setEmbedded-boolean-) | Imposta un valore che indica se il font è incorporato. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato |
| [setSubset](#setSubset-boolean-) | Imposta un valore che indica se il font è un subset. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
Determina se il font contiene i caratteri specificati

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> Ottiene il nome reale del font dell'oggetto {@code Font} se è inizializzato. Anche quando il font è sostituito o ha un nome interno per il pdf. O stringa vuota se il font non è inizializzato. </p>

**Returns:**
Valore stringa <hr> <pre> L'esempio dimostra come cercare testo nella prima pagina e visualizzare il nome effettivo del carattere di una prima occorrenza di testo. // Apri documento Document doc = new Document(@"D:\Tests\input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Visualizza il nome effettivo del carattere della prima occorrenza di testo System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
Misura il punto di ascensione massimo.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

Ottiene il valore BaseFont dell'oggetto font PDF. Conosciuto anche come nome PostScript del font.

**Returns:**
valore String

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

A volte i font PDF (di solito font cinesi/giapponesi/coreani) possono avere un nome di font specifico. Questo nome è il valore della proprietà PDF del font \"BaseFont\" e a volte questa proprietà può essere rappresentata in forma esadecimale. Se si legge questo nome direttamente può apparire in forma non leggibile. Per ottenere una forma leggibile è necessario decodificare il nome del font secondo le regole specifiche per quel font. Questa proprietà restituisce il nome del font decodificato, quindi usala nei casi in cui ti imbatti in un {@code FontName} non leggibile. Se la proprietà {@code FontName} ha una forma leggibile, questa proprietà sarà la stessa di {@code FontName}, così puoi usare questa proprietà in tutti i casi in cui devi ottenere il nome del font in una forma leggibile.

**Returns:**
valore String

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
Misura il punto di discesa massimo.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> Ottiene il nome del font dell'oggetto {@code Font}. </p>

**Returns:**
Valore stringa <hr> <pre> L'esempio dimostra come cercare testo nella prima pagina e visualizzare il nome del carattere di una prima occorrenza di testo. // Apri documento Document doc = new Document(@"D:\Tests\input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Visualizza il nome del carattere della prima occorrenza di testo System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

Proprietà utili per regolare il comportamento dei Font

**Returns:**
oggetto IFontOptions

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> Oggetto font di sistema. </p> <hr> <p> Solo per uso interno </p>

**Returns:**
oggetto IFont

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> Oggetto font PDF. </p> <hr> <p> Solo per uso interno </p>

**Returns:**
oggetto IPdfFont

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

Lo scopo di questo metodo è restituire la descrizione dell'errore se un tentativo di incorporare il font è fallito. Se non ci sono errori restituisce una stringa vuota.

**Returns:**
Descrizione errore

### getType {#getType--}
```
public String getType()
```

Il nome del tipo di font

**Returns:**
Oggetto stringa

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> Ottiene un'indicazione se il font è presente (installato) nel sistema. </p>

**Returns:**
valore booleano <hr> <pre> L'esempio dimostra come cercare testo nella prima pagina e ottenere il valore che indica se il carattere è installato nel sistema. // Apri documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Visualizza il valore IsSubset del carattere della prima occorrenza di testo if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println("il carattere è installato nel sistema"); </pre> <hr> <p> Alcune operazioni non sono disponibili con i caratteri che non possono essere trovati nel sistema. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> Restituisce un valore che indica se il carattere è incorporato. Il carattere basato su IFont verrà automaticamente sottoposto a sottoinsieme e incorporato </p> <hr> <pre> Il seguente esempio dimostra come trovare un carattere, contrassegnarlo come incorporato, cercare testo nella pagina del documento e sostituire il carattere del testo. // Crea il carattere e contrassegnalo per l'incorporamento com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // apri documento com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf"); // crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world" com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // cambia il carattere per la prima occorrenza di testo absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // salva il documento doc.save("D:\\Tests\\output.pdf"); </pre>

**Returns:**
valore booleano @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> Restituisce un valore che indica se il carattere è un sottoinsieme. Il carattere basato su IFont verrà automaticamente sottoposto a sottoinsieme e incorporato </p> <hr> <pre> L'esempio dimostra come cercare testo nella prima pagina e ottenere il valore che indica se il carattere è un sottoinsieme. // Apri documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'assorbitore per la prima pagina doc.getPages().get_Item(1).accept(absorber); // Visualizza il valore IsSubset del carattere della prima occorrenza di testo if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("il carattere è un sottoinsieme"); </pre>

**Returns:**
valore booleano @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
Misura la stringa.

### save {#save-java.io.OutputStream-}
Salva il font nello stream. Nota che il font viene salvato in formato TTF intermedio destinato ad essere usato solo in una copia convertita del documento originale. Il file del font non è destinato a essere usato al di fuori del contesto del documento originale.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

Imposta un valore che indica se il font è incorporato. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

Imposta un valore che indica se il font è un subset. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
