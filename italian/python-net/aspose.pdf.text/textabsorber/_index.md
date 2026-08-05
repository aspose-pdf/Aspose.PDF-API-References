---
title: "TextAbsorber"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta un oggetto assorbitore di testo.<br/>            Esegue l'estrazione del testo e fornisce l'accesso al risultato tramite l'oggetto [text](/pdf/python-net/aspose.pdf.text/textabsorber/)."
type: docs
weight: 320
url: /it/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

Rappresenta un oggetto assorbitore di testo.<br/>            Esegue l'estrazione del testo e fornisce l'accesso al risultato tramite l'oggetto [text](/pdf/python-net/aspose.pdf.text/textabsorber/).

Il tipo TextAbsorber espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| TextAbsorber() | Inizializza una nuova istanza di [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/). |
| TextAbsorber(extraction_options) | Inizializza una nuova istanza della classe TextAbsorber |
| TextAbsorber(extraction_options, text_search_options) | Inizializza una nuova istanza della classe TextAbsorber |
| TextAbsorber(text_search_options) | Inizializza una nuova istanza della classe TextAbsorber |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| text | Ottiene il testo estratto che il [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) estrae dal documento PDF o dalla pagina. |
| has_errors | Il valore indica se sono stati trovati errori durante l'estrazione del testo.<br/>            La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| errors | Elenco di oggetti [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Contiene informazioni sugli errori trovati durante l'estrazione del testo.<br/>            La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| extraction_options | Ottiene o imposta le opzioni di estrazione del testo. |
| text_search_options | Ottiene o imposta le opzioni di ricerca del testo. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| visit(page) | Estrae il testo nella pagina specificata |
| visit(form) | Estrae il testo sul XForm specificato. |
| visit(pdf) | Estrae il testo sul documento specificato |

### Vedi anche

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

