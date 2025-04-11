---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Получает список аннотаций указанных типов
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Получает список аннотаций указанных типов.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | Int32 | Начальная страница, с которой будут выбраны аннотации. |
| end | Int32 | Конечная страница, до которой будут выбраны аннотации. |
| annotTypes | String[] | Массив необходимых типов аннотаций. |

### Возвращаемое значение

Список аннотаций.

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### См. также

* класс [Annotation](../../../aspose.pdf.annotations/annotation/)
* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Получает список аннотаций указанных типов.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | Int32 | Начальная страница, с которой будут выбраны аннотации. |
| end | Int32 | Конечная страница, до которой будут выбраны аннотации. |
| annotTypes | AnnotationType[] | Массив необходимых типов аннотаций. |

### Возвращаемое значение

Список аннотаций.

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### См. также

* класс [Annotation](../../../aspose.pdf.annotations/annotation/)
* перечисление [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)