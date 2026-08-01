---
title: "Form.ImportFdf"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. fdf 파일에서 필드 내용을 가져와 새 pdf에 삽입합니다."
type: docs
weight: 280
url: /ko/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

fdf 파일에서 필드 내용을 가져와 새 pdf에 삽입합니다.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFdfStream | Stream | 입력 fdf 스트림. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


