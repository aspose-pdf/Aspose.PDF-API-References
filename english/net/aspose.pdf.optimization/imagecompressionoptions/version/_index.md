---
title: "ImageCompressionOptions.Version"
linktitle: "Version"
articleTitle: "Version"
second_title: "Aspose.PDF for .NET"
description: "Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applic..."
type: docs
weight: 60
url: "/net/aspose.pdf.optimization/imagecompressionoptions/version/"
product_version: "26.9.0"
---
## ImageCompressionOptions.Version property

Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard".

```csharp
public ImageCompressionVersion Version { get; set; }
```

### Property Value

[ImageCompressionVersion](../../../aspose.pdf.optimization/imagecompressionversion/)

### See Also

* class [ImageCompressionVersion](../../../aspose.pdf.optimization/imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)

