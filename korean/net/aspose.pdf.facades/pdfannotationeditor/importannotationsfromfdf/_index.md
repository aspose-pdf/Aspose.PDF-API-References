---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 메서드. FDF 파일에서 모든 주석을 가져옵니다.
type: docs
weight: 100
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf 메서드

FDF 파일에서 모든 주석을 가져옵니다.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fdfFile | 문자열 | 입력 FDF 파일입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfAnnotationEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)