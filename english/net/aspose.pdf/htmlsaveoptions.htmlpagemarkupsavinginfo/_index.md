---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo class. If SplitToPages property of HtmlSaveOptions then several HTMLfiles one HTML file per converted page are created during conversion of PDF to HTML. This class represents set of data that related to custom saving of one HTMLpages markup during conversion of PDF to HTML
type: docs
weight: 5670
url: /net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

If SplitToPages property of HtmlSaveOptions, then several HTML-files (one HTML file per converted page) are created during conversion of PDF to HTML. This class represents set of data that related to custom saving of one HTML-page's markup during conversion of PDF to HTML

```csharp
public class HtmlPageMarkupSavingInfo
```

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Set by converter. Represents saved HTML as stream |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Should be set in custom code when necessary. This flag must be set to "true" in custom code if for some reasons supplied html-markup should be processed not with custom code but with converter's code itself in standard for converter way. So, setting if this flag in custom code means that custom code did not process referenced file and converter must handle it itself |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Set by converter. If set SplitToPages property, then several HTML-files(one HTML file per converted page) are created during conversion created . This property contains ordinal of saved HTML page's file. The property can be used in logic of custom code to decide how to process or where to save HTML page and If splitting on pages turned off this value always contains '1' since in such case only one big HTML page is generated for whole source document. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during conversion created . This property tells to custom code from what page of original PDF was created saved HTML-markup. If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0' that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


