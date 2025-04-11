---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. pdf의 필드 내용을 xml 스트림으로 내보냅니다. 버튼 필드의 값은 내보내지지 않습니다.
type: docs
weight: 100
url: /ko/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml 메서드

pdf의 필드 내용을 xml 스트림으로 내보냅니다. 버튼 필드의 값은 내보내지지 않습니다.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputXmlStream | Stream | 출력 Xml 스트림. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)