---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor 속성. 확대/축소 계수를 가져오거나 설정합니다. 값 1.0은 100에 해당합니다. 기본값은 1.0입니다. 다음 예제는 문서 페이지의 확대/축소를 변경하는 방법을 보여줍니다.
type: docs
weight: 110
url: /ko/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## PdfPageEditor.Zoom 속성

확대/축소 계수를 가져오거나 설정합니다. 값 1.0은 100%에 해당합니다. 기본값은 1.0입니다. 다음 예제는 문서 페이지의 확대/축소를 변경하는 방법을 보여줍니다.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### 참조

* 클래스 [PdfPageEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)