---
title: "TextState"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta lo stato di un testo"
type: docs
weight: 490
url: /it/python-net/aspose.pdf.text/textstate/
---

## TextState class

Rappresenta lo stato di un testo

Il tipo TextState espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| TextState() | Crea un oggetto di stato del testo. |
| TextState(font_size) | Inizializza una nuova istanza della classe TextState |
| TextState(foreground_color) | Inizializza una nuova istanza della classe TextState |
| TextState(foreground_color, font_size) | Inizializza una nuova istanza della classe TextState |
| TextState(font_family) | Inizializza una nuova istanza della classe TextState |
| TextState(font_family, bold, italic) | Inizializza una nuova istanza della classe TextState |
| TextState(font_family, font_size) | Inizializza una nuova istanza della classe TextState |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| character_spacing | Ottiene o imposta la spaziatura dei caratteri del testo. |
| line_spacing | Ottiene o imposta l'interlinea del testo. |
| horizontal_scaling | Ottiene o imposta la scala orizzontale del testo. |
| subscript | Ottiene o imposta il pedice del testo. |
| superscript | Ottiene o imposta il apice del testo. |
| word_spacing | Ottiene o imposta la spaziatura delle parole del testo. |
| invisible | Ottiene o imposta l'invisibilità del testo. Questo riflette sostanzialmente lo stato [rendering_mode](/pdf/python-net/aspose.pdf.text/textstate/), eccetto alcuni casi speciali (come il ritaglio). |
| rendering_mode | Ottiene o imposta la modalità di rendering del testo. |
| font_size | Ottiene o imposta la dimensione del font del testo. |
| font | Ottiene o imposta il font del testo. |
| foreground_color | Ottiene o imposta il colore di primo piano del testo. |
| stroking_color | Ottiene o imposta il colore di primo piano del testo. |
| underline | Ottiene o imposta la sottolineatura per il testo, rappresentata dall'oggetto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) |
| strike_out | Imposta il barrato per il testo, rappresentato dall'oggetto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) |
| background_color | Imposta il colore di sfondo del testo. |
| font_style | Imposta lo stile del font del testo. |
| horizontal_alignment | Ottiene o imposta l'allineamento orizzontale del testo. |
| TAB_TAG | Puoi inserire questo tag nel testo per dichiarare la tabulazione. |
| TABSTOP_DEFAULT_VALUE | Valore predefinito della tabulazione nelle larghezze del carattere spazio del font predefinito. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| apply_changes_from(text_state) | Applica le impostazioni da un altro textState. |
| measure_string(str) | Misura la stringa. |

### Vedi anche

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

