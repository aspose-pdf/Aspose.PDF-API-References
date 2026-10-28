---
title: "Form.FieldNames"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 속성. 양식에 있는 필드 이름 목록을 가져옵니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames property

양식에 있는 필드 이름 목록을 가져옵니다.

```csharp
public string[] FieldNames { get; }
```

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


