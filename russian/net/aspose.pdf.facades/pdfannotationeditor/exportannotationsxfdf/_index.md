---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Экспортирует содержимое указанных типов аннотаций в XFDF
type: docs
weight: 50
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Экспортирует содержимое указанных типов аннотаций в XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlOutputStream | Stream | Выходной поток XFDF. |
| start | Int32 | Начальная страница, с которой будут экспортированы аннотации документа. |
| end | Int32 | Конечная страница, на которую будут экспортированы аннотации документа. |
| annotTypes | String[] | Массив типов аннотаций, которые необходимо экспортировать. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### См. также

* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Экспортирует содержимое указанных типов аннотаций в XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlOutputStream | Stream | Выходной поток XFDF. |
| start | Int32 | Начальная страница, с которой будут экспортированы аннотации документа. |
| end | Int32 | Конечная страница, на которую будут экспортированы аннотации документа. |
| annotTypes | AnnotationType[] | Массив типов аннотаций, которые необходимо экспортировать. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### См. также

* перечисление [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)