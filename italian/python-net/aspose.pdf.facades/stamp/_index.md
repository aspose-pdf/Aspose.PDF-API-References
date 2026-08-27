---
title: "Stamp"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che rappresenta un timbro."
type: docs
weight: 410
url: /it/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

Classe che rappresenta un timbro.

Il tipo Stamp espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Stamp() | Inizializza una nuova istanza della classe Stamp |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| stamp_id | Ottiene o imposta l'identificatore del timbro. |
| qualità | Ottiene o imposta la qualità del timbro immagine in percentuale. Valori consentiti 0..100%. |
| opacità | Ottiene o imposta l'opacità del timbro. |
| page_number | Ottiene o imposta il numero di pagina. |
| pagine | Ottiene o imposta un array con i numeri delle pagine che saranno interessate dal timbro. <br/>            Se Pages = null tutte le pagine del documento sono interessate. |
| rotation | Ottiene o imposta la rotazione del timbro in gradi. |
| is_background | Ottiene o imposta lo stato di sfondo. Se true il timbro sarà posizionato come sfondo della pagina spampata.<br/>            Per impostazione predefinita è impostato su false. |
| blending_space | Ottiene o imposta un valore BlendingColorSpace che definisce uno spazio colore <br/>            utilizzato per eseguire operazioni di trasparenza e fusione sulla pagina. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(pdf_file, page_number) | Imposta il file PDF e il numero di pagina che saranno usati come timbro. |
| bind_pdf(pdf_stream, page_number) | Imposta il file PDF e il numero di pagina che saranno usati come timbro. |
| bind_image(image_file) | Imposta l'immagine come timbro. |
| bind_image(image) | Imposta l'immagine che sarà usata come timbro. |
| bind_logo(formatted_text) | Imposta il testo come timbro. |
| bind_text_state(text_state) | Imposta lo stato del testo del timbro. |
| set_origin(origin_x, origin_y) | Imposta la posizione nella pagina dove verrà posato il timbro. |
| set_image_size(width, height) | Imposta le dimensioni del timbro immagine. L'immagine verrà scalata in base ai valori specificati. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

