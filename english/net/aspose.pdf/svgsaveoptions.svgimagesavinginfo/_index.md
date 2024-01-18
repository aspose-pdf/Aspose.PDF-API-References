---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo class. This class represents set of data that related to external resource image files saving during PDF to HTML conversion
type: docs
weight: 7680
url: /net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

This class represents set of data that related to external resource image file's saving during PDF to HTML conversion.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Set by converter. Represents binary content of saved file. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | represent type os saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file |

### See Also

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


