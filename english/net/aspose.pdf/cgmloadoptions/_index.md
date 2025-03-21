---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CgmLoadOptions class. Contains options for loading/importing CGM file into pdf document
type: docs
weight: 3010
url: /net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions class

Contains options for loading/importing CGM file into pdf document.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Creates default load options for converting CGM file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Creates load options with defined !:pageSize. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Gets or sets output page size for import. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


