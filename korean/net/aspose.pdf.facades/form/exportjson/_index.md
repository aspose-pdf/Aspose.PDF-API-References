---
title: "Form.ExportJson"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 문서의 모든 필드 내용을 JSON 스트림으로 내보냅니다. 버튼 필드 값은 내보내지 않습니다."
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

문서의 모든 필드 내용을 JSON 스트림으로 내보냅니다. 버튼 필드 값은 내보내지 않습니다.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputJsonStream | Stream | 문서 필드 데이터가 기록될 출력 JSON 스트림입니다. |
| indented | Boolean | 옵션. JSON 출력이 가독성을 위해 들여쓰기될지 여부를 지정합니다. 기본값은 true입니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


