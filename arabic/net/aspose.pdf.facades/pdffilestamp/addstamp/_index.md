---
title: "PdfFileStamp.AddStamp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileStamp. يضيف ختمًا إلى الملف"
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp method

يضيف طابعًا إلى الملف.

```csharp
public void AddStamp(Stamp stamp)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ختم | ختم | كائن الختم الذي. |

## أمثلة

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

### انظر أيضًا

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


