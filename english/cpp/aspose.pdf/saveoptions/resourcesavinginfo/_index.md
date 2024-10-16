---
title: Aspose::Pdf::SaveOptions::ResourceSavingInfo class
linktitle: ResourceSavingInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SaveOptions::ResourceSavingInfo class. This class represents set of data that related to external resource file''s saving that occures during conversion of PDF to some other format (f.e. HTML) in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf/saveoptions/resourcesavinginfo/
---
## ResourceSavingInfo class


This class represents set of data that related to external resource file's saving that occures during conversion of PDF to some other format (f.e. HTML)

```cpp
class ResourceSavingInfo : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_ResourceType](./get_resourcetype/)() const | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file. |
## Fields

| Field | Description |
| --- | --- |
| [ContentStream](./contentstream/) | Set by converter. Represents binary content of saved file. |
| [CustomProcessingCancelled](./customprocessingcancelled/) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file). |
| [SupposedFileName](./supposedfilename/) | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file. |
## See Also

* Class [Object](../../../system/object/)
* Class [SaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
