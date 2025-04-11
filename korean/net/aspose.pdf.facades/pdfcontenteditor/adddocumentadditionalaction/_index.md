---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 문서 이벤트에 대한 추가 작업을 추가합니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction 메서드

문서 이벤트에 대한 추가 작업을 추가합니다.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| eventType | 문자열 | 문서 이벤트 유형. |
| code | 문자열 | JavaScript 코드. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)