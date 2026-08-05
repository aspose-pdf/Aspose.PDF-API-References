---
title: "RichMediaAnnotation"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che descrive RichMediaAnnotation che consente di incorporare dati video/audio nel documento PDF."
type: docs
weight: 710
url: /it/python-net/aspose.pdf.annotations/richmediaannotation/
---

## RichMediaAnnotation class

Classe che descrive RichMediaAnnotation che consente di incorporare dati video/audio nel documento PDF.

Il tipo RichMediaAnnotation espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| RichMediaAnnotation(page, rect) | Inizializza una nuova istanza della classe RichMediaAnnotation |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| vertical_alignment | Ottiene o imposta l'allineamento verticale del paragrafo |
| horizontal_alignment | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| margine | Ottiene o imposta un margine esterno per il paragrafo (per la generazione PDF) |
| is_first_paragraph_in_column | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| is_kept_with_next | Ottiene o imposta un valore bool che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| is_in_new_page | Ottiene o imposta un valore bool che forza la generazione di questo paragrafo in una nuova pagina.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| is_in_line_paragraph | Ottiene o imposta se un paragrafo è in linea.<br/>            Il valore predefinito è false. (per la generazione PDF) |
| collegamento | Ottiene o imposta il collegamento ipertestuale del frammento (per il generatore PDF). |
| z_index | Ottiene o imposta un valore intero che indica l'ordine Z del grafico. Un grafico con ZIndex più grande <br/>            verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo <br/>            verrà posizionato dietro il testo nella pagina. |
| update_appearance_on_convert | Se true, l'aspetto dell'annotazione verrà aggiornato prima di convertire il documento PF in immagine. Questo consente di convertire correttamente i campi ma probabilmente richiede più tempo. |
| use_font_subset | Se questa proprietà è impostata su true, i caratteri verranno aggiunti al documento come sottoinsiemi. Il valore predefinito è true. |
| flags | Flag dell'annotazione. |
| annotation_type | Restituisce il tipo di annotazione. |
| width | Ottiene o imposta la larghezza dell'annotazione. |
| actions | Restituisce l'elenco delle azioni di annotazione. |
| height | Ottiene o imposta l'altezza dell'annotazione. |
| rect | Restituisce o imposta il rettangolo dell'annotazione. |
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
| page_index | Restituisce l'indice della pagina che contiene l'annotazione. |
| custom_player | Imposta o ottiene il lettore flash personalizzato per riprodurre dati video/audio. |
| custom_flash_variables | Imposta o ottiene le variabili flash che vengono passate al lettore. |
| content | Dati del contenuto Rich Media. |
| type | Ottiene o imposta il tipo di contenuto. Valori possibili: Audio, Video. |
| activate_on | Evento che attiva l'applicazione. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| clone() | Clona questa istanza.<br/>            Metodo virtuale. Restituisce sempre null. |
| get_rectangle(consider_rotation) | Restituisce il rettangolo dell'annotazione tenendo conto della rotazione della pagina. |
| accept(visitor) | Accetta il visitatore per questa annotazione. |
| flatten() | Posiziona i contenuti dell'annotazione direttamente sulla pagina,<br/>            l'oggetto annotazione verrà rimosso. |
| change_after_resize(transform) | Aggiorna i parametri e l'aspetto, secondo la trasformazione della matrice. |
| add_custom_data(name, data) | Aggiunge dati personalizzati con nome (ad esempio richiesti per script flash). |
| set_content(file_name, audio) | Imposta il flusso di contenuto. |
| set_poster(image_stream) | Imposta il poster dell'annotazione. |
| update() | Aggiorna i dati con i parametri specificati. |

### Vedi anche

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

