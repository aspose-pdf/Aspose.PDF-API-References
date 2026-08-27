---
title: "PdfContentEditor.ExtractLink"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Извлекает коллекцию экземпляров Link, содержащихся в PDF‑документе."
type: docs
weight: 370
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

Извлекает коллекцию экземпляров Link, содержащихся в PDF‑документе.

```csharp
public IList<Annotation> ExtractLink()
```

### Возвращаемое значение

Коллекция объектов Link.

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // работа с экземпляром Link.
}
```

### См. также

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


