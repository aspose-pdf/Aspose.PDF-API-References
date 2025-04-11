---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 문서의 모든 필드 내용을 JSON 스트림으로 내보냅니다. 버튼 필드 값은 내보내지지 않습니다.
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson 메서드

문서의 모든 필드 내용을 JSON 스트림으로 내보냅니다. 버튼 필드 값은 내보내지지 않습니다.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputJsonStream | Stream | 문서의 필드 데이터가 기록될 출력 JSON 스트림입니다. |
| indented | Boolean | 선택 사항. JSON 출력이 가독성을 높이기 위해 들여쓰기를 해야 하는지 여부를 지정합니다. 기본값은 true입니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)