---
title: "FormDataConverter"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per convertire dati da un formato a un altro.<br/>            Può convertire i dati in fdf/xml/pdf/xfdf verso OLEDB/OdbcDB.<br/>            Può anche convertire i dati in OLEDB/OdbcDB verso fdf/xml/xfdf.<br/>            Può convertire il fdf in xml con tag \"hard-named\"."
type: docs
weight: 100
url: /it/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Rappresenta una classe per convertire dati da un formato a un altro.<br/>            Può convertire i dati in fdf/xml/pdf/xfdf verso OLEDB/OdbcDB.<br/>            Può anche convertire i dati in OLEDB/OdbcDB verso fdf/xml/xfdf.<br/>            Può convertire il fdf in xml con tag "hard-named".

Il tipo FormDataConverter espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| FormDataConverter() | Inizializza una nuova istanza della classe FormDataConverter |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| create_missing_field | ConvertToDataTable creerà il campo richiesto se non esiste nella Tabella. |
| replace_existing_table | ImportIntoDatabase eliminerà la tabella esistente e creerà una nuova tabella se questa proprietà è impostata su true. |
| clear_table_before_export | ExportFromData cancellerà la tabella prima dell'esportazione dei dati. |
| create_missing_table | ImportIntoDatabase creerà la tabella se non esiste. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | Converti il file XML di import/export dei dati del modulo nel formato FDF. |
| convert_fdf_to_xml(source_fdf, dest_xml) | Converti il file FDF in XML. |
| convert_to_data_table(source_streams, source_type) | Converti i file di stream in una tabella. |
| import_into_data_base(connect_string, db_type) | Importa i dati dalla tabella nel database. |
| export_from_data_base(connect_string, db_type) | Esporta i dati dal database nella tabella. |
| convert_to_streams(dest_stream, dest_type) | Converti i dati nella tabella in flussi. |
| conver_to_streams(dest_stream, dest_type) | Questo metodo è obsoleto. Usa ConvertToStreams() invece. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

