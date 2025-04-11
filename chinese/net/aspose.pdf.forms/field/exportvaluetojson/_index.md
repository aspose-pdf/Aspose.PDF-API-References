---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: 字段方法。将指定字段的内容导出到 JSON 流中。按钮字段值不被导出
type: docs
weight: 180
url: /zh/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson 方法

将指定字段的内容导出到 JSON 流中。按钮字段值不被导出。

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputJsonStream | Stream | 输出 JSON 流，字段数据将写入此流。 |
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

* 类 [Field](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)