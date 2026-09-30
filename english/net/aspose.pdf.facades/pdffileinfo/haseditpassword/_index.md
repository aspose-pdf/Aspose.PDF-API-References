---
title: "PdfFileInfo.HasEditPassword"
linktitle: "HasEditPassword"
articleTitle: "HasEditPassword"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileInfo property. Returns true if password is needed to modify permissions or document security property. Pay attention that this property can be read on..."
type: docs
weight: 410
url: "/net/aspose.pdf.facades/pdffileinfo/haseditpassword/"
product_version: "26.9.0"
---
## PdfFileInfo.HasEditPassword property

Returns true if password is needed to modify permissions or document security property.
 Pay attention that this property can be read only if valid password was provided in [`PdfFileInfo`](../../../aspose.pdf.facades/pdffileinfo/) constructor.
 In case PasswordType is Inaccessible (means that invalid password was provided) reading this property will fail with [`InvalidPasswordException`](../../../aspose.pdf/invalidpasswordexception/).

```csharp
public bool HasEditPassword { get; }
```

### See Also

* class [PdfFileInfo](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

