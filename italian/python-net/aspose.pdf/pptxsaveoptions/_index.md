---
title: "PptxSaveOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Opzioni di salvataggio per l'esportazione in formato SVG"
type: docs
weight: 1290
url: /it/python-net/aspose.pdf/pptxsaveoptions/
---

## PptxSaveOptions class

Opzioni di salvataggio per l'esportazione in formato SVG

Il tipo PptxSaveOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PptxSaveOptions() | Inizializza una nuova istanza della classe PptxSaveOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| warning_handler | Callback per gestire eventuali avvisi generati. <br/>            Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. <br/>            Continuare è l'azione predefinita e l'operazione di Salvataggio continua, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di Salvataggio dovrebbe cessare. |
| save_format | Formato di salvataggio dei dati. |
| close_response | Ottiene o imposta il valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| extract_ocr_sublayer_only | Questo attributo attiva la funzionalità di estrazione di immagini o testo <br/>            per documenti PDF con sottostrato OCR. |
| try_merge_adjacent_same_background_images | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella)<br/>              costruite da diverse immagini di sfondo a tassello identiche posizionate vicine tra loro.<br/>              In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano<br/>              confini visibili tra le parti delle immagini di sfondo,<br/>              poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader.<br/>               Se sembra che il documento esportato contenga tali confini visibili tra <br/>              le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare <br/>              questo effetto indesiderato. <br/>                ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione,<br/>              quindi, per favore, utilizza questa opzione solo quando è davvero necessaria. |
| slides_as_images | Se impostato su true, tutto il contenuto viene riconosciuto come immagini (una per pagina) |
| image_resolution | Ottiene o imposta la risoluzione dell'immagine (dpi). Il valore predefinito è 192 dpi. |
| separate_images | Se impostato su true, le immagini vengono separate da tutte le altre grafiche |
| optimize_text_boxes | Attiva/disattiva il riconoscimento delle colonne di testo |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

