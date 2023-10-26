---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormDataConverter class. Represents a class to convert data from one format to another format. It can convert the data in fdf/xml/pdf/xfdf to the OLEDB/OdbcDB. It also can convert the data in the OLEDB/OdbcDB to the data in fdf/xml/xfdf. It can convert the fdf to the xml with hardnamed tag
type: docs
weight: 2370
url: /net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

Represents a class to convert data from one format to another format. It can convert the data in fdf/xml/pdf/xfdf to the OLEDB/OdbcDB. It also can convert the data in the OLEDB/OdbcDB to the data in fdf/xml/xfdf. It can convert the fdf to the xml with "hard-named" tag.

```csharp
public sealed class FormDataConverter
```

## Constructors

| Name | Description |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData will clear table before data export. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable will create required field if it does not exists in Table. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase will create table if it does not exists. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase will drop existing table and create new table if this property set to true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Gets or sets the middle data container, one DataTable. It must be defined before converting data from one format to another format. The Columns and TableName of the DataTable should be defined. The TableName is the name of the Table in the database. Every column's ColumnName is the qualified field name of the pdf. Every column's Caption is the column name of table in the database. If the field name is the same as the table column name, the Caption need not specified. |

## Methods

| Name | Description |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | This method is obsolete. Please use ConvertToStreams() instead. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Convert files of strems into table. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Convert data in table into streams. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Exports data from database into table. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Imports data from table into database. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Convert FDF file into XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Convert XML import/export form data file into FDF format. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


