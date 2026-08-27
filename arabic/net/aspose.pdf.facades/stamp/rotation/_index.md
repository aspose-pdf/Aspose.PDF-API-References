---
title: "Stamp.Rotation"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Stamp. تحصل أو تعيين دوران الختم بالدرجات."
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation property

يحصل أو يعيّن دوران الطابع بالدرجات.

```csharp
public float Rotation { get; set; }
```

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


