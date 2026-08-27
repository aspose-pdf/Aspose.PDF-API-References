---
title: "PdfFileStamp.AddStamp"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfFileStamp. Добавляет штамп в файл"
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp method

Добавляет штамп в файл.

```csharp
public void AddStamp(Stamp stamp)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| штамп | Штамп | Объект штампа, который. |

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

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


