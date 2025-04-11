---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. xml 파일의 필드 내용을 가져와 새 pdf에 넣습니다.
type: docs
weight: 310
url: /ko/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

xml 파일의 필드 내용을 가져와 새 pdf에 넣습니다.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | Stream | 가져오기 위해 XML이 읽혀지는 스트림입니다. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

xml 파일의 필드 내용을 가져와 새 pdf에 넣습니다.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | Stream | 입력 xml 스트림입니다. |
| IgnoreFormTemplateChanges | Boolean | 이 매개변수가 true이면 XFA 양식 템플릿의 모든 변경 사항이 저장되지 않습니다. |

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)