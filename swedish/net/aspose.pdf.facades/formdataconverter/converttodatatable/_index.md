---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter-metod. Konvertera filer av strömmar till tabell
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## FormDataConverter.ConvertToDataTable metod

Konvertera filer av strömmar till tabell.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStreams | Stream[] | Array av källströmmar i angivet format. |
| sourceType | DataType | Format av data i strömmar. Giltiga värden är: PDF, FDF, XFDF, XML. |

## Exempel

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

### Se Även

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)