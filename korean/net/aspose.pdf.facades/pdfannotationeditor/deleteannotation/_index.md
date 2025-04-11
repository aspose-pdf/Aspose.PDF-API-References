---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 메서드. 지정된 주석 이름으로 주석을 삭제합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation 메서드

지정된 주석 이름으로 주석을 삭제합니다.

```csharp
public void DeleteAnnotation(string annotName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| annotName | 문자열 | 주석 이름 |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfAnnotationEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)