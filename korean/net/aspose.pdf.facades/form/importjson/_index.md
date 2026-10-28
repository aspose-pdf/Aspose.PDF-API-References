---
title: "Form.ImportJson"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. JSON 스트림에서 모든 필드 데이터를 가져와 전체 이름으로 일치하는 문서 필드에 입력합니다."
type: docs
weight: 290
url: /ko/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson method

JSON 스트림에서 모든 필드 데이터를 문서 필드에 가져오며, 전체 이름으로 필드를 매칭합니다.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputJsonStream | Stream | 문서 필드에 가져올 필드 데이터를 포함하는 입력 JSON 스트림입니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


