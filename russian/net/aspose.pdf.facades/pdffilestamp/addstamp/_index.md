---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileStamp. Добавляет штамп в файл
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## Метод PdfFileStamp.AddStamp

Добавляет штамп в файл.

```csharp
public void AddStamp(Stamp stamp)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stamp | Stamp | Объект штампа. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### См. также

* класс [Stamp](../../stamp/)
* класс [PdfFileStamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)