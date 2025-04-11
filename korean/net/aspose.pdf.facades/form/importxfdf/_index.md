---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. xfdfxml 파일의 필드 내용을 가져와 새로운 pdf에 넣습니다.
type: docs
weight: 300
url: /ko/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf 메서드

xfdf(xml) 파일의 필드 내용을 가져와 새로운 pdf에 넣습니다.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputXfdfStream | Stream | 입력 xfdf(xml) 스트림입니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)