---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Изменяет аннотации указанного типа на указанном диапазоне страниц. Поддерживает изменение следующих свойств аннотации Изменено, Заголовок, Содержимое, Цвет, Тема и Открыто
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## Метод PdfAnnotationEditor.ModifyAnnotations

Изменяет аннотации указанного типа на указанном диапазоне страниц. Поддерживает изменение следующих свойств аннотации: Изменено, Заголовок, Содержимое, Цвет, Тема и Открыто.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | Int32 | Номер начальной страницы. |
| end | Int32 | Номер конечной страницы. |
| annotation | Annotation | Объект аннотации содержит новые свойства. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### См. также

* класс [Annotation](../../../aspose.pdf.annotations/annotation/)
* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)