---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Convertir archivos de flujos en tabla
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## Método FormDataConverter.ConvertToDataTable

Convertir archivos de flujos en tabla.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceStreams | Stream[] | Array de flujos de origen en el formato especificado. |
| sourceType | DataType | Formato de datos en los flujos. Los valores válidos son: PDF, FDF, XFDF, XML. |

## Ejemplos

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

### Ver También

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)