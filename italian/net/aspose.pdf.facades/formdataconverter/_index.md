---
title: "Classe FormDataConverter"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Facades.FormDataConverter. Rappresenta una classe per convertire i dati da un formato all'altro. Può convertire i dati in fdf/xml/pdf/xfdf in OLEDB/OdbcDB. Può anche convertire i dati in OLEDB/OdbcDB nei dati in fdf/xml/xfdf. Può convertire il fdf in xml con tag hardnamed"
type: docs
weight: 4440
url: /it/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

Rappresenta una classe per convertire i dati da un formato a un altro. Può convertire i dati in fdf/xml/pdf/xfdf nel OLEDB/OdbcDB. Può anche convertire i dati nel OLEDB/OdbcDB nei dati in fdf/xml/xfdf. Può convertire il fdf in xml con un tag "hard-named".

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
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData cancellerà la tabella prima dell'esportazione dei dati. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable creerà il campo richiesto se non esiste nella Table. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase creerà la table se non esiste. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase eliminerà la table esistente e ne creerà una nuova se questa proprietà è impostata su true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Ottiene o imposta il contenitore dati intermedio, un DataTable. Deve essere definito prima di convertire i dati da un formato all'altro. Le Columns e il TableName del DataTable devono essere definiti. Il TableName è il nome della Table nel database. Il ColumnName di ogni colonna è il nome del campo qualificato del pdf. La Caption di ogni colonna è il nome della colonna della table nel database. Se il nome del campo è lo stesso del nome della colonna della table, la Caption non è necessaria. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Questo metodo è obsoleto. Si prega di utilizzare ConvertToStreams() al suo posto. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Converti i file di strems in una table. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Converti i dati nella table in streams. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Esporta i dati dal database nella table. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Importa i dati dalla table nel database. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Converti il file FDF in XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Converti il file di dati del modulo XML import/export in formato FDF. |

### Vedi anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


