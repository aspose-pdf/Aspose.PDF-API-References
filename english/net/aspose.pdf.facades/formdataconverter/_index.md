---
title: "FormDataConverter Class"
linktitle: "FormDataConverter"
articleTitle: "FormDataConverter"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.FormDataConverter class. Represents a class to convert data from one format to another format. It can convert the data in fdf/xml/pdf/xfdf..."
type: docs
weight: 210
url: "/net/aspose.pdf.facades/formdataconverter/"
keywords: "FormDataConverter, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FormDataConverter class

Represents a class to convert data from one format to another format.
 It can convert the data in fdf/xml/pdf/xfdf to the OLEDB/OdbcDB.
 It also can convert the data in the OLEDB/OdbcDB to the data in fdf/xml/xfdf.
 It can convert the fdf to the xml with "hard-named" tag.

```csharp
public sealed class FormDataConverter
```

## Constructors

| Name | Description |
| --- | --- |
| [FormDataConverter](./formdataconverter/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ClearTableBeforeExport](./cleartablebeforeexport/) { get; set; } | ExportFromData will clear table before data export. |
| [CreateMissingField](./createmissingfield/) { get; set; } | ConvertToDataTable will create required field if it does not exists in Table. |
| [CreateMissingTable](./createmissingtable/) { get; set; } | ImportIntoDatabase will create table if it does not exists. |
| [ReplaceExistingTable](./replaceexistingtable/) { get; set; } | ImportIntoDatabase will drop existing table and create new table if this property set to true. |
| [Table](./table/) { get; set; } | Gets or sets the middle data container, one DataTable. |

## Methods

| Name | Description |
| --- | --- |
| [ConverToStreams](./convertostreams/)(*Stream[], DataType*) | This method is obsolete. Please use ConvertToStreams() instead. |
| [ConvertFdfToXml](./convertfdftoxml/)(*Stream, Stream*) | Convert FDF file into XML. |
| [ConvertToDataTable](./converttodatatable/)(*Stream[], DataType*) | Convert files of strems into table. |
| [ConvertToStreams](./converttostreams/)(*Stream[], DataType*) | Convert data in table into streams. |
| [ConvertXmlToFdf](./convertxmltofdf/)(*Stream, Stream*) | Convert XML import/export form data file into FDF format. |
| [ExportFromDataBase](./exportfromdatabase/)(*string, DataType*) | Exports data from database into table. |
| [ImportIntoDataBase](./importintodatabase/)(*string, DataType*) | Imports data from table into database. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

