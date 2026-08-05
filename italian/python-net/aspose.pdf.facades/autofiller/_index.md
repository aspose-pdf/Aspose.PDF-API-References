---
title: "AutoFiller"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per ricevere dati da un database o altra fonte dati, li inserisce nei campi progettati del modello pdf e infine genera un nuovo file pdf o stream.<br/>             Ha due modalità di input del file modello: input come stream o file pdf.<br/>             Ha quattro tipi di modalità di output: un stream unito, un file unito, molti piccoli stream, molti piccoli file.<br/>             Può ricevere dati letterali contenuti in un System.Data.DataTable."
type: docs
weight: 20
url: /it/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

Rappresenta una classe per ricevere dati da un database o altra fonte dati, li inserisce nei campi progettati del modello pdf e infine genera un nuovo file pdf o stream.<br/>             Ha due modalità di input del file modello: input come stream o file pdf.<br/>             Ha quattro tipi di modalità di output: un stream unito, un file unito, molti piccoli stream, molti piccoli file.<br/>             Può ricevere dati letterali contenuti in un System.Data.DataTable.

Il tipo AutoFiller espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| AutoFiller() | Inizializza una nuova istanza della classe AutoFiller |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| output_stream | Ottiene o imposta l'OutputStream. Uno dei quattro modalità di output. Il suo caso d'uso classico è Response.OutputStream.<br/>            Si prega di consultare la demo online. |
| output_streams | Ottiene o imposta i numerosi Output Streams. Uno dei quattro modalità di output. |
| input_stream | Ottiene o imposta lo stream del modello di input. Uno dei due modalità di input. |
| input_file_name | Ottiene o imposta il file modello di input. Uno dei due modalità di input. |
| output_file_name | Ottiene o imposta il singolo grande file di output unito. Uno dei quattro modalità di output. |
| generating_path | Ottiene o imposta il Percorso di Generazione dei piccoli file pdf se devono essere generati molti piccoli file pdf. Funziona con un'altra proprietà [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName.<br/>            Uno dei quattro modalità di output. |
| basic_file_name | Ottiene o imposta il nome file di base se devono essere generati molti piccoli file. Il file generato sarà del tipo "BasicFileName0","BasicFileName1",...<br/>            Funziona con un'altra proprietà [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| save() | Salva tutti i pdf. |
| save(dest_file) | Salva tutti i pdf. |
| save(dest_stream) | Salva tutti i pdf. |
| bind_pdf(src_file) | Associa un file Pdf. |
| bind_pdf(src_stream) | Associa un file Pdf. |
| bind_pdf(src_doc) | Associa un documento Pdf. |
| close() | Chiude l'oggetto e gli stream di output. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

