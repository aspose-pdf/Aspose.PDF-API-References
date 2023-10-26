---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Stamp property. Gets or sets background status. If true stamp will be placed as background of the spamped page. By default is set to false
type: docs
weight: 30
url: /net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

Gets or sets background status. If true stamp will be placed as background of the spamped page. By default is set to false.

```csharp
public bool IsBackground { get; set; }
```

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


