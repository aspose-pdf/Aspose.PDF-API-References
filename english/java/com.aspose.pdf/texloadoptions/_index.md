---
title: TeXLoadOptions
linktitle: TeXLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing TeX file into PDF document.
type: docs
weight: 4870
url: /java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

Represents options for loading/importing TeX file into PDF document.

## Constructors

| Constructor | Description |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | Creates default load options for converting TeX file into PDF document. |

## Methods

| Method | Description |
| --- | --- |
| [getDateTime](#getDateTime--) | Gets/sets a certain value for date/time primitives like year, month, day and time. |
| [getInputDirectory](#getInputDirectory--) | Gets/sets TeX input directory. |
| [getJobName](#getJobName--) | Gets/set the name of the job. |
| [getLoadResult](#getLoadResult--) | Gets result for TeX load and compiling - did everything go smoothly or were there any comments/errors. |
| [getNoLigatures](#getNoLigatures--) | Gets/sets a flag that cancels ligatures in all fonts. |
| [getOutputDirectory](#getOutputDirectory--) | Gets/sets TeX output directory. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | Gets/sets a flag that allows to rasterize math formulas. |
| [getRepeat](#getRepeat--) | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | Gets/sets TeX requires input directory. Required input is the files that are somehow included into the main .tex file, e.g., packages for which there's no built-in support. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | Gets/sets the flag indicating whether to show terminal output on the console. |
| [getSubsetFonts](#getSubsetFonts--) | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [setDateTime](#setDateTime-java.util.Date-) | Gets/sets a certain value for date/time primitives like year, month, day and time. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Gets/sets TeX input directory. |
| [setJobName](#setJobName-java.lang.String-) | Gets/set the name of the job. |
| [setNoLigatures](#setNoLigatures-boolean-) | Gets/sets a flag that cancels ligatures in all fonts. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | Gets/sets TeX output directory. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | Gets/sets a flag that allows to rasterize math formulas. |
| [setRepeat](#setRepeat-boolean-) | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Gets/sets TeX requires input directory. Required input is the files that are somehow included into the main .tex file, e.g., packages for which there's no built-in support. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | Gets/sets the flag indicating whether to show terminal output on the console. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Gets/sets the flag indicating whether to subset fonts in output file or not. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

Creates default load options for converting TeX file into PDF document.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

Gets/sets a certain value for date/time primitives like year, month, day and time.

**Returns:**
Date instance

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

Gets/sets TeX input directory.

**Returns:**
ITeXInputDirectory instance

### getJobName {#getJobName--}
```
public final String getJobName()
```

Gets/set the name of the job.

**Returns:**
String value

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

Gets result for TeX load and compiling - did everything go smoothly or were there any comments/errors.

**Returns:**
TeXLoadResult element

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

Gets/sets a flag that cancels ligatures in all fonts.

**Returns:**
boolean value

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

Gets/sets TeX output directory.

**Returns:**
ITeXOutputDirectory instance

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

Gets/sets a flag that allows to rasterize math formulas.

**Returns:**
boolean value

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data.

**Returns:**
boolean value

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

Gets/sets TeX requires input directory. Required input is the files that are somehow included into the main .tex file, e.g., packages for which there's no built-in support.

**Returns:**
ITeXInputDirectory instance

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

Gets/sets the flag indicating whether to show terminal output on the console.

**Returns:**
boolean value

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

Gets/sets the flag indicating whether to subset fonts in output file or not.

**Returns:**
boolean value

### setDateTime {#setDateTime-java.util.Date-}
Gets/sets a certain value for date/time primitives like year, month, day and time.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Gets/sets TeX input directory.

### setJobName {#setJobName-java.lang.String-}
Gets/set the name of the job.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

Gets/sets a flag that cancels ligatures in all fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
Gets/sets TeX output directory.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

Gets/sets a flag that allows to rasterize math formulas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Gets/sets TeX requires input directory. Required input is the files that are somehow included into the main .tex file, e.g., packages for which there's no built-in support.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

Gets/sets the flag indicating whether to show terminal output on the console.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Gets/sets the flag indicating whether to subset fonts in output file or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
