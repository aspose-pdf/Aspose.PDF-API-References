---
title: "Heading"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta l'intestazione."
type: docs
weight: 460
url: /it/python-net/aspose.pdf/heading/
---

## Heading class

Rappresenta l'intestazione.

Il tipo Heading espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Heading(level) | Inizializza una nuova istanza della classe Heading |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| vertical_alignment | Ottiene o imposta l'allineamento verticale del frammento di testo. |
| horizontal_alignment | Ottiene o imposta l'allineamento orizzontale del frammento di testo. |
| margine | Ottiene o imposta un margine esterno per il paragrafo (per la generazione PDF) |
| is_first_paragraph_in_column | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| is_kept_with_next | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| is_in_new_page | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| is_in_line_paragraph | Ottiene o imposta se un paragrafo è in linea.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| collegamento | Imposta il collegamento ipertestuale del frammento |
| z_index | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande <br/>            verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo <br/>            verrà posizionato dietro il testo nella pagina. |
| replace_options | Ottiene le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con una versione più corta o più lunga. |
| text | Ottiene o imposta l'oggetto stringa di testo che l'oggetto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) rappresenta. |
| text_state | Ottiene o imposta lo stato del testo per il testo che l'oggetto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) rappresenta. |
| segments | Ottiene i segmenti di testo per l'attuale [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| position | Ottiene o imposta la posizione del testo per il testo, rappresentato con l'oggetto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| baseline_position | Ottiene la posizione del testo per il testo, rappresentato con l'oggetto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/).<br/>            L'YIndent della struttura Position rappresenta la coordinata di base della linea del frammento di testo. |
| rectangle | Ottiene il rettangolo del TextFragment |
| pagina | Ottiene la pagina che contiene il TextFragment |
| modulo | Ottiene l'oggetto modulo che contiene il TextFragment |
| wrap_lines_count | Ottiene o imposta wrap lines count per questo paragrafo (solo per la generazione di PDF) |
| end_note | Ottiene o imposta la nota finale del paragrafo (solo per la generazione di PDF) |
| foot_note | Ottiene o imposta la nota a piè di pagina del paragrafo (solo per la generazione di PDF) |
| toc_page | Ottiene la pagina che contiene questa intestazione. |
| top | Ottiene il valore Y superiore di queste intestazioni. |
| start_number | Ottiene il numero di inizio dell'intestazione. |
| is_auto_sequence | Ottiene se l'intestazione deve essere numerata automaticamente. |
| is_in_list | Ottiene se l'intestazione deve essere nell'elenco del sommario. |
| destination_page | Ottiene la pagina di destinazione. |
| level | Ottiene il livello. |
| style | Ottiene o imposta lo stile. |
| user_label | Ottiene o imposta l'etichetta utente. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| clone() | Clona l'intestazione. |
| isolate_text_segments(start_index, length) | Ottiene [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) che rappresentano la parte specificata del testo del [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| clone_with_segments() | Clona l'intestazione con tutti i segmenti. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

