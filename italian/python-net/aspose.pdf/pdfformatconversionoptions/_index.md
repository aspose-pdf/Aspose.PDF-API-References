---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "rappresenta un insieme di opzioni per convertire un documento PDF"
type: docs
weight: 1220
url: /it/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

rappresenta un insieme di opzioni per convertire un documento PDF

Il tipo PdfFormatConversionOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | Inizializza una nuova istanza della classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format) | Inizializza una nuova istanza della classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(format) | Inizializza una nuova istanza della classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(format, action) | Inizializza una nuova istanza della classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | Inizializza una nuova istanza della classe PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_stream, format, action) | Inizializza una nuova istanza della classe PdfFormatConversionOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| is_async_image_streams_conversion_mode | Ottiene/imposta l'esecuzione dei flussi di immagini in modalità asincrona. |
| is_low_memory_mode | È abilitata la modalità di conversione a bassa memoria |
| formato | Formato PDF. |
| log_file_name | Percorso del file in cui verranno memorizzati i commenti. |
| log_stream | Flusso in cui verranno memorizzati i commenti. |
| error_action | Azione per gli oggetti che non possono essere convertiti |
| transparency_action | Azione per gli oggetti mascherati dell'immagine |
| convert_soft_mask_action | Azione per le immagini con maschera morbida. |
| predefinito | Ottiene l'oggetto PdfFormatConversionOptions con i parametri predefiniti |
| non_specification_cases | Contiene flag per controllare il processo di conversione PDF/A nei casi in cui il documento sorgente<br/>            non corrisponda alla specifica PDF/A. |
| symbolic_font_encoding_strategy | Strategia per copiare i dati di codifica per i font simbolici se il font TrueType simbolico<br/>            ha più di una sottotabella di codifica. |
| align_text | Questo flag controlla l'allineamento del testo nel documento convertito. Per impostazione predefinita la conversione del documento <br/>            non influisce sull'allineamento del testo e lo lascia invariato. Tuttavia, in alcuni casi la sostituzione dei font<br/>            provoca sovrapposizioni di testo o spazi extra nel documento convertito. Quando questo flag è impostato<br/>            verranno eseguite operazioni speciali di allineamento. Questo flag dovrebbe essere impostato solo per i documenti<br/>            che presentano problemi di testo sovrapposto o spazi extra, poiché l'uso di questo flag diminuisce<br/>            le prestazioni e in alcuni casi potrebbe corrompere il contenuto del testo. |
| pua_text_processing_strategy | Strategia per elaborare i simboli dall'area Private Use (PUA) Unicode. |
| optimize_file_size | Ottiene o imposta un flag che abilita/disabilita la modalità di conversione speciale per ottenere un documento PDF/A con dimensione ridotta.<br/>            Ora questo flag influisce sull'ottimizzazione dei caratteri utilizzati nel documento PDF, possibilmente, in futuro, questo flag <br/>            sarà anche usato per attivare l'ottimizzazione di altre strutture dati, come la grafica.  <br/>            L'insieme di questo flag e della modalità potrebbe ridurre significativamente la dimensione del file ma allo stesso tempo potrebbe<br/>            diminuire significativamente le prestazioni della conversione. |
| exclude_fonts_strategy | Strategia(e) per escludere i caratteri superflui e ridurre la dimensione del file del documento. <br/>            Questo parametro ha senso solo quando il flag [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) è impostato su true.<br/>            Per impostazione predefinita viene utilizzata la combinazione di strategie [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) e<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/). |
| font_embedding_options | Opzioni per i casi in cui non è possibile incorporare alcuni caratteri nel documento PDF. |
| unicode_processing_rules | Regole per risolvere i problemi di mappatura Unicode. Può essere null. |
| icc_profile_file_name | Ottiene o imposta il nome file del profilo ICC. In caso di null viene utilizzato il profilo ICC predefinito. |
| not_accessible_fonts | Questa proprietà è out-property. Contiene tutti i caratteri (nomi dei caratteri) che non sono stati trovati sul computer <br/>            durante l'ultima conversione PDF/A. |
| is_transfer_info | Ottiene o imposta se trasferire i dati da Info a Metadata quando convertito in PDF 2.0. True per impostazione predefinita. |
| align_strategy | Strategia per allineare il testo. Questo parametro ha senso solo quando il flag [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) è impostato su true. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

