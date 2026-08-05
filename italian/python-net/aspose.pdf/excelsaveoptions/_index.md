---
title: "ExcelSaveOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Opzioni di salvataggio per l'esportazione in formato Excel"
type: docs
weight: 330
url: /it/python-net/aspose.pdf/excelsaveoptions/
---

## ExcelSaveOptions class

Opzioni di salvataggio per l'esportazione in formato Excel

Il tipo ExcelSaveOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| ExcelSaveOptions() | Inizializza una nuova istanza della classe ExcelSaveOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| warning_handler | Callback per gestire eventuali avvisi generati. <br/>            Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. <br/>            Continuare è l'azione predefinita e l'operazione di Salvataggio continua, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di Salvataggio dovrebbe cessare. |
| save_format | Formato di salvataggio dei dati. |
| close_response | Ottiene o imposta il valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| extract_ocr_sublayer_only | Questo attributo attiva la funzionalità di estrazione di immagini o testo <br/>            per documenti PDF con sottostrato OCR. |
| try_merge_adjacent_same_background_images | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella)<br/>              costruite da diverse immagini di sfondo a tassello identiche posizionate vicine tra loro.<br/>              In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano<br/>              confini visibili tra le parti delle immagini di sfondo,<br/>              poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader.<br/>               Se sembra che il documento esportato contenga tali confini visibili tra <br/>              le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare <br/>              questo effetto indesiderato. <br/>                ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione,<br/>              quindi, per favore, utilizza questa opzione solo quando è davvero necessaria. |
| minimize_the_number_of_worksheets | Imposta true se è necessario ridurre al minimo il numero di fogli di lavoro nella cartella di lavoro risultante.<br/>            Il valore predefinito è false; significa che ogni pagina PDF viene salvata come foglio di lavoro separato. |
| insert_blank_column_at_first | Imposta true se è necessario inserire una colonna vuota come prima colonna del foglio di lavoro.<br/>            Il valore predefinito è false; significa che la colonna vuota non verrà inserita. |
| uniform_worksheets | Imposta true per utilizzare una divisione uniforme delle colonne nel documento. <br/>            Il valore predefinito è false; significa che la divisione delle colonne sarà indipendente per ogni pagina. |
| formato | Formato di output |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

