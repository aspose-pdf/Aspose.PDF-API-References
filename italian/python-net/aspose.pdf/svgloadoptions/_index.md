---
title: "SvgLoadOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta le opzioni per il caricamento/importazione di file SVG in un documento pdf."
type: docs
weight: 1450
url: /it/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

Rappresenta le opzioni per il caricamento/importazione di file SVG in un documento pdf.

Il tipo SvgLoadOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| SvgLoadOptions() | Inizializza una nuova istanza della classe SvgLoadOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| warning_handler | Callback per gestire eventuali avvisi generati. <br/>            Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. <br/>            Continue è l'azione predefinita e l'operazione di Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di Load dovrebbe terminare. |
| load_format | Rappresenta il formato di file che [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) descrive. |
| page_info | Ottiene o imposta le informazioni di pagina che dovrebbero essere applicate durante il caricamento del documento.<br/>            NOTA che questo parametro funziona solo quando ConversionEngine == ConversionEngines.NewEngine |
| adjust_page_size | Adatta la dimensione della pagina pdf alla dimensione svg |
| conversion_engine | Consente di selezionare il motore di conversione che verrà utilizzato durante la conversione.<br/>            Attualmente il nuovo motore è in fase di B-testing, quindi questo valore è impostato per impostazione predefinita su <br/>            ConversionEngines.LegacyEngine |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

