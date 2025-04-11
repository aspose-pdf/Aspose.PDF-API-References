---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。导入 fdf 文件中的字段内容并将其放入新的 pdf 中
type: docs
weight: 280
url: /zh/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf 方法

导入 fdf 文件中的字段内容并将其放入新的 pdf 中。

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFdfStream | Stream | 输入的 fdf 流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### 另请参阅

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)