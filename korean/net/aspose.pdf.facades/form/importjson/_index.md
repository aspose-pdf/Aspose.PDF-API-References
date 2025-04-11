---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. JSON 스트림에서 모든 필드 데이터를 가져와서 전체 이름으로 필드와 일치하는 문서 필드에 가져옵니다.
type: docs
weight: 290
url: /ko/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson 메서드

JSON 스트림에서 모든 필드 데이터를 문서 필드로 가져오며, 전체 이름으로 필드와 일치시킵니다.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputJsonStream | Stream | 문서 필드로 가져올 필드 데이터가 포함된 입력 JSON 스트림입니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)