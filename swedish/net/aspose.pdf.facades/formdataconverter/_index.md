---
title: "Klass FormDataConverter"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.FormDataConverter-klass. Representerar en klass för att konvertera data från ett format till ett annat format. Den kan konvertera data i fdf/xml/pdf/xfdf till OLEDB/OdbcDB. Den kan också konvertera data i OLEDB/OdbcDB till data i fdf/xml/xfdf. Den kan konvertera fdf till xml med hårdkodat tagg"
type: docs
weight: 4440
url: /sv/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

Representerar en klass för att konvertera data från ett format till ett annat format. Den kan konvertera data i fdf/xml/pdf/xfdf till OLEDB/OdbcDB. Den kan också konvertera data i OLEDB/OdbcDB till data i fdf/xml/xfdf. Den kan konvertera fdf till xml med \"hard-named\"‑tagg.

```csharp
public sealed class FormDataConverter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData rensar tabellen innan dataexport. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable skapar nödvändigt fält om det inte finns i tabellen. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase skapar tabell om den inte finns. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase tar bort befintlig tabell och skapar ny tabell om den här egenskapen är satt till true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Hämtar eller anger den mellersta databehållaren, en DataTable. Den måste definieras innan data konverteras från ett format till ett annat format. Kolumnerna och TableName för DataTable bör definieras. TableName är namnet på tabellen i databasen. Varje kolumns ColumnName är det kvalificerade fältnamnet i pdf:en. Varje kolumns Caption är kolumnnamnet i tabellen i databasen. Om fältnamnet är detsamma som tabellkolumnens namn behöver Caption inte specificeras. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Denna metod är föråldrad. Använd ConvertToStreams() istället. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Konvertera filer av strömmar till en tabell. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Konvertera data i tabellen till strömmar. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Exporterar data från databasen till en tabell. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Importerar data från tabellen till databasen. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Konvertera FDF-fil till XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Konvertera XML-import/export-formulärdatafil till FDF-format. |

### Se även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


