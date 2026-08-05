---
title: "FormEditor"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe per modificare i moduli (aggiunta/cancellazione di campi ecc.)"
type: docs
weight: 110
url: /it/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Classe per modificare i moduli (aggiunta/cancellazione di campi ecc.)

Il tipo FormEditor espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| FormEditor(src_stream, dest_stream) | Inizializza una nuova istanza della classe FormEditor |
| FormEditor(src_file_name, dest_file_name) | Inizializza una nuova istanza della classe FormEditor |
| FormEditor() | Costruttore per FormEditor. |
| FormEditor(document) | Inizializza una nuova istanza della classe FormEditor |
| FormEditor(document, dest_file_name) | Inizializza una nuova istanza della classe FormEditor |
| FormEditor(document, dest_stream) | Inizializza una nuova istanza della classe FormEditor |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| src_file_name | Ottiene o imposta il nome del file di origine. |
| dest_file_name | Ottiene o imposta il nome del file di destinazione. |
| src_stream | Ottiene o imposta lo stream di origine. |
| dest_stream | Ottiene o imposta lo stream di destinazione. |
| items | Imposta gli elementi che saranno aggiunti a una nuova list box o combo box. |
| export_items | Imposta le opzioni per la combo box con valori di esportazione. |
| facade | Imposta gli attributi visivi del campo. |
| radio_gap | Il membro per registrare lo spazio tra due pulsanti radio adiacenti in pixel, il valore predefinito è 50. |
| radio_horiz | Il flag per indicare se i pulsanti radio sono disposti orizzontalmente o verticalmente, il valore predefinito è true. |
| radio_button_item_size | Ottiene o imposta la dimensione dell'elemento del pulsante radio (quando viene aggiunto un nuovo campo pulsante radio). |
| submit_flag | Imposta i flag di invio del pulsante submit |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(src_file) | Associa il documento PDF per la modifica. |
| bind_pdf(src_stream) | Associa il documento PDF per la modifica. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save() | Salva le modifiche nel file di destinazione. |
| save(dest_file) | Salva le modifiche nel file di destinazione. |
| save(dest_stream) | Salva le modifiche nel file di destinazione. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | Aggiunge un campo del tipo specificato al modulo. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | Aggiunge un campo del tipo specificato al modulo. |
| copy_inner_field(field_name, new_field_name, page_num) | Copia un campo esistente nella stessa posizione del numero di pagina specificato.<br/>            Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento sorgente ha, tranne il campo appena copiato. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | Copia un campo esistente in una nuova posizione specificata sia dal numero di pagina che dalle coordinate.<br/>            Verrà prodotto un nuovo documento, che contiene tutto ciò che il documento sorgente ha, tranne il campo appena copiato. |
| copy_outer_field(src_file_name, field_name) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate originali.<br/>            Nota: Solo per campi AcroForm (esclusi i radio button). |
| copy_outer_field(src_file_name, field_name, page_num) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina specificato e le coordinate originali.<br/>             Nota: Solo per campi AcroForm (esclusi i radio button). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | Copia un campo esistente da un documento PDF a un altro documento con il numero di pagina e le coordinate specificati.<br/>            Nota: Solo per campi AcroForm (esclusi i radio button). |
| decorate_field(field_name) | Modifica gli attributi visivi del campo specificato. |
| decorate_field(field_type) | Modifica gli attributi visivi di tutti i campi con il tipo di campo specificato. |
| decorate_field() | Modifica gli attributi visivi del campo specificato. |
| add_list_item(field_name, item_name) | Aggiunge un nuovo elemento alla casella di riepilogo. |
| add_list_item(field_name, export_name) | Aggiunge un nuovo elemento con valore Export al campo casella di riepilogo esistente, solo per il campo combo box AcroForm. |
| close() | Chiude la facciata. |
| set_field_attribute(field_name, flag) | Imposta gli attributi del campo. |
| set_field_appearance(field_name, flags) | Imposta i flag del campo |
| get_field_appearance(field_name) | Ottiene i flag del campo. |
| set_submit_flag(field_name, submit_form_flag) | Imposta il flag di invio del pulsante di invio. |
| set_submit_url(field_name, url) | Imposta l'URL del pulsante. |
| set_field_limit(field_name, field_limit) | Imposta il conteggio massimo di caratteri del campo di testo. |
| set_field_comb_number(field_name, comb_number) | Imposta il numero di spazi (combs) per un campo di testo a riga singola regolare (il campo è <br/>            automaticamente diviso in tante posizioni equidistanti, o spazi, <br/>            quanto il valore del parametro combNumber). |
| move_field(field_name, llx, lly, urx, ury) | Imposta la nuova posizione del campo. |
| remove_field(field_name) | Rimuove il campo dal modulo. |
| reset_facade() | Reimposta tutti gli attributi visivi a valore vuoto. |
| reset_inner_facade() | Reimposta tutti gli attributi visivi della facciata interna a valore vuoto. |
| rename_field(field_name, new_field_name) | Modifica il nome del campo. |
| remove_field_action(field_name) | Rimuovi l'azione di invio del campo. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | Aggiungi un pulsante di invio al modulo. |
| del_list_item(field_name, item_name) | Elimina l'elemento dal campo elenco. |
| set_field_script(field_name, script) | Imposta JavaScript per un campo PushButton. Se esisteva un JavaScript precedente, verrà sostituito da quello nuovo. |
| add_field_script(field_name, script) | Aggiungi JavaScript per un campo PushButton. Se esiste un evento precedente, il nuovo evento viene aggiunto dopo di esso. |
| single_2_multiple(field_name) | Trasforma un campo di testo a riga singola in uno a più righe. |
| set_field_alignment(field_name, alignment) | Imposta lo stile di allineamento di un campo di testo. |
| set_field_alignment_v(field_name, alignment) | Imposta lo stile di allineamento verticale di un campo di testo. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

