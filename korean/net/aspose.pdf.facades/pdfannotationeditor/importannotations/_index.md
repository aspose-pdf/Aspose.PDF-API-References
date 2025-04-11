---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor 메서드. 다른 PDF 문서의 배열에서 문서로 지정된 주석을 가져옵니다.
type: docs
weight: 90
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

다른 PDF 문서의 배열에서 문서로 지정된 주석을 가져옵니다.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | String[] | 소스 주석이 포함된 PDF 문서의 경로 배열입니다. |
| annotType | AnnotationType[] | 가져올 주석 유형의 배열입니다. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### See Also

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

다른 PDF 문서의 배열에서 문서로 주석을 가져옵니다.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | String[] | 소스 주석이 포함된 PDF 문서의 경로 배열입니다. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

다른 PDF 문서 스트림의 배열에서 문서로 지정된 주석을 가져옵니다.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFileStream | Stream[] | 소스 주석이 포함된 PDF 문서의 스트림 배열입니다. |
| annotType | AnnotationType[] | 가져올 주석 유형입니다. |

## Examples

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

### See Also

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

다른 PDF 문서 스트림의 배열에서 문서로 주석을 가져옵니다.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFileStream | Stream[] | 소스 주석이 포함된 PDF 문서의 스트림 배열입니다. |

## Examples

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

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)