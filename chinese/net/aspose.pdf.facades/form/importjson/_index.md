---
title: "Form.ImportJson"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。从 JSON 流导入所有字段数据到文档字段中，按完整名称匹配字段"
type: docs
weight: 290
url: /zh/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson method

从 JSON 流导入所有字段数据到文档字段中，按完整名称匹配字段。

```csharp
public void ImportJson(Stream inputJsonStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputJsonStream | Stream | 包含要导入到文档字段的字段数据的输入 JSON 流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


