---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Stamp property. Gets or sets array with numbers of pages which will be affected by stamp. If Pages  null all pages of the document are affected
type: docs
weight: 60
url: /net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

Gets or sets array with numbers of pages which will be affected by stamp. If Pages = null all pages of the document are affected.

```csharp
public int[] Pages { get; set; }
```

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


