---
title: Aspose::Pdf::TeXLoadOptions class
linktitle: TeXLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TeXLoadOptions class. Represents options for loading/importing TeX file into PDF document in C++.'
type: docs
weight: 18100
url: /cpp/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class


Represents options for loading/importing TeX file into PDF document.

```cpp
class TeXLoadOptions : public Aspose::Pdf::LoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_DateTime](./get_datetime/)() | Gets/sets a certain value for date/time primitives like year, month, day and time. |
| [get_InputDirectory](./get_inputdirectory/)() | Gets/sets TeX input directory. |
| [get_JobName](./get_jobname/)() const | Gets/set the name of the job. |
| [get_NoLigatures](./get_noligatures/)() | Gets/sets a flag that cancels ligatures in all fonts. |
| [get_OutputDirectory](./get_outputdirectory/)() | Gets/sets TeX output directory. |
| [get_RasterizeFormulas](./get_rasterizeformulas/)() | Gets/sets a flag that allows to rasterize math formulas. |
| [get_Repeat](./get_repeat/)() | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data. |
| [get_RequiredInputDirectory](./get_requiredinputdirectory/)() | Gets/sets TeX requires input directory. Required input is the files that are somehow included into the main .tex file, e.g., packages for which there's no built-in support. |
| [get_ShowTerminalOutput](./get_showterminaloutput/)() const | Gets/sets the flag indicating whether to show terminal output on the console. |
| [get_SubsetFonts](./get_subsetfonts/)() | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [GetLoadResult](./getloadresult/)() | Gets result for TeX load and compiling - did everything go smoothly or were there any comments/errors. |
| [set_DateTime](./set_datetime/)(System::DateTime) | Gets/sets a certain value for date/time primitives like year, month, day and time. |
| [set_InputDirectory](./set_inputdirectory/)(System::SharedPtr\<ITeXInputDirectory\>) | Gets/sets TeX input directory. |
| [set_JobName](./set_jobname/)(System::String) | Gets/set the name of the job. |
| [set_NoLigatures](./set_noligatures/)(bool) | Gets/sets a flag that cancels ligatures in all fonts. |
| [set_OutputDirectory](./set_outputdirectory/)(System::SharedPtr\<ITeXOutputDirectory\>) | Gets/sets TeX output directory. |
| [set_RasterizeFormulas](./set_rasterizeformulas/)(bool) | Gets/sets a flag that allows to rasterize math formulas. |
| [set_Repeat](./set_repeat/)(bool) | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data. |
| [set_RequiredInputDirectory](./set_requiredinputdirectory/)(System::SharedPtr\<ITeXInputDirectory\>) | Gets/sets TeX requires input directory. Required input is the files that are somehow included into the main .tex file, e.g., packages for which there's no built-in support. |
| [set_ShowTerminalOutput](./set_showterminaloutput/)(bool) | Gets/sets the flag indicating whether to show terminal output on the console. |
| [set_SubsetFonts](./set_subsetfonts/)(bool) | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [TeXLoadOptions](./texloadoptions/)() | Creates default load options for converting TeX file into PDF document. |
## See Also

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
