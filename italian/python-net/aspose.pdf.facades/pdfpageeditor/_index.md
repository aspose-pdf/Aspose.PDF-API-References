---
title: "PdfPageEditor"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per modificare la pagina del file PDF, includendo la rotazione della pagina, lo zoom, lo spostamento della posizione e la modifica delle dimensioni della pagina."
type: docs
weight: 340
url: /it/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

Rappresenta una classe per modificare la pagina del file PDF, includendo la rotazione della pagina, lo zoom, lo spostamento della posizione e la modifica delle dimensioni della pagina.

Il tipo PdfPageEditor espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfPageEditor() | Costruttore per la classe PdfPageEditor. |
| PdfPageEditor(document) | Inizializza una nuova istanza della classe PdfPageEditor |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| transition_duration | Ottiene o imposta la durata dell'effetto di transizione. |
| transition_type | Ottiene o imposta lo stile di transizione da utilizzare quando si passa a questa pagina da un'altra durante una presentazione. |
| display_duration | Ottiene o imposta la durata di visualizzazione per le pagine. |
| process_pages | Ottiene o imposta i numeri di pagina da modificare. Per impostazione predefinita, ogni pagina verrà modificata. |
| rotation | Ottiene o imposta la rotazione delle pagine, la rotazione deve essere 0, 90, 180 o 270.<br/>            Il valore predefinito è 0. |
| zoom | Ottiene o imposta il coefficiente di zoom. Il valore 1.0 corrisponde al 100%.<br/>            Il valore predefinito è 1.0. |
| page_size | Ottiene o imposta la dimensione della pagina del file di output. |
| alignment | Ottiene o imposta l'allineamento orizzontale del contenuto PDF originale nella pagina di risultato, il valore predefinito è AlignmentType.Left. |
| horizontal_alignment | Ottiene o imposta l'allineamento orizzontale del contenuto PDF originale nella pagina di risultato, il valore predefinito è AlignmentType.Left. |
| vertical_alignment | Ottiene o imposta l'allineamento verticale del contenuto PDF originale nella pagina di risultato, il valore predefinito è VerticalAlignmentType.Bottom. |
| vertical_alignment_type | Ottiene o imposta l'allineamento verticale del contenuto PDF originale nella pagina di risultato, il valore predefinito è VerticalAlignmentType.Bottom. |
| SPLITVOUT | Divisione verticale in uscita |
| SPLITHOUT | Divisione orizzontale in uscita |
| SPLITVIN | Divisione verticale in ingresso |
| SPLITHIN | Divisione orizzontale IN |
| BLINDV | Tende verticali |
| BLINDH | Tende verticali |
| INBOX | Scatola interna |
| OUTBOX | Scatola esterna |
| LRWIPE | Cancellazione sinistra-destra |
| RLWIPE | Cancellazione destra-sinistra |
| BTWIPE | Cancellazione dal basso verso l'alto |
| TBWIPE | Cancellazione dall'alto verso il basso |
| DISSOLVE | La vecchia pagina si dissolve |
| LRGLITTER | Scintillio da sinistra a destra |
| TBGLITTER | Scintillio dall'alto verso il basso |
| DGLITTER | Scintillio diagonale |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(src_file) | Associa il documento PDF per la modifica. |
| bind_pdf(src_stream) | Associa il documento PDF per la modifica. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save(output_file) | Salva il documento modificato nel file. |
| save(output_stream) | Salva il documento modificato nello stream. |
| close() | Rilascia tutte le risorse associate alla facciata corrente. |
| move_position(move_x, move_y) | Sposta l'origine da (0, 0) al punto indicato. <br/>            L'origine è in basso a sinistra e l'unità è il punto (1 pollice = 72 punti). |
| get_pages() | Restituisce il numero totale di pagine. |
| get_page_size(page) | Restituisce le dimensioni della pagina specificata. |
| get_page_rotation(page) | Restituisce la rotazione della pagina specificata. |
| get_page_box_size(page, page_box_name) | Restituisce la dimensione della casella specificata nel documento. |
| apply_changes() | Applica le modifiche apportate alle pagine del documento. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

