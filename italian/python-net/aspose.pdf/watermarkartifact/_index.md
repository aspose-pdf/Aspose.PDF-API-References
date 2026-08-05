---
title: "WatermarkArtifact"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "La classe descrive l'artefatto della filigrana. Questo può essere usato per"
type: docs
weight: 1640
url: /it/python-net/aspose.pdf/watermarkartifact/
---

## WatermarkArtifact class

La classe descrive l'artefatto della filigrana. Questo può essere usato per

Il tipo WatermarkArtifact espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| WatermarkArtifact() | Crea un'istanza dell'artifact Watermark. |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| custom_type | Ottiene il nome del tipo di artifact. Può essere usato se il tipo di artifact non è standard. |
| custom_subtype | Ottiene il nome del sottotipo di artifact. Può essere usato se il sottotipo di artifact non è un sottotipo standard. |
| type | Ottiene il tipo di artifact. |
| subtype | Ottiene il sottotipo di artifact. Se l'artifact ha un sottotipo non standard, il nome del sottotipo può essere letto tramite CustomSubtype. |
| contents | Ottiene la collezione degli operatori interni dell'artifact. |
| modulo | Ottiene XForm dell'artifact (se XForm è usato). |
| rectangle | Ottiene il rettangolo dell'artifact. |
| position | Ottiene o imposta la posizione dell'artifact.<br/>            Se questa proprietà è specificata, i margini e gli allineamenti sono ignorati. |
| right_margin | Margine destro dell'artifact. <br/>            Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| left_margin | Margine sinistro dell'artifact. <br/>            Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| top_margin | Margine superiore dell'artifact. <br/>            Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| bottom_margin | Margine inferiore dell'artifact. <br/>            Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| artifact_horizontal_alignment | Allineamento orizzontale dell'artifact. <br/>            Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| artifact_vertical_alignment | Allineamento verticale dell'artifact. <br/>            Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| rotation | Ottiene o imposta l'angolo di rotazione dell'artifact. |
| text | Ottiene il testo dell'artifact. |
| image | Ottiene l'immagine dell'artifact (se presente). |
| opacità | Ottiene o imposta l'opacità dell'artifact. I valori possibili sono nell'intervallo 0..1. |
| righe | Righe dell'artifact di testo multilinea. |
| text_state | Stato del testo per il testo dell'artifact. |
| is_background | Se vero l'Artifact è posizionato dietro i contenuti della pagina. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| set_image(image_stream) | Imposta l'immagine dell'artifact. |
| set_image(image_name) | Imposta l'immagine dell'artifact. |
| set_text(formatted_text) | Imposta il testo dell'artifact. |
| set_text_and_state(text, text_state) | Imposta il testo e le proprietà del testo dell'artifact. |
| set_lines_and_state(text, text_state) | Imposta il testo e le proprietà del testo dell'artifact. Consente di specificare più righe. |
| set_pdf_page(page) | Imposta la pagina PDF che viene posizionata sulla pagina del documento come artifact. |
| get_value(name) | Ottiene il valore personalizzato dell'artifact. |
| set_value(name, value) | Imposta il valore personalizzato dell'artifact. |
| remove_value(name) | Rimuove il valore personalizzato dall'artifact. |
| begin_updates() | Avvia gli aggiornamenti ritardati. Usa questa funzionalità se devi apportare diverse modifiche allo stesso artefatto per migliorare le prestazioni. <br/>            Di solito gli operatori dell'artefatto vengono modificati in qualsiasi momento quando la proprietà dell'artefatto è cambiata. Questo causa la modifica del contenuto della pagina<br/>            ogni volta che l'artefatto è cambiato. Per evitare questo effetto, inserisci tutti gli aggiornamenti dell'artefatto tra le chiamate StartUpdates/SaveUpdates.<br/>            Questo consente di modificare il contenuto della pagina una sola volta. |
| save_updates() | Salva tutti gli aggiornamenti nell'artefatto che sono stati effettuati dopo la chiamata a BeginUpdates(). |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

