---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo.PdfHostPageNumber"
linktitle: "PdfHostPageNumber"
articleTitle: "PdfHostPageNumber"
second_title: "Aspose.PDF for .NET API Reference"
description: "HtmlPageMarkupSavingInfo field. Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during ..."
type: docs
weight: 30
url: "/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber/"
product_version: "26.9"
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo.PdfHostPageNumber field

Set by converter.
 If SplitToPages property set, then several HTML-files(one HTML file per converted page)
 are created during conversion created .
 This property tells to custom code from what page of original PDF was created saved HTML-markup.
 If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0'
 that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file.

```csharp
public int PdfHostPageNumber;
```

### See Also

* class [HtmlPageMarkupSavingInfo](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

