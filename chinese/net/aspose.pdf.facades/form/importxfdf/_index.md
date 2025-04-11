---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。导入xfdfxml文件中的字段内容并将其放入新的pdf中
type: docs
weight: 300
url: /zh/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf 方法

导入xfdf(xml)文件中的字段内容并将其放入新的pdf中。

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputXfdfStream | Stream | 输入的xfdf(xml)流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)