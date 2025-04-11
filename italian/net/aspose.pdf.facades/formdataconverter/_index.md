---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.FormDataConverter. Rappresenta una classe per convertire i dati da un formato a un altro formato. Può convertire i dati in fdf/xml/pdf/xfdf in OLEDB/OdbcDB. Può anche convertire i dati in OLEDB/OdbcDB nei dati in fdf/xml/xfdf. Può convertire il fdf in xml con tag "hard-named".
type: docs
weight: 4320
url: /it/net/aspose.pdf.facades/formdataconverter/
---
## Classe FormDataConverter

Rappresenta una classe per convertire i dati da un formato a un altro formato. Può convertire i dati in fdf/xml/pdf/xfdf in OLEDB/OdbcDB. Può anche convertire i dati in OLEDB/OdbcDB nei dati in fdf/xml/xfdf. Può convertire il fdf in xml con tag "hard-named".

```csharp
public sealed class FormDataConverter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData pulirà la tabella prima dell'esportazione dei dati. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable creerà il campo richiesto se non esiste nella Tabella. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase creerà la tabella se non esiste. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase eliminerà la tabella esistente e creerà una nuova tabella se questa proprietà è impostata su true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Ottiene o imposta il contenitore dati intermedio, una DataTable. Deve essere definito prima di convertire i dati da un formato a un altro formato. Le colonne e il nome della tabella della DataTable devono essere definiti. Il TableName è il nome della Tabella nel database. Ogni ColumnName della colonna è il nome del campo qualificato del pdf. Ogni Caption della colonna è il nome della colonna della tabella nel database. Se il nome del campo è lo stesso del nome della colonna della tabella, la Caption non deve essere specificata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Questo metodo è obsoleto. Si prega di utilizzare ConvertToStreams() invece. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Converte file di flussi in tabella. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Converte i dati nella tabella in flussi. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Esporta i dati dal database nella tabella. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Importa i dati dalla tabella nel database. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Converte il file FDF in XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Converte il file di dati del modulo XML import/export in formato FDF. |

### Vedi Anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)