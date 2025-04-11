---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。导入xml文件中的字段内容并将其放入新的pdf中
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

导入xml文件中的字段内容并将其放入新的pdf中。

```csharp
public void ImportXml(Stream inputXmlStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputXmlStream | Stream | 从中读取要导入的XML的流。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### 另请参阅

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

导入xml文件中的字段内容并将其放入新的pdf中。

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputXmlStream | Stream | 输入xml流。 |
| IgnoreFormTemplateChanges | Boolean | 如果此参数为true，则所有XFA表单模板的更改将不会被保存 |

### 另请参阅

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)