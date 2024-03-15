---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase property. Gets or sets a value indicating whether additional means are necessary to preserve text alignment during the PDF/A conversion process
type: docs
weight: 10
url: /net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText property

Gets or sets a value indicating whether additional means are necessary to preserve text alignment during the PDF/A conversion process.

```csharp
public bool AlignText { get; set; }
```

### Property Value

`true` if the text alignment gets changed and additional actions are necessary to restore it; otherwise, `false`.

## Remarks

When set to `true`, the conversion process will attempt to restore the original text segment bounds. For the most of the documents there is no need to change this property from the default `false` value, as the text alignment doesn't change during the default conversion process.

### See Also

* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


