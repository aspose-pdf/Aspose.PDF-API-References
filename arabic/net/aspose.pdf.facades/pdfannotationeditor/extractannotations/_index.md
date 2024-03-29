---
title: ExtractAnnotations
second_title: Aspose.PDF لمرجع .NET API
description: الحصول على قائمة التعليقات التوضيحية للأنواع المحددة.
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

الحصول على قائمة التعليقات التوضيحية للأنواع المحددة.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| start | Int32 | صفحة البداية التي سيتم تحديد التعليقات التوضيحية منها. |
| end | Int32 | صفحة النهاية التي سيتم تحديد التعليقات التوضيحية إليها. |
| annotTypes | String[] | مجموعة أنواع التعليقات التوضيحية المطلوبة. |

### قيمة الإرجاع

قائمة التعليقات التوضيحية.

### أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### أنظر أيضا

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfannotationeditor)
* المجسم [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

الحصول على قائمة التعليقات التوضيحية للأنواع المحددة.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| start | Int32 | صفحة البداية التي سيتم تحديد التعليقات التوضيحية منها. |
| end | Int32 | صفحة النهاية التي سيتم تحديد التعليقات التوضيحية إليها. |
| annotTypes | AnnotationType[] | مجموعة أنواع التعليقات التوضيحية المطلوبة. |

### قيمة الإرجاع

قائمة التعليقات التوضيحية.

### أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### أنظر أيضا

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfannotationeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
