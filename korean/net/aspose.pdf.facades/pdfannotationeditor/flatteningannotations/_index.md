---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 메서드. 문서의 모든 주석을 평면화합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

문서의 모든 주석을 평면화합니다.

```csharp
public void FlatteningAnnotations()
```

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### 참조

* 클래스 [PdfAnnotationEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

문서의 모든 주석을 평면화합니다.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| flattenSettings | FlattenSettings | 평면화 모드를 지정합니다. |

### 참조

* 클래스 [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* 클래스 [PdfAnnotationEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

지정된 유형의 주석을 평면화합니다.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| start | Int32 | 시작 페이지. |
| end | Int32 | 종료 페이지. |
| annotType | AnnotationType[] | 평면화해야 하는 주석 유형입니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### 참조

* 열거형 [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* 클래스 [PdfAnnotationEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)