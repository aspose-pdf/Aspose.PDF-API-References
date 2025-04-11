---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 메서드. 지정된 유형의 주석 목록을 가져옵니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

지정된 유형의 주석 목록을 가져옵니다.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| start | Int32 | 주석이 선택될 시작 페이지입니다. |
| end | Int32 | 주석이 선택될 종료 페이지입니다. |
| annotTypes | String[] | 필요한 주석 유형의 배열입니다. |

### 반환 값

주석 목록입니다.

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### 참조

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

지정된 유형의 주석 목록을 가져옵니다.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| start | Int32 | 주석이 선택될 시작 페이지입니다. |
| end | Int32 | 주석이 선택될 종료 페이지입니다. |
| annotTypes | AnnotationType[] | 필요한 주석 유형의 배열입니다. |

### 반환 값

주석 목록입니다.

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### 참조

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)