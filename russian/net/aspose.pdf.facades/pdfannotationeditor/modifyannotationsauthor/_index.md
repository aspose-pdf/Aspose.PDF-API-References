---
title: "PdfAnnotationEditor.ModifyAnnotationsAuthor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfAnnotationEditor. Изменяет автора аннотаций в указанном диапазоне страниц"
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor method

Изменяет автора аннотаций в указанном диапазоне страниц.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | Int32 | Номер начальной страницы. |
| end | Int32 | Номер конечной страницы. |
| srcAuthor | String | Автор, который должен быть изменён. |
| desAuthor | String | Новый автор. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### См. также

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


