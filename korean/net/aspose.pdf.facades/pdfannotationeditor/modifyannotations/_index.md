---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 메서드. 지정된 페이지 범위에서 지정된 유형의 주석을 수정합니다. 수정된 제목, 내용, 색상, 주제 및 열기와 같은 다음 주석 속성을 수정하는 것을 지원합니다.
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations 메서드

지정된 페이지 범위에서 지정된 유형의 주석을 수정합니다. 수정된, 제목, 내용, 색상, 주제 및 열기와 같은 다음 주석 속성을 수정하는 것을 지원합니다.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| start | Int32 | 시작 페이지 번호입니다. |
| end | Int32 | 끝 페이지 번호입니다. |
| annotation | Annotation | 새로운 속성을 포함하는 주석 객체입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [Annotation](../../../aspose.pdf.annotations/annotation/)
* 클래스 [PdfAnnotationEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)