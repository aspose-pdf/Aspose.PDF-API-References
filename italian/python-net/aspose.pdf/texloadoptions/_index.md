---
title: "TeXLoadOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta le opzioni per il caricamento/importazione di un file TeX in un documento PDF."
type: docs
weight: 1520
url: /it/python-net/aspose.pdf/texloadoptions/
---

## TeXLoadOptions class

Rappresenta le opzioni per il caricamento/importazione di un file TeX in un documento PDF.

Il tipo TeXLoadOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| TeXLoadOptions() | Inizializza una nuova istanza della classe TeXLoadOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| warning_handler | Callback per gestire eventuali avvisi generati. <br/>            Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. <br/>            Continue è l'azione predefinita e l'operazione di Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di Load dovrebbe terminare. |
| load_format | Rappresenta il formato di file che [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) descrive. |
| job_name | Ottiene/imposta il nome del lavoro. |
| input_directory | Ottiene/imposta la directory di input TeX. |
| output_directory | Ottiene/imposta la directory di output TeX. |
| repeat | Ottiene/imposta il flag che indica se è necessario eseguire il lavoro TeX due volte nel caso,<br/>            ad esempio, ci siano riferimenti nei file TeX di input. In generale, questo comportamento è utile quando<br/>            il motore raccoglie alcuni dati durante il processo di composizione e li memorizza in un file ausiliario,<br/>            tutto al primo avvio. E al secondo avvio, il motore in qualche modo utilizza tali dati. |
| subset_fonts | Ottiene/imposta il flag che indica se sottodividere i caratteri nel file di output o meno. |
| show_terminal_output | Ottiene/imposta il flag che indica se mostrare l'output del terminale sulla console. |
| date_time | Ottiene/imposta un certo valore per le primitive data/ora come \year, \month, \day e \time. |
| no_ligatures | Ottiene/imposta un flag che annulla le legature in tutti i caratteri. |
| rasterize_formulas | Ottiene/imposta un flag che consente di rasterizzare le formule matematiche. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

