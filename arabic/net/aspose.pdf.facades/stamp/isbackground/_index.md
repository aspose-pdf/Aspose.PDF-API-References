---
title: "Stamp.IsBackground"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Stamp. يحصل أو يحدد حالة الخلفية. إذا كان true سيتم وضع الختم كخلفية للصفحة المختومة. بشكل افتراضي يتم تعيينه إلى false"
type: docs
weight: 30
url: /ar/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

يحصل أو يعيّن حالة الخلفية. إذا كانت true سيتم وضع الطابع كخلفية للصفحة المختومة. بشكل افتراضي يتم تعيينها إلى false.

```csharp
public bool IsBackground { get; set; }
```

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


