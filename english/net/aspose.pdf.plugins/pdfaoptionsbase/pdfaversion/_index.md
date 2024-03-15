---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase property. Gets or sets the version of the PDF/A standard to be used for validation or conversion
type: docs
weight: 110
url: /net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## PdfAOptionsBase.PdfAVersion property

Gets or sets the version of the PDF/A standard to be used for validation or conversion.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### Property Value

The version of the PDF/A standard. This can be one of the values from the [`PdfAStandardVersion`](../../pdfastandardversion/) enumeration.

## Remarks

The PDF/A standard version is used to determine the compliance level for PDF/A validation and conversion. If the version is set to Auto, the system will automatically determine the appropriate PDF/A standard version for validation based on the document metadata. For the PDF/A conversion process the Auto defaults to the PDF/A-1b standard version.

### See Also

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


