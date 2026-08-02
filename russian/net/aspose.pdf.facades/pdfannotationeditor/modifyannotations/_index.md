---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfAnnotationEditor. Изменяет аннотации указанного типа в заданном диапазоне страниц. Поддерживает изменение следующих свойств аннотации: Modified, Title, Contents, Color, Subject и Open."
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

Изменяет аннотации указанного типа в указанном диапазоне страниц. Поддерживает изменение следующих свойств аннотации: Modified, Title, Contents, Color, Subject и Open.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | Int32 | Номер начальной страницы. |
| end | Int32 | Номер конечной страницы. |
| аннотация | Аннотация | Объект аннотации содержит новые свойства. |

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

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


