---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Извлекает коллекцию экземпляров Link, содержащихся в PDF-документе
type: docs
weight: 370
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## Метод PdfContentEditor.ExtractLink

Извлекает коллекцию экземпляров Link, содержащихся в PDF-документе.

```csharp
public IList<Annotation> ExtractLink()
```

### Возвращаемое значение

Коллекция объектов Link

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // work with Link instance
}
```

### См. также

* класс [Annotation](../../../aspose.pdf.annotations/annotation/)
* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)