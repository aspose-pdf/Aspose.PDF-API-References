---
title: "XslFoLoadOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta le opzioni per il caricamento/importazione di file XSL-FO in un documento PDF."
type: docs
weight: 1820
url: /it/python-net/aspose.pdf/xslfoloadoptions/
---

## XslFoLoadOptions class

Rappresenta le opzioni per il caricamento/importazione di file XSL-FO in un documento PDF.

Il tipo XslFoLoadOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| XslFoLoadOptions() | Crea l'oggetto [XslFoLoadOptions](/pdf/python-net/aspose.pdf/xslfoloadoptions/) senza dati xsl. |
| XslFoLoadOptions(xsl_file) | Inizializza una nuova istanza della classe XslFoLoadOptions |
| XslFoLoadOptions(xsl_stream) | Inizializza una nuova istanza della classe XslFoLoadOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| warning_handler | Callback per gestire eventuali avvisi generati. <br/>            Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. <br/>            Continue è l'azione predefinita e l'operazione di Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di Load dovrebbe terminare. |
| load_format | Rappresenta il formato di file che [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) descrive. |
| xsl_stream | Ottiene i dati xsl per convertire xml in documento pdf. |
| base_path | Il percorso/base URL da cui vengono cercati i percorsi relativi alle risorse esterne (se presenti) referenziate nel file SVG caricato. |
| parsing_errors_handling_type | Il documento XSLFO di origine può contenere errori di formattazione. Questo enum elenca le possibili strategie di gestione di tali errori |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

