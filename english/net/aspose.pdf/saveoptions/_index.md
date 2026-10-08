---
title: "SaveOptions Class"
linktitle: "SaveOptions"
articleTitle: "SaveOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.SaveOptions class. SaveOptions type hold level of abstraction on individual save options"
type: docs
weight: 2720
url: "/net/aspose.pdf/saveoptions/"
keywords: "SaveOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## SaveOptions class

SaveOptions type hold level of abstraction on individual save options

```csharp
public abstract class SaveOptions
```

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

## Other Members

| Name | Description |
| --- | --- |
| class [BorderInfo](../../aspose.pdf/saveoptions.borderinfo) | Instance of this class represents information about border That can be drown on some result document. |
| class [BorderPartStyle](../../aspose.pdf/saveoptions.borderpartstyle) | Represents information of one part of border(top, bottom, left side or right side) |
| enum [HtmlBorderLineType](../../aspose.pdf/saveoptions.htmlborderlinetype) | Represents line types that can be used in result document for drawing borders or another lines |
| class [MarginInfo](../../aspose.pdf/saveoptions.margininfo) | Instance of this class represents information about page margin That can be drown on some result document. |
| class [MarginPartStyle](../../aspose.pdf/saveoptions.marginpartstyle) | Represents information of one part of margin(top, botom, left side or right side) |
| enum [NodeLevelResourceType](../../aspose.pdf/saveoptions.nodelevelresourcetype) | enumerates possible types of saved external resources |
| class [ResourceSavingInfo](../../aspose.pdf/saveoptions.resourcesavinginfo) | This class represents set of data that related to external resource file's saving that occures during conversion of PDF to some other format (f.e. HTML) |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

