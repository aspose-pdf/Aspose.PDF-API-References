---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfAnnotationEditor. تحصل على قائمة بالتعليقات التوضيحية من الأنواع المحددة
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

تحصل على قائمة بالتعليقات التوضيحية من الأنواع المحددة.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| start | Int32 | الصفحة التي ستبدأ منها اختيار التعليقات التوضيحية. |
| end | Int32 | الصفحة التي ستنتهي عندها اختيار التعليقات التوضيحية. |
| annotTypes | String[] | مصفوفة بأنواع التعليقات التوضيحية المطلوبة. |

### Return Value

قائمة التعليقات التوضيحية.

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### See Also

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

تحصل على قائمة بالتعليقات التوضيحية من الأنواع المحددة.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| start | Int32 | الصفحة التي ستبدأ منها اختيار التعليقات التوضيحية. |
| end | Int32 | الصفحة التي ستنتهي عندها اختيار التعليقات التوضيحية. |
| annotTypes | AnnotationType[] | مصفوفة بأنواع التعليقات التوضيحية المطلوبة. |

### Return Value

قائمة التعليقات التوضيحية.

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### See Also

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)