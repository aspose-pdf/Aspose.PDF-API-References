---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormDataConverter. تحويل ملفات التدفقات إلى جدول
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## طريقة FormDataConverter.ConvertToDataTable

تحويل ملفات التدفقات إلى جدول.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceStreams | Stream[] | مصفوفة من التدفقات المصدرية بالتنسيق المحدد. |
| sourceType | DataType | تنسيق البيانات في التدفقات. القيم الصالحة هي: PDF، FDF، XFDF، XML. |

## أمثلة

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

### انظر أيضًا

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)