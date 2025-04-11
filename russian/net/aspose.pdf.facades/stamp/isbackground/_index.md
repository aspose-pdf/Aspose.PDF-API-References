---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Свойство Stamp. Получает или устанавливает статус фона. Если true, штамп будет размещен в качестве фона страницы со штампом. По умолчанию установлено значение false.
type: docs
weight: 30
url: /ru/net/aspose.pdf.facades/stamp/isbackground/
---
## Свойство Stamp.IsBackground

Получает или устанавливает статус фона. Если true, штамп будет размещен в качестве фона страницы со штампом. По умолчанию установлено значение false.

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

* класс [Stamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)