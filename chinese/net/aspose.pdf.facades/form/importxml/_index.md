---
title: "Form.ImportXml"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。将 xml 文件中字段的内容导入并放入新的 pdf。"
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

从 xml 文件导入字段内容并将其放入新的 pdf。

```csharp
public void ImportXml(Stream inputXmlStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputXmlStream | Stream | 读取导入用 XML 的流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

从 xml 文件导入字段内容并将其放入新的 pdf。

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputXmlStream | Stream | 输入的 xml 流。 |
| IgnoreFormTemplateChanges | Boolean | 如果此参数为 true，则所有对 XFA 表单模板的更改都不会被保存。 |

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


