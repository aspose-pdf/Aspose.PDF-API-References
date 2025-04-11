---
title: PdfPageEditor.GetPages
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 메서드. 총 페이지 수를 반환합니다.
type: docs
weight: 150
url: /ko/net/aspose.pdf.facades/pdfpageeditor/getpages/
---
## PdfPageEditor.GetPages 메서드

총 페이지 수를 반환합니다.

```csharp
public int GetPages()
```

### 반환 값

페이지 수.

## 예제

다음 예제는 GetPages() 메서드 사용을 보여줍니다:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
Console.WriteLine("Document has: " + editor.GetPages());
```

### 참조

* 클래스 [PdfPageEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)