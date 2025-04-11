---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormDataConverter. تحويل البيانات في الجدول إلى تدفقات
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## طريقة FormDataConverter.ConvertToStreams

تحويل البيانات في الجدول إلى تدفقات.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| destStream | Stream[] | التدفقات التي سيتم تخزين البيانات فيها. |
| destType | DataType | نوع البيانات المخزنة. القيم الصالحة هي: XML، FDF، XFDF. |

## أمثلة

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
DataRow newrow = table.NewRow();
newrow["textField"] = "NEW DATA";
newrow["listboxField"] = "Item1";
newrow["comboboxField"] = "Item1";
newrow["checkboxField"] = "true";
newrow["radiobuttonField"] = "true";
table.Rows.Add(newrow);
fc.Table = table;
fc.ConvertToStreams(new Stream[] { stream }, DataType.XML);
```

### انظر أيضًا

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)