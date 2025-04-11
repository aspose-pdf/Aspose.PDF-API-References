---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。将 pdf 字段的内容导出到 xml 流中。按钮字段的值将不会被导出
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml 方法

将 pdf 字段的内容导出到 xml 流中。按钮字段的值将不会被导出。

```csharp
public void ExportXml(Stream outputXmlStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputXmlStream | Stream | 输出 Xml 流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### 另请参见

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)