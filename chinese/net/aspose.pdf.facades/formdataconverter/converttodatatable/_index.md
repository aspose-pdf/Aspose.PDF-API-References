---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 方法。将流文件转换为表格
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## FormDataConverter.ConvertToDataTable 方法

将流文件转换为表格。

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceStreams | Stream[] | 指定格式的源流数组。 |
| sourceType | DataType | 流中数据的格式。有效值为：PDF, FDF, XFDF, XML。 |

## 示例

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

### 另请参阅

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)