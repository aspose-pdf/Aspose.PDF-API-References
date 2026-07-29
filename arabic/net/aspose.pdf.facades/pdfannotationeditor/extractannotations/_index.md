---
title: "PdfAnnotationEditor.ExtractAnnotations"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. يحصل على قائمة التعليقات من الأنواع المحددة."
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

يحصل على قائمة التعليقات التوضيحية للأنواع المحددة.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| start | Int32 | صفحة البداية التي سيتم اختيار التعليقات منها. |
| end | Int32 | صفحة النهاية التي سيتم اختيار التعليقات إليها. |
| annotTypes | String[] | المصفوفة التي تحتوي على أنواع التعليقات المطلوبة. |

### قيمة الإرجاع

قائمة التعليقات التوضيحية.

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### انظر أيضًا

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

يحصل على قائمة التعليقات التوضيحية للأنواع المحددة.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| start | Int32 | صفحة البداية التي سيتم اختيار التعليقات منها. |
| end | Int32 | صفحة النهاية التي سيتم اختيار التعليقات إليها. |
| annotTypes | AnnotationType[] | المصفوفة التي تحتوي على أنواع التعليقات المطلوبة. |

### قيمة الإرجاع

قائمة التعليقات التوضيحية.

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### انظر أيضًا

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


