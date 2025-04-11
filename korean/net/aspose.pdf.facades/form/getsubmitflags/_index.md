---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 제출 버튼의 제출 플래그를 반환합니다.
type: docs
weight: 270
url: /ko/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags 메서드

제출 버튼의 제출 플래그를 반환합니다.

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 자격이 있는 필드 이름입니다. |

### 반환 값

버튼의 제출 플래그입니다.

## 예제

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### 참조

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)