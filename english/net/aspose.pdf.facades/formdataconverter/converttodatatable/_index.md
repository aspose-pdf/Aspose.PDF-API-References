---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter method. Convert files of strems into table
type: docs
weight: 80
url: /net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## FormDataConverter.ConvertToDataTable method

Convert files of strems into table.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreams | Stream[] | Array of source streams in specified format. |
| sourceType | DataType | Format of data in streams. Valid values are: PDF, FDF, XFDF, XML. |

## Examples

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
FormDataConverter fc = new FormDataConverter();
Stream stream = new FileStream("PdfWithAcroForm.pdf", FileMode.Open);
fc.Table = table;
fc.ConvertToDataTable(new Stream[] { stream }, DataType.PDF);
stream.Close();
```

### See Also

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


