---
title: "Form.ImportXfdf"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。从 xfdfxml 文件导入字段内容并将其放入新的 pdf 中。"
type: docs
weight: 300
url: /zh/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

从 xfdf(xml) 文件导入字段内容并将其放入新的 pdf。

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputXfdfStream | Stream | 输入 xfdf(xml) 流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


