---
title: Class LoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptions class. LoadOptions type holds level of abstraction on individual load options
type: docs
weight: 6240
url: /net/aspose.pdf/loadoptions/
---
## LoadOptions class

LoadOptions type holds level of abstraction on individual load options

```csharp
public abstract class LoadOptions
```

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which `LoadOptions` describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


