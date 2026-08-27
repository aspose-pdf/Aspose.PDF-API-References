---
title: "PdfAnnotationEditor.FlatteningAnnotations"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تقوم بتسطيح جميع التعليقات التوضيحية في المستند"
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

يُسطّح جميع التعليقات التوضيحية في المستند.

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

يُسطّح جميع التعليقات التوضيحية في المستند.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| flattenSettings | FlattenSettings | يحدد أوضاع التسطيح. |

### انظر أيضًا

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

يُسطّح التعليقات التوضيحية للأنواع المحددة.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| start | Int32 | صفحة البداية. |
| end | Int32 | ثم صفحة النهاية. |
| annotType | AnnotationType[] | يجب تسطيح أنواع التعليقات التوضيحية. |

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


