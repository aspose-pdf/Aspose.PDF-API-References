---
title: "Field"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe base per i campi del modulo acro."
type: docs
weight: 90
url: /it/python-net/aspose.pdf.forms/field/
---

## Field class

Classe base per i campi del modulo acro.

Il tipo Field espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Field(doc) | Inizializza una nuova istanza della classe Field |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| vertical_alignment | Nessuno |
| horizontal_alignment | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| margine | Nessuno |
| is_first_paragraph_in_column | Nessuno |
| is_kept_with_next | Nessuno |
| is_in_new_page | Nessuno |
| is_in_line_paragraph | Nessuno |
| collegamento | Nessuno |
| z_index | Nessuno |
| update_appearance_on_convert | Se true, l'aspetto dell'annotazione verrà aggiornato prima di convertire il documento PF in immagine. Questo consente di convertire correttamente i campi ma probabilmente richiede più tempo. |
| use_font_subset | Se questa proprietà è impostata su true, i caratteri verranno aggiunti al documento come sottoinsiemi. Il valore predefinito è true. |
| flags | Flag dell'annotazione. |
| annotation_type | Restituisce il tipo di annotazione. |
| width | Ottiene o imposta la larghezza dell'annotazione. |
| actions | Restituisce le azioni dell'annotazione. |
| height | Ottiene o imposta l'altezza dell'annotazione. |
| rect | Restituisce o imposta il rettangolo del campo. |
| contents | Ottiene o imposta il testo dell'annotazione. |
| name | Ottiene o imposta il nome dell'annotazione nella pagina. |
| modified | Ottiene o imposta la data e l'ora in cui l'annotazione è stata modificata di recente. |
| color | Ottiene o imposta il colore dell'annotazione. |
| border | Ottiene o imposta le caratteristiche del bordo dell'annotazione. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| active_state | Ottiene o imposta lo stato di aspetto dell'annotazione corrente. |
| characteristics | Ottiene le caratteristiche dell'annotazione. |
| states | Ottiene il dizionario di aspetto dell'annotazione. |
| alignment | Allineamento dell'annotazione. Questa proprietà è obsoleta. Usa HorizontalAligment invece. |
| text_horizontal_alignment | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| full_name | Restituisce il nome completo dell'annotazione. |
| appearance | Restituisce il dizionario di aspetto dell'annotazione. |
| page_index | Restituisce l'indice della pagina che contiene questo campo. |
| on_activated | Un'azione che deve essere eseguita quando l'annotazione viene attivata. |
| evidenziazione | Modalità di evidenziazione dell'annotazione. |
| genitore | Ottiene il genitore dell'annotazione. |
| default_appearance | Ottiene o imposta l'aspetto predefinito del campo. |
| read_only | Ottiene o imposta lo stato di sola lettura del campo. |
| obbligatorio | Ottiene o imposta lo stato obbligatorio del campo. |
| esportabile | Ottiene o imposta il flag esportabile del campo. |
| partial_name | Ottiene o imposta il nome parziale del campo. |
| alternate_name | Ottiene o imposta il nome alternativo del campo (Un campo alternativo <br/>            nome che deve essere usato al posto del nome reale del campo <br/>            ovunque il campo debba essere identificato nell'interfaccia utente).<br/>            Il nome alternativo è usato come tooltip del campo in Adobe Acrobat. |
| mapping_name | Ottiene o imposta il nome di mapping del campo che deve essere usato durante l'esportazione dei dati dei campi modulo interattivi dal documento. |
| value | Ottiene o imposta il valore del campo. |
| is_synchronized | Restituisce true se il dizionario è sincronizzato. |
| sync_root | Oggetto di sincronizzazione. |
| is_group | Ottiene o imposta il valore booleano che indica se questo campo è un campo non terminale, cioè un gruppo di campi. |
| annotation_index | Ottiene o imposta l'indice di questa annotazione nella pagina. |
| is_shared_field | Proprietà per il supporto del Generatore. Utilizzata quando il campo è aggiunto all'intestazione o al piè di pagina. Se true, questo campo verrà creato una sola volta e la sua apparizione sarà visibile su tutte le pagine del documento. Se false, verrà creato un campo separato per ogni pagina del documento. |
| fit_into_rectangle | Se true, la dimensione del carattere verrà ridotta per adattare il testo al rettangolo specificato. |
| max_font_size | Dimensione massima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione. |
| min_font_size | Dimensione minima del carattere che può essere usata per il contenuto del campo. -1 per non verificare la dimensione. |
| tab_order | Ottiene o imposta l'ordine di tabulazione del campo. |
## Indexer
| Nome | Descrizione |
| :- | :- |
| [index] | Ottiene il sottocampo contenuto in questo campo per indice. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| clone() | Nessuno |
| get_rectangle(consider_rotation) | Restituisce il rettangolo dell'annotazione tenendo conto della rotazione della pagina. |
| accept(visitor) | Accetta il visitatore. |
| flatten() | Rimuove questo campo e posiziona il suo valore direttamente nella pagina. |
| change_after_resize(transform) | Aggiorna i parametri e l'aspetto, secondo la trasformazione della matrice. |
| recalculate() | Ricalcola tutti i campi calcolati nel modulo. |
| copy_to(array, index) | Copia i sotto‑campi di questo campo nell'array a partire dall'indice specificato. |
| set_position(point) | Imposta la posizione del campo. |

### Vedi anche

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

