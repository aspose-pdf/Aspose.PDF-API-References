---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Импортирует указанные аннотации в документ из массива других PDF-документов
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Импортирует указанные аннотации в документ из массива других PDF-документов.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFile | String[] | Массив путей к PDF-документам, содержащим исходные аннотации. |
| annotType | AnnotationType[] | Массив типов аннотаций, которые необходимо импортировать. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### См. также

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Импортирует аннотации в документ из массива других PDF-документов.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFile | String[] | Массив путей к PDF-документам, содержащим исходные аннотации. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### См. также

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Импортирует указанные аннотации в документ из массива потоков других PDF-документов.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFileStream | Stream[] | Массив потоков PDF-документов, содержащих исходные аннотации. |
| annotType | AnnotationType[] | Типы аннотаций, которые необходимо импортировать. |

## Примеры

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

### См. также

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Импортирует аннотации в документ из массива потоков других PDF-документов.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotFileStream | Stream[] | Массив потоков PDF-документов, содержащих исходные аннотации. |

## Примеры

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

### См. также

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)