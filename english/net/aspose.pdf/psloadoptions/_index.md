---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsLoadOptions class. Represents options for loading/importing of .mhtfile into pdf document
type: docs
weight: 9880
url: /net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

Represents options for loading/importing of .mht-file into pdf document.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertFontsToTTF](../../aspose.pdf/psloadoptions/convertfontstottf/) { get; set; } | Specifies whether to save non-TrueType fonts to TTF. It significantly decreases the volume of the resulting document in PS to PDF conversion and increases the speed of conversion of PS files with a large quantity of text in non-TrueType fonts to any output format. However, there is small vertical shift of text when converting PostSctipt file to image. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Gets or sets fonts folders paths. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


