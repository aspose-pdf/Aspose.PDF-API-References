---
title: "PdfContentEditor.RemoveDocumentOpenAction"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 문서에서 열기 동작을 제거합니다. 이 작업은 시작 시 명시적인 GoTo 동작을 사용하는 여러 문서를 연결할 때 유용합니다."
type: docs
weight: 430
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

문서에서 열기 동작을 제거합니다. 이 작업은 시작 시 명시적인 'GoTo' 동작을 사용하는 여러 문서를 연결할 때 유용합니다.

```csharp
public void RemoveDocumentOpenAction()
```

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


