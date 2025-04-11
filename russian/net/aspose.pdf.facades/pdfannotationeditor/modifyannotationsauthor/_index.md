---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Изменяет автора аннотаций на указанном диапазоне страниц
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## Метод PdfAnnotationEditor.ModifyAnnotationsAuthor

Изменяет автора аннотаций на указанном диапазоне страниц.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | Int32 | Номер начальной страницы. |
| end | Int32 | Номер конечной страницы. |
| srcAuthor | String | Автор, который должен быть изменен. |
| desAuthor | String | Новый автор. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)