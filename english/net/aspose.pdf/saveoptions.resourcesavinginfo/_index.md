---
title: "SaveOptions.ResourceSavingInfo Class"
linktitle: "SaveOptions.ResourceSavingInfo"
articleTitle: "SaveOptions.ResourceSavingInfo"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.SaveOptions.ResourceSavingInfo class. This class represents set of data that related to external resource file's saving that occures during conver..."
type: docs
weight: 2790
url: "/net/aspose.pdf/saveoptions.resourcesavinginfo/"
keywords: "SaveOptions.ResourceSavingInfo, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SaveOptions.ResourceSavingInfo class

This class represents set of data 
 that related to external resource file's saving that 
 occures during conversion of PDF to some other format (f.e. HTML)

```csharp
public class ResourceSavingInfo
```

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](./resourcetype/) { get; } | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](./contentstream/) | Set by converter. Represents binary content of saved file. |
| [CustomProcessingCancelled](./customprocessingcancelled/) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file). |
| [SupposedFileName](./supposedfilename/) | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

