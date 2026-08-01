---
title: "Form.ImportXfdf"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. xfdfxml 파일에서 필드 내용을 가져와 새 pdf에 삽입합니다."
type: docs
weight: 300
url: /ko/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

xfdf(xml) 파일에서 필드 내용을 가져와 새 pdf에 삽입합니다.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputXfdfStream | Stream | 입력 xfdf(xml) 스트림. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


