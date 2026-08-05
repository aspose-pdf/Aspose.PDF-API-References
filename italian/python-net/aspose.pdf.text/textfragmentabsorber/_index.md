---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta un oggetto assorbitore di frammenti di testo.<br/>            Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)."
type: docs
weight: 400
url: /it/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Rappresenta un oggetto assorbitore di frammenti di testo.<br/>            Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/).

Il tipo TextFragmentAbsorber espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| TextFragmentAbsorber() | Inizializza una nuova istanza di [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. |
| TextFragmentAbsorber(text_edit_options) | Inizializza una nuova istanza della classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase) | Inizializza una nuova istanza della classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options) | Inizializza una nuova istanza della classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | Inizializza una nuova istanza della classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_edit_options) | Inizializza una nuova istanza della classe TextFragmentAbsorber |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| text | Ottiene il testo estratto che il [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) estrae dal documento PDF o dalla pagina. |
| has_errors | Il valore indica se sono stati trovati errori durante l'estrazione del testo.<br/>            La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| errors | Elenco di oggetti [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Contiene informazioni sugli errori trovati durante l'estrazione del testo.<br/>            La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| extraction_options | Ottiene o imposta le opzioni di estrazione del testo. |
| text_search_options | Ottiene o imposta le opzioni di ricerca. Le opzioni consentono la ricerca usando espressioni regolari. |
| text_fragments | Ottiene la collezione di occorrenze di ricerca presentate con oggetti [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| phrase | Ottiene o imposta la frase che il [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) ricerca nel documento PDF o nella pagina. |
| text_edit_options | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| text_replace_options | Ottiene o imposta le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con una lunghezza più corta o più lunga. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| visit(page) | Esegue la ricerca nella pagina specificata. |
| visit(pdf) | Esegue la ricerca nel documento specificato. |
| visit(x_form) | Esegue la ricerca nell'oggetto modulo specificato. |
| apply_for_all_fragments(font) | Applica il carattere a tutti i frammenti di testo che sono stati assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti sulla/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| apply_for_all_fragments(font_size) | Applica la dimensione del carattere a tutti i frammenti di testo che sono stati assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti sulla/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| apply_for_all_fragments(font, font_size) | Applica il carattere e la dimensione a tutti i frammenti di testo che sono stati assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti sulla/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| remove_all_text(page) | Rimuove tutto il testo dalla pagina specificata. |
| remove_all_text(page, rect) | Rimuove il testo all'interno del rettangolo specificato dalla pagina specificata. |
| remove_all_text(document) | Rimuove tutto il testo dal documento. |
| reset() | Cancella la collezione TextFragments di questo oggetto [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/). |

### Vedi anche

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

