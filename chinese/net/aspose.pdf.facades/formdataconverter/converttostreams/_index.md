---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 方法。将表中的数据转换为流
type: docs
weight: 90
url: /zh/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## FormDataConverter.ConvertToStreams 方法

将表中的数据转换为流。

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destStream | Stream[] | 存储数据的流。 |
| destType | DataType | 存储数据的类型。有效值为：XML, FDF, XFDF。 |

## 示例

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

### 另请参阅

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)