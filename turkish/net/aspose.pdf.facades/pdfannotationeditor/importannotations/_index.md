---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. Belirtilen notları başka PDF belgelerinin dizisinden belgeye aktarır.
type: docs
weight: 90
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Belirtilen notları başka PDF belgelerinin dizisinden belgeye aktarır.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| annotFile | String[] | Kaynak notları içeren PDF belgelerinin yol dizisi. |
| annotType | AnnotationType[] | Aktarılacak not türleri dizisi. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Notları başka PDF belgelerinin dizisinden belgeye aktarır.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| annotFile | String[] | Kaynak notları içeren PDF belgelerinin yol dizisi. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Belirtilen notları başka PDF belge akışlarının dizisinden belgeye aktarır.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| annotFileStream | Stream[] | Kaynak notları içeren PDF belgelerinin akış dizisi. |
| annotType | AnnotationType[] | Aktarılacak not türleri. |

## Örnekler

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

### Ayrıca Bakınız

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Notları başka PDF belge akışlarının dizisinden belgeye aktarır.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| annotFileStream | Stream[] | Kaynak notları içeren PDF belgelerinin akış dizisi. |

## Örnekler

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

### Ayrıca Bakınız

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)