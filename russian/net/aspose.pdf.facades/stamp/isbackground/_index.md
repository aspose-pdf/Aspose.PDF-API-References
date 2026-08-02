---
title: "Stamp.IsBackground"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Stamp. Получает или задает статус фона. Если true, штамп будет размещён как фон spamped страницы. По умолчанию установлено false"
type: docs
weight: 30
url: /ru/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

Получает или задает статус фона. Если true, штамп будет размещён как фон обработанной страницы. По умолчанию установлено false.

```csharp
public bool IsBackground { get; set; }
```

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### См. также

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


