---
title: Class XpsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XpsLoadOptions class. Represents options for loading/importing xps file into pdf document
type: docs
weight: 11920
url: /net/aspose.pdf/xpsloadoptions/
---
## XpsLoadOptions class

Represents options for loading/importing xps file into pdf document.

```csharp
public sealed class XpsLoadOptions : LoadOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XpsLoadOptions](xpsloadoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpsloadoptions/batchsize/) { get; set; } | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

### See Also

* class [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


