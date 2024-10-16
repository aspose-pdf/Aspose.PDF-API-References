---
title: Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingInfo class
linktitle: HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingInfo class. If SplitToPages property of HtmlSaveOptions, then several HTML-files (one HTML file per converted page) are created during conversion of PDF to HTML. This class represents set of data that related to custom saving of one HTML-page''s markup during conversion of PDF to HTML in C++.'
type: docs
weight: 8500
url: /cpp/aspose.pdf/htmlsaveoptions/htmlpagemarkupsavinginfo/
---
## HtmlPageMarkupSavingInfo class


If SplitToPages property of [HtmlSaveOptions](../), then several HTML-files (one HTML file per converted page) are created during conversion of PDF to HTML. This class represents set of data that related to custom saving of one HTML-page's markup during conversion of PDF to HTML.

```cpp
class HtmlPageMarkupSavingInfo : public System::Object
```

## Fields

| Field | Description |
| --- | --- |
| [ContentStream](./contentstream/) | Set by converter. Represents saved HTML as stream. |
| [CustomProcessingCancelled](./customprocessingcancelled/) | Should be set in custom code when necessary. This flag must be set to "true" in custom code if for some reasons supplied html-markup should be processed not with custom code but with converter's code itself in standard for converter way. So, setting if this flag in custom code means that custom code did not process referenced file and converter must handle it itself. |
| [HtmlHostPageNumber](./htmlhostpagenumber/) | Set by converter. If set SplitToPages property, then several HTML-files(one HTML file per converted page) are created during conversion created . This property contains ordinal of saved HTML page's file. The property can be used in logic of custom code to decide how to process or where to save HTML page and If splitting on pages turned off this value always contains '1' since in such case only one big HTML page is generated for whole source document. |
| [PdfHostPageNumber](./pdfhostpagenumber/) | Set by converter. If SplitToPages property set, then several HTML-files(one HTML file per converted page) are created during conversion created . This property tells to custom code from what page of original PDF was created saved HTML-markup. If original page number for some reason is inknown or SplitOnPages=false,then this property allways contains '0' that signals that converter cannot supply exact original PDF's page number for supplied HTML-markup file. |
| [SupposedFileName](./supposedfilename/) | Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content. |
## See Also

* Class [Object](../../../system/object/)
* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
