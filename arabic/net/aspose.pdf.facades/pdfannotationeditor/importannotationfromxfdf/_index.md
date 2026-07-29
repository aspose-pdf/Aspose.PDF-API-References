---
title: "PdfAnnotationEditor.ImportAnnotationFromXfdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تستورد التعليقات التوضيحية المحددة من ملف XFDF"
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

يستورد التعليقات التوضيحية المحددة من ملف XFDF.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xfdfFile | String | ملف XFDF الإدخال. |
| annotType | AnnotationType[] | مصفوفة التعليقات التوضيحية التي سيتم استيرادها. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

يستورد التعليقات التوضيحية المحددة من تدفق بيانات XFDF.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xfdfStream | Stream | تيار بيانات XFDF الإدخال. |
| annotType | AnnotationType[] | مصفوفة أنواع التعليقات التوضيحية التي سيتم استيرادها. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


