---
title: PdfAnnotationEditor.DeleteAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 메서드. 문서의 모든 주석을 삭제합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

문서의 모든 주석을 삭제합니다.

```csharp
public void DeleteAnnotations()
```

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### 참조

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

문서에서 지정된 유형의 모든 주석을 삭제합니다.

```csharp
public void DeleteAnnotations(string annotType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| annotType | 문자열 | 삭제될 주석의 유형입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### 참조

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)