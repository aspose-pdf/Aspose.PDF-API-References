---
title: LatexLoadOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents options for loading/importing TeX file into PDF document.
type: docs
weight: 820
url: /python-net/aspose.pdf/latexloadoptions/
---

## LatexLoadOptions class

Represents options for loading/importing TeX file into PDF document.

The LatexLoadOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|LatexLoadOptions()|Initializes a new instance of the LatexLoadOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.|
|load_format|Represents file format which [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) describes.|
|job_name|Gets/set the name of the job.|
|input_directory|Gets/sets TeX input directory.|
|output_directory|Gets/sets TeX output directory.|
|repeat|Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case,<br/>            for example, there are references in input TeX file(s). In general, this behavior is useful when<br/>            the engine collects some data along the typesetting process and stores it in an auxilliary file,<br/>            all at the first run. And at the second run, the engine somehow uses that data.|
|subset_fonts|Gets/sets the flag indicating whether to subset fonts in output file or not.|
|show_terminal_output|Gets/sets the flag indicating whether to show terminal output on the console.|
|date_time|Gets/sets a certain value for date/time primitives like \year, \month, \day and \time.|
|no_ligatures|Gets/sets a flag that cancels ligatures in all fonts.|
|rasterize_formulas|Gets/sets a flag that allows to rasterize math formulas.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

