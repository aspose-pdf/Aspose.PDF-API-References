---
title: "PdfAnnotationEditor.ExtractAnnotations"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfAnnotationEditor. Получает список аннотаций указанных типов."
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
| start | Int32 | Начальная страница, с которой аннотации будут выбраны. |
| end | Int32 | Конечная страница, до которой аннотации будут выбраны. |
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

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Получает список аннотаций указанных типов.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | Int32 | Начальная страница, с которой аннотации будут выбраны. |
| end | Int32 | Конечная страница, до которой аннотации будут выбраны. |
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

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


