---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 문서 이벤트에 대한 추가 작업을 추가합니다"
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

문서 이벤트에 대한 추가 작업을 추가합니다.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| eventType | String | 문서 이벤트 유형. |
| code | String | JavaScript 코드. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


