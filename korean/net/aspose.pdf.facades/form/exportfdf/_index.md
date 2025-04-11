---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. pdf의 필드 내용을 fdf 스트림으로 내보냅니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf 메서드

pdf의 필드 내용을 fdf 스트림으로 내보냅니다.

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

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)