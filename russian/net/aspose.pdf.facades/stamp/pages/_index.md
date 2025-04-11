---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Свойство Stamp. Получает или задает массив с номерами страниц, которые будут затронуты штампом. Если Pages = null, все страницы документа затронуты
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/stamp/pages/
---
## Свойство Stamp.Pages

Получает или задает массив с номерами страниц, которые будут затронуты штампом. Если Pages = null, все страницы документа затронуты.

```csharp
public int[] Pages { get; set; }
```

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### См. также

* класс [Stamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)