---
title: FormDataConverter
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a class to convert data from one format to another format.<br/>            It can convert the data in fdf/xml/pdf/xfdf to the OLEDB/OdbcDB.<br/>            It also can convert the data in the OLEDB/OdbcDB to the data in fdf/xml/xfdf.<br/>            It can convert the fdf to the xml with "hard-named" tag.
type: docs
weight: 100
url: /python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Represents a class to convert data from one format to another format.<br/>            It can convert the data in fdf/xml/pdf/xfdf to the OLEDB/OdbcDB.<br/>            It also can convert the data in the OLEDB/OdbcDB to the data in fdf/xml/xfdf.<br/>            It can convert the fdf to the xml with "hard-named" tag.

The FormDataConverter type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FormDataConverter()|Initializes a new instance of the FormDataConverter class|
## Properties
| Name | Description |
| :- | :- |
|create_missing_field|ConvertToDataTable will create required field if it does not exists in Table.|
|replace_existing_table|ImportIntoDatabase will drop existing table and create new table if this property set to true.|
|clear_table_before_export|ExportFromData will clear table before data export.|
|create_missing_table|ImportIntoDatabase will create table if it does not exists.|
## Methods
| Name | Description |
| :- | :- |
|convert_xml_to_fdf(source_xml, dest_fdf)|Convert XML  import/export form data file into FDF format.|
|convert_fdf_to_xml(source_fdf, dest_xml)|Convert FDF file into XML.|
|convert_to_data_table(source_streams, source_type)|Convert files of strems into table.|
|import_into_data_base(connect_string, db_type)|Imports data from table into database.|
|export_from_data_base(connect_string, db_type)|Exports data from database into table.|
|convert_to_streams(dest_stream, dest_type)|Convert data in table into streams.|
|conver_to_streams(dest_stream, dest_type)|This method is obsolete. Please use ConvertToStreams() instead.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

