---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Свойство Stamp. Получает или задает угол поворота штампа в градусах
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/stamp/rotation/
---
## Свойство Stamp.Rotation

Получает или задает угол поворота штампа в градусах.

```csharp
public float Rotation { get; set; }
```

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### См. также

* класс [Stamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)