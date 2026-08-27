---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta un oggetto assorbitore di frammenti di testo. Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>."
type: docs
weight: 5120
url: /it/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> Rappresenta un oggetto assorbitore di frammenti di testo. Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> L'oggetto {@code TextFragmentAbsorber} è fondamentalmente utilizzato nello scenario di ricerca del testo. Quando la ricerca è completata, le occorrenze sono rappresentate con oggetti {@code TextFragment} contenuti nella collezione {@code TextFragmentAbsorber.TextFragments}. L'oggetto {@code TextFragment} fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (font, dimensione del font, colore, ecc.). </p>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | Applica la dimensione del carattere a tutti i frammenti di testo assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti nella/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | Applica il carattere a tutti i frammenti di testo assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti nella/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | Applica il carattere e la dimensione a tutti i frammenti di testo assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti nella/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| [getErrors](#getErrors--) | Elenco di oggetti {@code TextExtractionError}. Contiene informazioni sugli errori trovati durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| [getExtractionOptions](#getExtractionOptions--) | Ottiene le opzioni di estrazione del testo. |
| [getPhrase](#getPhrase--) | <p> Ottiene la frase che {@code TextFragmentAbsorber} cerca nel documento PDF o nella pagina. </p> |
| [getRegexResults](#getRegexResults--) | Ottiene il dizionario delle occorrenze di ricerca presentate con la classe System.Text.RegularExpressions.Regex come chiave e {@link TextFragment} come valore. L'esempio dimostra come trovare il testo con un array di espressioni regolari nella prima pagina del documento PDF. // Apri documento Document doc = new Document(\"input.pdf\"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Crea l'oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e terminano con 'o' usando l'espressione regolare. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Ottieni i risultati Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | Ottiene il testo estratto che il {@code TextAbsorber} estrae dal documento PDF o dalla pagina. |
| [getTextEditOptions](#getTextEditOptions--) | Ottiene le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [getTextFragments](#getTextFragments--) | <p> Ottiene la collezione di occorrenze di ricerca presentate con oggetti {@code TextFragment}. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con una versione più corta o più lunga. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Ottiene le opzioni di ricerca. Le opzioni abilitano la ricerca usando espressioni regolari. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | Il valore indica se sono stati trovati errori durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | Rimuove tutto il testo dal documento. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | Rimuove tutto il testo dalla pagina specificata. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Rimuove il testo all'interno del rettangolo specificato dalla pagina indicata. |
| [reset](#reset--) | Cancella la collezione TextFragments di questo oggetto {@code TextFragmentAbsorber}. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Imposta le opzioni di estrazione del testo. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> Imposta la frase che il {@code TextFragmentAbsorber} ricerca nel documento PDF o nella pagina. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> Imposta la collezione di occorrenze di ricerca presentate con oggetti {@code TextFragment}. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Imposta le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con una versione più corta o più lunga. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Imposta le opzioni di ricerca. Le opzioni abilitano la ricerca usando espressioni regolari. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Esegue la ricerca sul documento specificato. </p> <hr> <pre> L'esempio dimostra come trovare il testo in un documento PDF e sostituire il testo di tutte le occorrenze di ricerca. // Apri documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Trova il font che sarà usato per cambiare il font del testo del documento Font font = FontRepository.findFont(\"Arial\"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accetta l'assorbitore per la prima pagina absorber.visit(doc); // Cambia il testo della prima occorrenza di testo absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Salva il documento doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Esegue la ricerca sulla pagina specificata. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Apri documento Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Trova il font che sarà usato per cambiare il font del testo del documento Font font = FontRepository.findFont(\"Arial\"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accetta l'assorbitore per la prima pagina absorber.visit(doc.getPages().get(1)); // Cambia il testo di tutte le occorrenze di ricerca per (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( \"hi world\"); } // Salva il documento doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | Esegue la ricerca sull'oggetto form specificato. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> Inizializza una nuova istanza di {@code TextFragmentAbsorber} che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code TextFragmentAbsorber.TextFragments}. </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

Applica la dimensione del carattere a tutti i frammenti di testo assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti nella/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontSize |  | Dimensione del carattere del testo. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
Applica il carattere a tutti i frammenti di testo assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti nella/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
Applica il carattere e la dimensione a tutti i frammenti di testo assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti nella/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo.

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Elenco di oggetti {@code TextExtractionError}. Contiene informazioni sugli errori trovati durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni.

**Returns:**
Elenco di oggetti TextExtractionError

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

Ottiene le opzioni di estrazione del testo.

**Returns:**
Oggetto TextExtractionOptions

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> Ottiene la frase che {@code TextFragmentAbsorber} cerca nel documento PDF o nella pagina. </p>

**Returns:**
String value <hr> <pre> L'esempio dimostra come eseguire più volte la ricerca di testo e effettuare sostituzioni di testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // search another word and replace it absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

Ottiene il dizionario delle occorrenze di ricerca presentate con la classe System.Text.RegularExpressions.Regex come chiave e {@link TextFragment} come valore. L'esempio dimostra come trovare il testo con un array di espressioni regolari nella prima pagina del documento PDF. // Apri documento Document doc = new Document(\"input.pdf\"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Crea l'oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e terminano con 'o' usando l'espressione regolare. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Ottieni i risultati Dictionary results = absorber.getRegexResults();

**Returns:**
Istanza di Dictionary

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

Ottiene il testo estratto che il {@code TextAbsorber} estrae dal documento PDF o dalla pagina.

**Returns:**
String value L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Ottiene le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere.

**Returns:**
Oggetto TextEditOptions

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> Ottiene la collezione di occorrenze di ricerca presentate con oggetti {@code TextFragment}. </p>

**Returns:**
TextFragmentCollection object <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire tutte le occorrenze trovate con nuovo testo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con una versione più corta o più lunga.

**Returns:**
Valore TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Ottiene le opzioni di ricerca. Le opzioni abilitano la ricerca usando espressioni regolari. </p>

**Returns:**
TextSearchOptions object <hr> <pre> L'esempio dimostra come eseguire la ricerca di testo usando espressioni regolari. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // make the absorber to search all words starting 'h' and ending 'o' using regular expression. absorber.setPhrase ( "h\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // we should find "hello" word and replace it with "Hi" doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

Il valore indica se sono stati trovati errori durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni.

**Returns:**
valore booleano

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
Rimuove tutto il testo dal documento.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
Rimuove tutto il testo dalla pagina specificata.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Rimuove il testo all'interno del rettangolo specificato dalla pagina indicata.

### reset {#reset--}
```
public void reset()
```

Cancella la collezione TextFragments di questo oggetto {@code TextFragmentAbsorber}.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
Imposta le opzioni di estrazione del testo.

### setPhrase {#setPhrase-java.lang.String-}
<p> Imposta la frase che il {@code TextFragmentAbsorber} ricerca nel documento PDF o nella pagina. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> Imposta la collezione di occorrenze di ricerca presentate con oggetti {@code TextFragment}. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Imposta le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con una versione più corta o più lunga.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Imposta le opzioni di ricerca. Le opzioni abilitano la ricerca usando espressioni regolari. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Esegue la ricerca sul documento specificato. </p> <hr> <pre> L'esempio dimostra come trovare il testo in un documento PDF e sostituire il testo di tutte le occorrenze trovate. // Apri documento Document doc = new Document("D:\\Tests\\input.pdf"); // Trova il font che verrà usato per modificare il font del testo del documento Font font = FontRepository.findFont("Arial"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'absorber per la prima pagina absorber.visit(doc); // Modifica il testo della prima occorrenza absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Salva il documento doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Esegue la ricerca sulla pagina specificata. </p> <hr> <pre> L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo. // Apri documento Document doc = new Document("D:\\Tests\\input.pdf"); // Trova il font che verrà usato per modificare il font del testo del documento Font font = FontRepository.findFont("Arial"); // Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accetta l'absorber per la prima pagina absorber.visit(doc.getPages().get(1)); // Modifica il testo di tutte le occorrenze trovate for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Salva il documento doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
Esegue la ricerca sull'oggetto form specificato.
