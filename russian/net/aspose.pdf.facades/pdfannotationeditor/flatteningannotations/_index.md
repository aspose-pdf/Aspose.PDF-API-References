---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Уплощает все аннотации в документе
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Уплощает все аннотации в документе.

```csharp
public void FlatteningAnnotations()
```

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### См. также

* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Уплощает все аннотации в документе.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Указывает режимы уплощения. |

### См. также

* класс [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Уплощает аннотации указанных типов.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | Int32 | Начальная страница. |
| end | Int32 | Конечная страница. |
| annotType | AnnotationType[] | Типы аннотаций, которые должны быть уплощены. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### См. также

* перечисление [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)