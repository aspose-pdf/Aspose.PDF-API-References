---
title: "ComboBoxField"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che rappresenta un campo Combobox del modulo."
type: docs
weight: 50
url: /it/python-net/aspose.pdf.forms/comboboxfield/
---

## ComboBoxField class

Classe che rappresenta un campo Combobox del modulo.

Il tipo ComboBoxField espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| ComboBoxField() | Costruttore per ComboBoxField da utilizzare in Generator. |
| ComboBoxField(doc) | Inizializza una nuova istanza della classe ComboBoxField |
| ComboBoxField(page, rect) | Inizializza una nuova istanza della classe ComboBoxField |
| ComboBoxField(doc, rect) | Inizializza una nuova istanza della classe ComboBoxField |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| vertical_alignment | Nessuno |
| horizontal_alignment | Nessuno |
| margine | Nessuno |
| is_first_paragraph_in_column | Nessuno |
| is_kept_with_next | Nessuno |
| is_in_new_page | Nessuno |
| is_in_line_paragraph | Nessuno |
| collegamento | Nessuno |
| z_index | Nessuno |
| update_appearance_on_convert | Nessuno |
| use_font_subset | Nessuno |
| flags | Nessuno |
| annotation_type | Nessuno |
| width | Nessuno |
| actions | Nessuno |
| height | Nessuno |
| rect | Restituisce o imposta il rettangolo del campo. |
| contents | Nessuno |
| name | Nessuno |
| modified | Nessuno |
| color | Nessuno |
| border | Nessuno |
| active_state | Nessuno |
| characteristics | Nessuno |
| states | Nessuno |
| alignment | Nessuno |
| text_horizontal_alignment | Nessuno |
| full_name | Nessuno |
| appearance | Nessuno |
| page_index | Restituisce l'indice della pagina che contiene questo campo. |
| on_activated | Nessuno |
| evidenziazione | Nessuno |
| genitore | Nessuno |
| default_appearance | Nessuno |
| read_only | Nessuno |
| obbligatorio | Nessuno |
| esportabile | Nessuno |
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
| commit_immediately | Ottiene o imposta il flag di commit al cambiamento di selezione. |
| multi_select | Ottiene o imposta il flag di selezione multipla. |
| selected | Ottiene o imposta l'indice dell'opzione selezionata. Questa proprietà consente di modificare la selezione. |
| selected_items | Ottiene o imposta l'array degli elementi selezionati. Per un elenco a selezione multipla l'array contiene più di un elemento. Per un elenco a selezione singola contiene un solo elemento. |
| opzioni | Ottiene la collezione delle opzioni di scelta. |
| modificabile | Ottiene o imposta lo stato modificabile del campo. |
| spell_check | Ottiene o imposta lo stato dell'attività di correzione ortografica. |
## Indexer
| Nome | Descrizione |
| :- | :- |
| [index] | Ottiene il sottocampo contenuto in questo campo per indice. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| add_option(option_name) | Aggiunge una nuova opzione con il nome specificato. |
| add_option(export, name) | Aggiunge una nuova opzione con il nome specificato. |
| clone() | Nessuno |
| get_rectangle(consider_rotation) | Nessuno |
| accept(visitor) | Nessuno |
| flatten() | Rimuove questo campo e posiziona il suo valore direttamente nella pagina. |
| change_after_resize(transform) | Nessuno |
| recalculate() | Ricalcola tutti i campi calcolati nel modulo. |
| copy_to(array, index) | Copia i sotto‑campi di questo campo nell'array a partire dall'indice specificato. |
| set_position(point) | Imposta la posizione del campo. |
| delete_option(option_name) | Elimina l'opzione per nome. |

### Vedi anche

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

