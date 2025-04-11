---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。将所有字段数据从 JSON 流导入到与字段全名匹配的文档字段中
type: docs
weight: 290
url: /zh/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson 方法

将所有字段数据从 JSON 流导入到文档字段中，按字段全名匹配字段。

```csharp
public void ImportJson(Stream inputJsonStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputJsonStream | Stream | 包含要导入到文档字段中的字段数据的输入 JSON 流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)