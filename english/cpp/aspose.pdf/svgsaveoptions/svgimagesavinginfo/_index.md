---
title: Aspose::Pdf::SvgSaveOptions::SvgImageSavingInfo class
linktitle: SvgImageSavingInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SvgSaveOptions::SvgImageSavingInfo class. This class represents set of data that related to external resource image file''s saving during PDF to HTML conversion in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf/svgsaveoptions/svgimagesavinginfo/
---
## SvgImageSavingInfo class


This class represents set of data that related to external resource image file's saving during PDF to HTML conversion.

```cpp
class SvgImageSavingInfo : public Aspose::Pdf::SaveOptions::ResourceSavingInfo
```

## Methods

| Method | Description |
| --- | --- |
| [SvgImageSavingInfo](./svgimagesavinginfo/)() | creates new instance of HtmlImageSavingInfo |
## Fields

| Field | Description |
| --- | --- |
| [ContentStream](../../saveoptions/resourcesavinginfo/contentstream/) | Set by converter. Represents binary content of saved file. |
| [CustomProcessingCancelled](../../saveoptions/resourcesavinginfo/customprocessingcancelled/) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file). |
| [ImageType](./imagetype/) | represent type os saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done |
| [SupposedFileName](../../saveoptions/resourcesavinginfo/supposedfilename/) | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file. |
## See Also

* Class [ResourceSavingInfo](../../saveoptions/resourcesavinginfo/)
* Class [SvgSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
