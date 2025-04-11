---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Form 속성. 모든 양식 제출 버튼 이름을 가져옵니다.
type: docs
weight: 40
url: /ko/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames 속성

모든 양식 제출 버튼 이름을 가져옵니다.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)