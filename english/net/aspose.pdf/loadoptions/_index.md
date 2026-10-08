---
title: "LoadOptions Class"
linktitle: "LoadOptions"
articleTitle: "LoadOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LoadOptions class. LoadOptions type holds level of abstraction on individual load options"
type: docs
weight: 1750
url: "/net/aspose.pdf/loadoptions/"
keywords: "LoadOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## LoadOptions class

LoadOptions type holds level of abstraction on individual load options

```csharp
public abstract class LoadOptions
```

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which `LoadOptions` describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

## Other Members

| Name | Description |
| --- | --- |
| enum [MarginsAreaUsageModes](../../aspose.pdf/loadoptions.marginsareausagemodes) | Represents mode of usage of margins area during conversion (like HTML, EPUB etc), defines treatement of instructions of imported format related to usage of margins. |
| enum [PageSizeAdjustmentModes](../../aspose.pdf/loadoptions.pagesizeadjustmentmodes) | ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specifies horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document). |
| class [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult) | Result of custom loading of resource |
| delegate [ResourceLoadingStrategy](../../aspose.pdf/loadoptions.resourceloadingstrategy) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere. For example during usage of Aspose.Pdf in cloud direct access to referenced files impossible, and some custome code put into special method should be used. This delegate defines signature of such custom method. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

