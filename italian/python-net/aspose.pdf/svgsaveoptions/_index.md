---
title: "SvgSaveOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Opzioni di salvataggio per l'esportazione in formato SVG"
type: docs
weight: 1460
url: /it/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

Opzioni di salvataggio per l'esportazione in formato SVG

Il tipo SvgSaveOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| SvgSaveOptions() | Inizializza una nuova istanza della classe SvgSaveOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| warning_handler | Callback per gestire eventuali avvisi generati. <br/>            Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continuare o Interrompere. <br/>            Continuare è l'azione predefinita e l'operazione di Salvataggio continua, tuttavia l'utente può anche restituire Interrompere, nel qual caso l'operazione di Salvataggio dovrebbe cessare. |
| save_format | Formato di salvataggio dei dati. |
| close_response | Ottiene o imposta il valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| extract_ocr_sublayer_only | Nessuno |
| try_merge_adjacent_same_background_images | Nessuno |
| treat_target_file_name_as_directory | Questa opzione definisce se verrà creata la directory di destinazione<br/>             (se ancora assente) con lo stesso nome del file di output richiesto <br/>             invece del file di output stesso.<br/>             In tal modo, la directory conterrà tutte le immagini SVG di output delle pagine (come descritto di seguito).<br/>               Se no, i file di output delle pagine diverse dalla prima verranno creati esattamente nella directory richiesta<br/>            come file di output principale, ma conterranno nel nome del file il suffisso _[2...n], che<br/>             è definito dal numero di pagina, per es. se definisci il file di output "C:\\AsposeTests\\output.svg"<br/>             e l'output conterrà diversi file svg delle pagine,<br/>             allora i file delle pagine saranno creati anche nella directory "C:\\AsposeTests\\" e avranno i nomi 'output.svg', 'output_2.svg', 'output_3.svg' ecc. |
| compress_output_to_zip_archive | Specifica se l'output verrà creato come un unico archivio zip.<br/>             Consulta il commento alle opzioni 'TreatTargetFileNameAsDirectory' per vedere le regole di denominazione<br/>             dei file svg delle pagine per documenti sorgente multipagina, che sono applicate anche al set compresso di file di output. |
| scale_to_pixels | Specifica se scalare il documento di output dai punti tipografici ai pixel. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

