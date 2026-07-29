---
title: "Form.ExportJson"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。将文档中所有字段的内容导出为 JSON 流。按钮字段值不予导出。"
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

将文档中所有字段的内容导出到 JSON 流中。按钮字段的值不会被导出。

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputJsonStream | Stream | 将写入文档字段数据的输出 JSON 流。 |
| indented | Boolean | 可选。指定 JSON 输出是否应缩进以提高可读性。默认值为 true。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


