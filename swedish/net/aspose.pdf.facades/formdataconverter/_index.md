---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormDataConverter klass. Representerar en klass för att konvertera data från ett format till ett annat format. Den kan konvertera data i fdf/xml/pdf/xfdf till OLEDB/OdbcDB. Den kan också konvertera data i OLEDB/OdbcDB till data i fdf/xml/xfdf. Den kan konvertera fdf till xml med "hårdnämd" tagg.
type: docs
weight: 4320
url: /sv/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter klass

Representerar en klass för att konvertera data från ett format till ett annat format. Den kan konvertera data i fdf/xml/pdf/xfdf till OLEDB/OdbcDB. Den kan också konvertera data i OLEDB/OdbcDB till data i fdf/xml/xfdf. Den kan konvertera fdf till xml med "hårdnämd" tagg.

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
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData kommer att rensa tabellen före dataexport. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable kommer att skapa nödvändig fält om det inte finns i tabellen. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase kommer att skapa tabell om den inte finns. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase kommer att ta bort befintlig tabell och skapa en ny tabell om denna egenskap är inställd på true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Hämtar eller ställer in den mellanliggande datakontainern, en DataTable. Den måste definieras innan data konverteras från ett format till ett annat format. Kolumnerna och TableName för DataTable bör definieras. TableName är namnet på tabellen i databasen. Varje kolumns ColumnName är det kvalificerade fältnamnet för pdf. Varje kolumns Caption är kolumnnamnet för tabellen i databasen. Om fältnamnet är detsamma som tabellkolumnnamnet, behöver Caption inte specificeras. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Denna metod är föråldrad. Vänligen använd ConvertToStreams() istället. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Konvertera filer av strömmar till tabell. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Konvertera data i tabellen till strömmar. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Exporterar data från databasen till tabell. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Importerar data från tabell till databas. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Konvertera FDF-fil till XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Konvertera XML import/export formulärdatafil till FDF-format. |

### Se Även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)