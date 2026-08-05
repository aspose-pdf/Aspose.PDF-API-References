---
title: "DocSaveOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Opzioni di salvataggio per l'esportazione in formato Doc"
type: docs
weight: 220
url: /it/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Opzioni di salvataggio per l'esportazione in formato Doc

Il tipo DocSaveOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| DocSaveOptions() | Inizializza una nuova istanza della classe DocSaveOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| warning_handler | Callback per gestire eventuali avvisi generati. <br/>            Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. <br/>            Continuare è l'azione predefinita e l'operazione di Salvataggio continua, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di Salvataggio dovrebbe cessare. |
| save_format | Formato di salvataggio dei dati. |
| close_response | Ottiene o imposta il valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| extract_ocr_sublayer_only | Questo attributo attiva la funzionalità di estrazione di immagini o testo <br/>            per documenti PDF con sottostrato OCR. |
| try_merge_adjacent_same_background_images | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella)<br/>              costruite da diverse immagini di sfondo a tassello identiche posizionate vicine tra loro.<br/>              In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano<br/>              confini visibili tra le parti delle immagini di sfondo,<br/>              poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader.<br/>               Se sembra che il documento esportato contenga tali confini visibili tra <br/>              le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare <br/>              questo effetto indesiderato. <br/>                ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione,<br/>              quindi, per favore, utilizza questa opzione solo quando è davvero necessaria. |
| modalità | Modalità di riconoscimento. |
| relative_horizontal_proximity | In PDF le parole possono essere rappresentate internamente con operatori che stampano parole<br/>              stampando indipendentemente le loro lettere o sillabe. Quindi, per rilevare le parole a volte è necessario rilevare gruppi<br/>              di caratteri indipendenti che in realtà sono parole.<br/>                Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) <br/>              che deve essere considerata come distanza tra parole durante il riconoscimento delle parole nel PDF di origine.<br/>              (la presenza di uno spazio vuoto almeno di questa larghezza tra le lettere indica che <br/>               gli elementi testuali appartengono a parole diverse).<br/>              È normalizzata alla dimensione del carattere - 1.0 significa il 100% della dimensione del carattere della parola presunta.<br/>             ATTENZIONE! Viene usata solo nei casi in cui il PDF di origine contiene caratteri specifici raramente usati<br/>             per i quali il valore ottimale non può essere calcolato dal font. <br/>               Quindi, nella stragrande maggioranza dei casi questo parametro non cambia nulla nel documento risultante. |
| max_distance_between_text_lines | Questo parametro è usato per raggruppare le linee di testo in paragrafi.<br/>            Determina quanto possono essere distanti due linee di testo relative. Specificato in centinaia di percento dell'altezza delle linee di testo. |
| recognize_bullets | Attiva il riconoscimento dei punti elenco |
| add_return_to_line_end | Usa interruzioni di paragrafo o di riga |
| image_resolution_x | Risoluzione X delle immagini convertite. |
| image_resolution_y | Risoluzione Y delle immagini convertite. |
| formato | Formato di output |
| batch_size | Definisce la dimensione del batch se la conversione batch è applicabile<br/>            alla coppia di formati di origine e destinazione. |
| memory_save_mode_path | Definisce il percorso (nome file o nome directory) per contenere<br/>            dati temporanei durante la conversione in modalità di salvataggio in memoria. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

