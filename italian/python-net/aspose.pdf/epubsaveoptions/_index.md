---
title: "EpubSaveOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Opzioni di salvataggio per l'esportazione in formato EPUB"
type: docs
weight: 320
url: /it/python-net/aspose.pdf/epubsaveoptions/
---

## EpubSaveOptions class

Opzioni di salvataggio per l'esportazione in formato EPUB

Il tipo EpubSaveOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| EpubSaveOptions() | Inizializza una nuova istanza della classe EpubSaveOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| warning_handler | Callback per gestire eventuali avvisi generati. <br/>            Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. <br/>            Continuare è l'azione predefinita e l'operazione di Salvataggio continua, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di Salvataggio dovrebbe cessare. |
| save_format | Formato di salvataggio dei dati. |
| close_response | Ottiene o imposta il valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| extract_ocr_sublayer_only | Questo attributo attiva la funzionalità di estrazione di immagini o testo <br/>            per documenti PDF con sottostrato OCR. |
| try_merge_adjacent_same_background_images | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella)<br/>              costruite da diverse immagini di sfondo a tassello identiche posizionate vicine tra loro.<br/>              In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano<br/>              confini visibili tra le parti delle immagini di sfondo,<br/>              poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader.<br/>               Se sembra che il documento esportato contenga tali confini visibili tra <br/>              le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare <br/>              questo effetto indesiderato. <br/>                ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione,<br/>              quindi, per favore, utilizza questa opzione solo quando è davvero necessaria. |
| content_recognition_mode | Quando il file PDF (che di solito ha un layout fisso) viene convertito,<br/>            il motore di conversione tenta di eseguire il raggruppamento e l'analisi a più livelli per ripristinare<br/>            l'intento originale dell'autore del documento e produrre un risultato in layout fluido.<br/>               Questa proprietà regola tale conversione per questo o quello<br/>            metodo desiderabile di riconoscimento del contenuto. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

