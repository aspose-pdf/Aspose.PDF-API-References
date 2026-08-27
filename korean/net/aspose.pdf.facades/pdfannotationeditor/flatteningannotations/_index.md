---
title: "PdfAnnotationEditor.FlatteningAnnotations"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfAnnotationEditor 메서드. 문서의 모든 주석을 평탄화합니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

문서의 모든 주석을 평탄화합니다.

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

### 또 보기

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

문서의 모든 주석을 평탄화합니다.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| flattenSettings | FlattenSettings | 평탄화 모드를 지정합니다. |

### 또 보기

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

지정된 유형의 주석을 평탄화합니다.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| start | Int32 | 시작 페이지. |
| end | Int32 | 그런 다음 페이지를 끝냅니다. |
| annotType | AnnotationType[] | 주석 유형은 평면화되어야 합니다. |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### 또 보기

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


