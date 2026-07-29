---
title: "PdfAnnotationEditor.ImportAnnotations"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تستورد التعليقات التوضيحية المحددة إلى المستند من مصفوفة مستندات PDF أخرى"
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

يستورد التعليقات التوضيحية المحددة إلى المستند من مصفوفة من مستندات PDF أخرى.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| annotFile | String[] | مصفوفة مسارات مستندات PDF التي تحتوي على التعليقات التوضيحية المصدر. |
| annotType | AnnotationType[] | مصفوفة أنواع التعليقات التوضيحية التي سيتم استيرادها. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

يستورد التعليقات التوضيحية إلى المستند من مصفوفة من مستندات PDF أخرى.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| annotFile | String[] | مصفوفة مسارات مستندات PDF التي تحتوي على التعليقات التوضيحية المصدر. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

يستورد التعليقات التوضيحية المحددة إلى المستند من مصفوفة من تدفقات مستندات PDF أخرى.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| annotFileStream | Stream[] | مصفوفة تدفقات مستندات PDF التي تحتوي على التعليقات التوضيحية المصدر. |
| annotType | AnnotationType[] | أنواع التعليقات التوضيحية التي سيتم استيرادها. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
stream[0]= File.OpenRead("with_annots1.pdf");
stream[1]= File.OpenRead("with_annots2.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(streams, annotTypes);
editor.Save("example_out.pdf");
stream[0].Close();
stream[1].Close();
```

### انظر أيضًا

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

يستورد التعليقات التوضيحية إلى المستند من مصفوفة من تدفقات مستندات PDF أخرى.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| annotFileStream | Stream[] | مصفوفة تدفقات مستندات PDF التي تحتوي على التعليقات التوضيحية المصدر. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
streams[0]= File.OpenRead("with_annots1.pdf");
streams[1]= File.OpenRead("with_annots2.pdf");
editor.ImportAnnotations(streams);
editor.Save("example_out.pdf");
streams[0].Close();
streams[1].Close();
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


