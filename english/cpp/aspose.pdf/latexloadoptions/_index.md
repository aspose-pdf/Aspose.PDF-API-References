---
title: Aspose::Pdf::LatexLoadOptions class
linktitle: LatexLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LatexLoadOptions class. Represents options for loading/importing TeX file into PDF document in C++.'
type: docs
weight: 8000
url: /cpp/aspose.pdf/latexloadoptions/
---
## LatexLoadOptions class


Represents options for loading/importing TeX file into PDF document.

```cpp
class LatexLoadOptions : public Aspose::Pdf::TeXLoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_DateTime](../texloadoptions/get_datetime/)() | Gets/sets a certain value for date/time primitives like year, month, day and time. |
| [get_DisableFontLicenseVerifications](../loadoptions/get_disablefontlicenseverifications/)() const | Gets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [get_InputDirectory](../texloadoptions/get_inputdirectory/)() | Gets/sets TeX input directory. |
| [get_JobName](../texloadoptions/get_jobname/)() const | Gets/set the name of the job. |
| [get_LoadFormat](../loadoptions/get_loadformat/)() const | Represents file format which [LoadOptions](../loadoptions/) describes. |
| [get_NoLigatures](../texloadoptions/get_noligatures/)() | Gets/sets a flag that cancels ligatures in all fonts. |
| [get_OutputDirectory](../texloadoptions/get_outputdirectory/)() | Gets/sets TeX output directory. |
| [get_RasterizeFormulas](../texloadoptions/get_rasterizeformulas/)() | Gets/sets a flag that allows to rasterize math formulas. |
| [get_Repeat](../texloadoptions/get_repeat/)() | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data. |
| [get_RequiredInputDirectory](../texloadoptions/get_requiredinputdirectory/)() | Gets/sets TeX requires input directory. Required input is the files that are somehow included into the main .tex file, e.g., packages for which there's no built-in support. |
| [get_ShowTerminalOutput](../texloadoptions/get_showterminaloutput/)() const | Gets/sets the flag indicating whether to show terminal output on the console. |
| [get_SubsetFonts](../texloadoptions/get_subsetfonts/)() | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [get_WarningHandler](../loadoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [GetLoadResult](../texloadoptions/getloadresult/)() | Gets result for TeX load and compiling - did everything go smoothly or were there any comments/errors. |
| [LoadOptions](../loadoptions/loadoptions/)() |  |
| [set_DateTime](../texloadoptions/set_datetime/)(System::DateTime) | Gets/sets a certain value for date/time primitives like year, month, day and time. |
| [set_DisableFontLicenseVerifications](../loadoptions/set_disablefontlicenseverifications/)(bool) | Sets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [set_InputDirectory](../texloadoptions/set_inputdirectory/)(System::SharedPtr\<ITeXInputDirectory\>) | Gets/sets TeX input directory. |
| [set_JobName](../texloadoptions/set_jobname/)(System::String) | Gets/set the name of the job. |
| [set_NoLigatures](../texloadoptions/set_noligatures/)(bool) | Gets/sets a flag that cancels ligatures in all fonts. |
| [set_OutputDirectory](../texloadoptions/set_outputdirectory/)(System::SharedPtr\<ITeXOutputDirectory\>) | Gets/sets TeX output directory. |
| [set_RasterizeFormulas](../texloadoptions/set_rasterizeformulas/)(bool) | Gets/sets a flag that allows to rasterize math formulas. |
| [set_Repeat](../texloadoptions/set_repeat/)(bool) | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data. |
| [set_RequiredInputDirectory](../texloadoptions/set_requiredinputdirectory/)(System::SharedPtr\<ITeXInputDirectory\>) | Gets/sets TeX requires input directory. Required input is the files that are somehow included into the main .tex file, e.g., packages for which there's no built-in support. |
| [set_ShowTerminalOutput](../texloadoptions/set_showterminaloutput/)(bool) | Gets/sets the flag indicating whether to show terminal output on the console. |
| [set_SubsetFonts](../texloadoptions/set_subsetfonts/)(bool) | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [set_WarningHandler](../loadoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [TeXLoadOptions](../texloadoptions/texloadoptions/)() | Creates default load options for converting TeX file into PDF document. |

## Deprecated
Use TeXLoadOptions instead. 

## See Also

* Class [TeXLoadOptions](../texloadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
