---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfAnnotationEditor. تقوم بتسوية جميع التعليقات التوضيحية في المستند
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

تقوم بتسوية جميع التعليقات التوضيحية في المستند.

```csharp
public void FlatteningAnnotations()
```

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

تقوم بتسوية جميع التعليقات التوضيحية في المستند.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| flattenSettings | FlattenSettings | يحدد أوضاع التسوية. |

### انظر أيضًا

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

تقوم بتسوية التعليقات التوضيحية من الأنواع المحددة.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| start | Int32 | الصفحة الابتدائية. |
| end | Int32 | الصفحة النهائية. |
| annotType | AnnotationType[] | يجب تسوية أنواع التعليقات التوضيحية. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)