---
title: Aspose::Pdf::HtmlSaveOptions::HtmlImageSavingInfo class
linktitle: HtmlImageSavingInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::HtmlImageSavingInfo class. This class represents set of data that related to external resource image file''s saving during PDF to HTML conversion in C++.'
type: docs
weight: 8400
url: /cpp/aspose.pdf/htmlsaveoptions/htmlimagesavinginfo/
---
## HtmlImageSavingInfo class


This class represents set of data that related to external resource image file's saving during PDF to HTML conversion.

```cpp
class HtmlImageSavingInfo : public Aspose::Pdf::SaveOptions::ResourceSavingInfo
```

## Methods

| Method | Description |
| --- | --- |
| [HtmlImageSavingInfo](./htmlimagesavinginfo/)() | creates new instance of [SaveOptions.ResourceSavingInfo](../../saveoptions/resourcesavinginfo/) |
## Fields

| Field | Description |
| --- | --- |
| [ContentStream](../../saveoptions/resourcesavinginfo/contentstream/) | Set by converter. Represents binary content of saved file. |
| [CustomProcessingCancelled](../../saveoptions/resourcesavinginfo/customprocessingcancelled/) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file). |
| [HtmlHostPageNumber](./htmlhostpagenumber/) | Tells to custom code to what page of generated set of HTML page-files pertains saved image. If splitting on pages turned off this value always contains '1' since in such case Only one HTML page is generated. |
| [ImageType](./imagetype/) | Represents type of saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done. |
| [ParentType](./parenttype/) | Saved image can pertain to HTML itself or can be extracted. from SVG embedded to HTML. This property can tell to custom code what's that type of parent of processed image. 

 It set by converter and can be used in custom code to decide what should be done with that image (f.e. custom code can decide where to save image or how it must be referenced in parent's content). |
| [PdfHostPageNumber](./pdfhostpagenumber/) | Tells to custom code to what page of original PDF document pertains saved image Since it's possible that will be saved not all pages of original document, this value tells us about host page number in original PDF. If original page number for some reason is inknown, it allways return '1'. |
| [SupposedFileName](../../saveoptions/resourcesavinginfo/supposedfilename/) | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file. |
## See Also

* Class [ResourceSavingInfo](../../saveoptions/resourcesavinginfo/)
* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
