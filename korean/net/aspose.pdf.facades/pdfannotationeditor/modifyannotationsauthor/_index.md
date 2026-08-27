---
title: "PdfAnnotationEditor.ModifyAnnotationsAuthor"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfAnnotationEditor 메서드. 지정된 페이지 범위에서 주석의 작성자를 수정합니다."
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor method

지정된 페이지 범위에서 주석의 작성자를 수정합니다.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| start | Int32 | 시작 페이지 번호입니다. |
| end | Int32 | 끝 페이지 번호입니다. |
| srcAuthor | String | 수정해야 하는 작성자입니다. |
| desAuthor | String | 새 작성자입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


