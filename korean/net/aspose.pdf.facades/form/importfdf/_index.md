---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. fdf 파일의 필드 내용을 가져와 새로운 pdf에 넣습니다.
type: docs
weight: 280
url: /ko/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf 메서드

fdf 파일의 필드 내용을 가져와 새로운 pdf에 넣습니다.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFdfStream | Stream | 입력 fdf 스트림입니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)