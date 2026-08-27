---
title: "Field.ExportValueToJson"
second_title: "Aspose.PDF for .NET API 参考"
description: "Field 方法。将指定字段的内容导出为 JSON 流。按钮字段的值不会被导出"
type: docs
weight: 180
url: /zh/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson method

将指定字段的内容导出到 JSON 流中。按钮字段的值不会被导出。

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputJsonStream | Stream | 用于写入字段数据的输出 JSON 流。 |
| indented | Boolean | 可选。指定 JSON 输出是否应缩进以提高可读性。默认值为 true。 |

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### 另请参见

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


