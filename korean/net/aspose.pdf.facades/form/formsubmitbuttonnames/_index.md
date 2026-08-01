---
title: "Form.FormSubmitButtonNames"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 속성. 모든 폼 제출 버튼 이름을 가져옵니다"
type: docs
weight: 40
url: /ko/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames property

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

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


