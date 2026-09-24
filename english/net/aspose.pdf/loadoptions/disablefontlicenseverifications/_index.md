---
title: "LoadOptions.DisableFontLicenseVerifications"
linktitle: "DisableFontLicenseVerifications"
articleTitle: "DisableFontLicenseVerifications"
second_title: "Aspose.PDF for .NET API Reference"
description: "LoadOptions property. Gets or sets flag to disable any license restrictions for all fonts while loading the file. When , allows to execute operations with fo..."
type: docs
weight: 40
url: "/net/aspose.pdf/loadoptions/disablefontlicenseverifications/"
product_version: "26.9.0"
---
## LoadOptions.DisableFontLicenseVerifications property

Gets or sets flag to disable any license restrictions for all fonts while loading the file.
 When , allows to execute operations with font that are prohibited by a license
 of this font, for example allows to embed a font into a PDF document even if license rules
 disable embedding for this font. 
 By default .

Be careful when using this flag. When it is set it means that person who sets this flag, 
 takes all responsibility of possible license/law violations on himself. 
 So he takes it on it's own risk.
 It's strongly recommended to use this flag only when you are fully confident that you are not breaking 
 the copyright law.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### See Also

* class [LoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

