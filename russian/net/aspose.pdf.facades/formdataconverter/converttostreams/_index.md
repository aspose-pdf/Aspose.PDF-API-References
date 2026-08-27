---
title: "FormDataConverter.ConvertToStreams"
second_title: "Справочник API Aspose.PDF для .NET"
description: "FormDataConverter метод. Преобразовать данные из таблицы в потоки"
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## FormDataConverter.ConvertToStreams method

Преобразовать данные в таблице в потоки.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | Stream[] | Потоки, в которых будут храниться данные. |
| destType | DataType | Тип сохраняемых данных. Допустимые значения: XML, FDF, XFDF. |

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


