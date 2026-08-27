---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfAnnotationEditor 메서드. 지정된 페이지 범위에서 지정된 유형의 주석을 수정합니다. 다음 주석 속성인 Modified, Title, Contents, Color, Subject 및 Open을 수정하는 것을 지원합니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

지정된 페이지 범위에서 지정된 유형의 주석을 수정합니다. 다음 주석 속성을 수정할 수 있습니다: Modified, Title, Contents, Color, Subject 및 Open.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| start | Int32 | 시작 페이지 번호입니다. |
| end | Int32 | 끝 페이지 번호입니다. |
| annotation | Annotation | 주석 객체에는 새로운 속성이 포함됩니다. |

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

### 또 보기

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


