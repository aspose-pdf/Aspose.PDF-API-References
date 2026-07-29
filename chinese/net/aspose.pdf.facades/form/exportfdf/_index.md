---
title: "Form.ExportFdf"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。将 pdf 中字段的内容导出到 fdf 流。"
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf method

将 PDF 字段的内容导出到 fdf 流中。

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

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


