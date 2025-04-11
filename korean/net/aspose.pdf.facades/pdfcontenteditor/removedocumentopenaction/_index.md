---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 문서에서 열기 작업을 제거합니다. 이 작업은 시작 시 명시적인 GoTo 작업을 사용하는 여러 문서를 연결할 때 유용합니다.
type: docs
weight: 430
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction 메서드

문서에서 열기 작업을 제거합니다. 이 작업은 시작 시 명시적인 'GoTo' 작업을 사용하는 여러 문서를 연결할 때 유용합니다.

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

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)