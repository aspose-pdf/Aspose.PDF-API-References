---
title: "Form.ExportXml"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。将 PDF 字段的内容导出到 XML 流中。按钮字段的值将不会被导出"
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml method

将 PDF 字段的内容导出到 xml 流中。按钮字段的值将不会被导出。

```csharp
public void ExportXml(Stream outputXmlStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputXmlStream | Stream | 输出 XML 流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


