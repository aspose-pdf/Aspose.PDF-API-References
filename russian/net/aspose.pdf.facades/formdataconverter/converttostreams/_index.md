---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: Метод FormDataConverter. Преобразовать данные в таблице в потоки
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## Метод FormDataConverter.ConvertToStreams

Преобразовать данные в таблице в потоки.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | Stream[] | Потоки, в которых будут храниться данные. |
| destType | DataType | Тип хранимых данных. Допустимые значения: XML, FDF, XFDF. |

## Примеры

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

### См. также

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)