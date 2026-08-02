---
title: "Stamp.Rotation"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Stamp. Получает или задает вращение штампа в градусах"
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation property

Получает или задает вращение штампа в градусах.

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

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


