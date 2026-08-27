---
title: "EpubLoadOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Contiene opzioni per il caricamento/importazione di file EPUB nel documento PDF."
type: docs
weight: 310
url: /it/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

Contiene opzioni per il caricamento/importazione di file EPUB nel documento PDF.

Il tipo EpubLoadOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| EpubLoadOptions() | Crea le opzioni di caricamento predefinite per convertire un file EPUB in documento PDF. <br/>            Dimensione predefinita della pagina PDF - A4 300dpi 2480 X 3508. |
| EpubLoadOptions(page_size) | Inizializza una nuova istanza della classe EpubLoadOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| warning_handler | Callback per gestire eventuali avvisi generati. <br/>            Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. <br/>            Continue è l'azione predefinita e l'operazione di Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di Load dovrebbe terminare. |
| load_format | Rappresenta il formato di file che [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) descrive. |
| page_size | Ottiene o imposta la dimensione della pagina di output per l'importazione. |
| margine | Ottiene un riferimento all'oggetto che rappresenta le informazioni sui margini. |
| margins_area_usage_mode | Rappresenta la modalità di utilizzo dell'area dei margini - definisce il trattamento <br/>              delle istruzioni (se presenti) CSS del documento importato<br/>              relative all'uso dei margini. |
| page_size_adjustment_mode | ATTENZIONE! La funzionalità è stata implementata ma non è ancora stata resa disponibile nell'API pubblica a causa di un problema bloccante nel <br/>              livello OSHARED rilevato per il documento di esempio.<br/>              <br/>             <br/>              Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione.<br/>             I formati (come HTML, EPUB ecc.), solitamente hanno un layout fluido, quindi consentono di adattare la dimensione della pagina richiesta.<br/>             Tuttavia a volte il contenuto ha posizioni orizzontali o dimensioni specificate che <br/>             non permettono di inserire il contenuto nella dimensione della pagina richiesta.<br/>               In tal caso possiamo definire cosa fare (ad esempio quando la dimensione del contenuto non si adatta <br/>             alla dimensione iniziale della pagina del documento PDF risultante). |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

