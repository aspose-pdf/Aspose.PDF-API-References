---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。将 pdf 字段的内容导出到 xml 流中。按钮字段的值将不会被导出
type: docs
weight: 90
url: /zh/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf 方法

将 pdf 字段的内容导出到 xml 流中。按钮字段的值将不会被导出。

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputXfdfStream | Stream | 输出的 xml 流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)