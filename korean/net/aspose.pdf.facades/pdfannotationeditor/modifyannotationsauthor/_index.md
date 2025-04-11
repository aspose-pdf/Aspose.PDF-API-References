---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 메서드. 지정된 페이지 범위에서 주석의 저자를 수정합니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor 메서드

지정된 페이지 범위에서 주석의 저자를 수정합니다.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| start | Int32 | 시작 페이지 번호. |
| end | Int32 | 끝 페이지 번호. |
| srcAuthor | String | 수정해야 하는 저자. |
| desAuthor | String | 새로운 저자. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfAnnotationEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)