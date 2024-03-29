---
title: ImportAnnotations
second_title: Aspose.PDF لمرجع .NET API
description: يستورد التعليقات التوضيحية المحددة في المستند من مصفوفة مستندات PDF أخرى.
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

يستورد التعليقات التوضيحية المحددة في المستند من مصفوفة مستندات PDF أخرى.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| annotFile | String[] | مصفوفة مسارات مستندات PDF التي تحتوي على تعليقات توضيحية المصدر. |
| annotType | AnnotationType[] | مصفوفة أنواع التعليقات التوضيحية التي سيتم استيرادها. |

### أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### أنظر أيضا

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfannotationeditor)
* المجسم [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

يستورد التعليقات التوضيحية في مستند من مصفوفة مستندات PDF أخرى.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| annotFile | String[] | مصفوفة مسارات مستندات PDF التي تحتوي على تعليقات توضيحية المصدر. |

### أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### أنظر أيضا

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfannotationeditor)
* المجسم [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

يستورد التعليقات التوضيحية المحددة في المستند من مصفوفة تدفق مستند PDF آخر.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| annotFileStream | Stream[] | مصفوفة تدفقات مستندات PDF التي تحتوي على التعليقات التوضيحية للمصدر. |
| annotType | AnnotationType[] | أنواع التعليقات التوضيحية التي سيتم استيرادها. |

### أمثلة

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

### أنظر أيضا

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfannotationeditor)
* المجسم [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

يقوم باستيراد التعليقات التوضيحية في المستند من مصفوفة تدفق مستند PDF آخر.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| annotFileStream | Stream[] | مصفوفة تدفقات مستندات PDF التي تحتوي على التعليقات التوضيحية للمصدر. |

### أمثلة

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

### أنظر أيضا

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfannotationeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
