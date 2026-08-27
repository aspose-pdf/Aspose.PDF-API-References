---
title: "Form.ImportFdf"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。将 fdf 文件中字段的内容导入并放入新的 pdf。"
type: docs
weight: 280
url: /zh/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

从 fdf 文件导入字段内容并将其放入新的 pdf。

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

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


