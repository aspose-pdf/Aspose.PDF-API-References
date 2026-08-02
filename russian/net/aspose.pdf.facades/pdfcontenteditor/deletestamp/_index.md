---
title: "PdfContentEditor.DeleteStamp"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfContentEditor метод. Удаляет несколько штампов на указанной Page по индексам штампов"
type: docs
weight: 330
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp method

Удаляет несколько штампов на указанной странице по индексам штампов.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы, на которой будет удалён штамп. |
| index | Int32[] | Индексы штампов. |

## Примеры

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


