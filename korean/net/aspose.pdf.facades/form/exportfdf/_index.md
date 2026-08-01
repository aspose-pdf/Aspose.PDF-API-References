---
title: "Form.ExportFdf"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. pdf의 필드 내용을 fdf 스트림으로 내보냅니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf method

pdf 필드의 내용을 fdf 스트림으로 내보냅니다.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFdfStream | Stream | 출력 fdf 스트림. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


