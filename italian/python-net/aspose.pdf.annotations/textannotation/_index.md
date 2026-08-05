---
title: "TextAnnotation"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta un'annotazione testuale che è un “appunto adesivo” allegato a un punto nel documento PDF."
type: docs
weight: 820
url: /it/python-net/aspose.pdf.annotations/textannotation/
---

## TextAnnotation class

Rappresenta un'annotazione testuale che è un “appunto adesivo” allegato a un punto nel documento PDF.

Il tipo TextAnnotation espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| TextAnnotation(document) | Inizializza una nuova istanza della classe TextAnnotation |
| TextAnnotation(page, rect) | Inizializza una nuova istanza della classe TextAnnotation |
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
| title | Ottiene o imposta un testo che verrà visualizzato nella barra del titolo dell'annotazione. |
| rich_text | Ottiene o imposta una stringa di testo formattato da visualizzare nella finestra pop-up quando l'annotazione viene aperta. |
| creation_date | Ottiene data e ora in cui l'annotazione è stata creata. |
| subject | Ottiene il testo che rappresenta la descrizione dell'oggetto. |
| popup | Annotazione pop-up per inserire o modificare il testo associato a questa annotazione. |
| opacità | Ottiene o imposta il valore costante di opacità da utilizzare nella visualizzazione dell'annotazione. |
| in_reply_to | Un riferimento all'annotazione a cui questa annotazione è "in risposta a".<br/>            Entrambe le annotazioni devono trovarsi nella stessa pagina del documento. |
| reply_type | Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione<br/>            e quella specificata da InReplyTo. |
| open | Ottiene o imposta un flag che specifica se l'annotazione deve essere visualizzata inizialmente aperta. |
| icon | Ottiene o imposta un'icona da utilizzare nella visualizzazione dell'annotazione. |
| state | Ottiene o imposta lo stato a cui l'annotazione originale dovrebbe essere impostata. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| clone() | Nessuno |
| get_rectangle(consider_rotation) | Restituisce il rettangolo dell'annotazione tenendo conto della rotazione della pagina. |
| accept(visitor) | Accetta un oggetto visitor per elaborare l'annotazione. |
| flatten() | Posiziona i contenuti dell'annotazione direttamente sulla pagina,<br/>            l'oggetto annotazione verrà rimosso. |
| change_after_resize(transform) | Aggiorna i punti di Inizio e Fine, secondo la trasformazione della matrice. |

### Vedi anche

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

