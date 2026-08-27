---
title: "Tabella"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una tabella che può essere aggiunta alla pagina."
type: docs
weight: 1480
url: /it/python-net/aspose.pdf/table/
---

## Table class

Rappresenta una tabella che può essere aggiunta alla pagina.

Il tipo Tabella espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Table() | Inizializza una nuova istanza della classe Tabella |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| vertical_alignment | Ottiene o imposta l'allineamento verticale del paragrafo |
| horizontal_alignment | Ottiene o imposta l'allineamento orizzontale del paragrafo |
| margine | Ottiene o imposta un margine esterno per il paragrafo (per la generazione PDF) |
| is_first_paragraph_in_column | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| is_kept_with_next | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| is_in_new_page | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| is_in_line_paragraph | Ottiene o imposta se un paragrafo è in linea.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| collegamento | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore PDF). |
| z_index | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande <br/>            verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo <br/>            verrà posizionato dietro il testo nella pagina. |
| background_color | Ottiene o imposta il colore di sfondo della tabella |
| break_text | Ottiene o imposta il testo di interruzione per la tabella |
| corner_style | Ottiene o imposta gli stili degli angoli del bordo |
| repeating_rows_style | Ottiene lo stile per le righe ripetute |
| repeating_columns_count | Ottiene o imposta il numero massimo di colonne per la tabella |
| repeating_rows_count | Ottiene il conteggio delle prime righe ripetute per più pagine |
| column_widths | Ottiene le larghezze delle colonne della tabella. |
| broken | Ottiene o imposta la rottura verticale della tabella; |
| default_cell_border | Ottiene il bordo predefinito della cella; |
| default_column_width | Ottiene il bordo predefinito della cella; |
| righe | Ottiene le righe della tabella. |
| border | Ottiene o imposta il bordo. |
| default_cell_padding | Ottiene o imposta il padding predefinito della cella. |
| default_cell_text_state | Ottiene o imposta lo stato di testo predefinito della cella. |
| alignment | Ottiene o imposta l'allineamento della tabella. |
| left | Ottiene o imposta la coordinata sinistra della tabella. |
| top | Ottiene o imposta la coordinata superiore della tabella. |
| is_broken | Ottiene o imposta se la tabella è interrotta - verrà troncata per la pagina successiva. |
| is_borders_included | Ottiene o imposta il bordo incluso nelle larghezze delle colonne. |
| column_adjustment | Ottiene o imposta la regolazione delle colonne della tabella. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| clone() | Clona la tabella. |
| get_width() | Ottieni larghezza. |
| get_height(parent_page) | Ottieni altezza. |
| set_column_text_state(col_number, text_state) | Imposta altezza. |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | Importa un array monodimensionale di dati in una tabella. L'importazione avviene una cella per ogni elemento dell'array e<br/>              inizia dalla riga e colonna definite nei parametri. Durante l'importazione, se si rileva che le righe necessarie<br/>              sono ancora assenti (cioè la tabella di destinazione è troppo piccola per contenere tutti i dati), verranno create le righe necessarie |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

