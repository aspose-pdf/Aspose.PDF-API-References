---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。将 pdf 字段的内容导出到 fdf 流
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf 方法

将 pdf 字段的内容导出到 fdf 流。

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFdfStream | Stream | 输出的 fdf 流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)