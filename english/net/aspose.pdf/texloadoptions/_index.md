---
title: "TeXLoadOptions Class"
linktitle: "TeXLoadOptions"
articleTitle: "TeXLoadOptions"
second_title: "Aspose.PDF for .NET"
description: "Represents options for loading/importing TeX file into PDF document."
type: docs
weight: 2990
url: "/net/aspose.pdf/texloadoptions/"
keywords: "TeXLoadOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TeXLoadOptions class

Represents options for loading/importing TeX file into PDF document.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TeXLoadOptions](./texloadoptions/#constructor) | Initializes a new instance of the TeXLoadOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [DateTime](./datetime/) { get; set; } | Gets/sets a certain value for date/time primitives like year, month, day and time. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. *(Inherited from LoadOptions)* |
| [InputDirectory](./inputdirectory/) { get; set; } | Gets/sets TeX input directory. |
| [JobName](./jobname/) { get; set; } | Gets/set the name of the job. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../../aspose.pdf/loadoptions/) describes. *(Inherited from LoadOptions)* |
| [NoLigatures](./noligatures/) { get; set; } | Gets/sets a flag that cancels ligatures in all fonts. |
| [OutputDirectory](./outputdirectory/) { get; set; } | Gets/sets TeX output directory. |
| [RasterizeFormulas](./rasterizeformulas/) { get; set; } | Gets/sets a flag that allows to rasterize math formulas. |
| [Repeat](./repeat/) { get; set; } | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case,. |
| [RequiredInputDirectory](./requiredinputdirectory/) { get; set; } | Gets/sets TeX requires input directory. |
| [ShowTerminalOutput](./showterminaloutput/) { get; set; } | Gets/sets the flag indicating whether to show terminal output on the console. |
| [SubsetFonts](./subsetfonts/) { get; set; } | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. *(Inherited from LoadOptions)* |

## Methods

| Name | Description |
| --- | --- |
| [GetLoadResult](./getloadresult/) | Gets result for TeX load and compiling - did everything go smoothly or were there any comments/errors. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

