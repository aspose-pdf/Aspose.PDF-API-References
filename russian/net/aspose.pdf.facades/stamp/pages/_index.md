---
title: "Stamp.Pages"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Stamp. Получает или задает массив с номерами страниц, которые будут затронуты штампом. Если Pages null, затрагиваются все страницы документа."
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

Получает или задает массив номеров страниц, которые будут затронуты штампом. Если Pages = null, затронуты все страницы документа.

```csharp
public int[] Pages { get; set; }
```

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//Разместить штамп только на 1‑й, 4‑й и 6‑й странице.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### См. также

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


