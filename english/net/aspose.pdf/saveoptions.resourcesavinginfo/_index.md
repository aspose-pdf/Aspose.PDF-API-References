---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SaveOptionsResourceSavingInfo class. This class represents set of data that related to external resource files saving that occures during conversion of PDF to some other format f.e. HTML
type: docs
weight: 7740
url: /net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo class

This class represents set of data that related to external resource file's saving that occures during conversion of PDF to some other format (f.e. HTML)

```csharp
public class ResourceSavingInfo
```

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Set by converter. Represents binary content of saved file. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


