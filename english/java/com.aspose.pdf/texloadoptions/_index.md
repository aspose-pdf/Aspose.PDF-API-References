---
title: TeXLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing TeX file into PDF document.
type: docs
weight: 358
url: /java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public class TeXLoadOptions extends LoadOptions
```

Represents options for loading/importing TeX file into PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [TeXLoadOptions()](#TeXLoadOptions--) | Creates default load options for converting TeX file into PDF document. |
## Methods

| Method | Description |
| --- | --- |
| [getJobName()](#getJobName--) | Gets/set the name of the job. |
| [setJobName(String value)](#setJobName-java.lang.String-) | Gets/set the name of the job. |
| [getInputDirectory()](#getInputDirectory--) | Gets/sets TeX input directory. |
| [setInputDirectory(ITeXInputDirectory value)](#setInputDirectory-com.aspose.tex.ITeXInputDirectory-) | Gets/sets TeX input directory. |
| [getOutputDirectory()](#getOutputDirectory--) | Gets/sets TeX output directory. |
| [setOutputDirectory(ITeXOutputDirectory value)](#setOutputDirectory-com.aspose.tex.ITeXOutputDirectory-) | Gets/sets TeX output directory. |
| [getRepeat()](#getRepeat--) | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). |
| [setRepeat(boolean value)](#setRepeat-boolean-) | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). |
| [getSubsetFonts()](#getSubsetFonts--) | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [setSubsetFonts(boolean value)](#setSubsetFonts-boolean-) | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [getShowTerminalOutput()](#getShowTerminalOutput--) | Gets/sets the flag indicating whether to show terminal output on the console. |
| [setShowTerminalOutput(boolean value)](#setShowTerminalOutput-boolean-) | Gets/sets the flag indicating whether to show terminal output on the console. |
| [getDateTime()](#getDateTime--) | Gets/sets a certain value for date/time primitives like \\year, \\month, \\day and \\time. |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | Gets/sets a certain value for date/time primitives like \\year, \\month, \\day and \\time. |
| [getNoLigatures()](#getNoLigatures--) | Gets/sets a flag that cancels ligatures in all fonts. |
| [setNoLigatures(boolean value)](#setNoLigatures-boolean-) | Gets/sets a flag that cancels ligatures in all fonts. |
| [getRasterizeFormulas()](#getRasterizeFormulas--) | Gets/sets a flag that allows to rasterize math formulas. |
| [setRasterizeFormulas(boolean value)](#setRasterizeFormulas-boolean-) | Gets/sets a flag that allows to rasterize math formulas. |
### TeXLoadOptions() {#TeXLoadOptions--}
```
public TeXLoadOptions()
```


Creates default load options for converting TeX file into PDF document.

### getJobName() {#getJobName--}
```
public final String getJobName()
```


Gets/set the name of the job.

**Returns:**
java.lang.String - String value
### setJobName(String value) {#setJobName-java.lang.String-}
```
public final void setJobName(String value)
```


Gets/set the name of the job.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getInputDirectory() {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```


Gets/sets TeX input directory.

**Returns:**
com.aspose.tex.ITeXInputDirectory - ITeXInputDirectory instance
### setInputDirectory(ITeXInputDirectory value) {#setInputDirectory-com.aspose.tex.ITeXInputDirectory-}
```
public final void setInputDirectory(ITeXInputDirectory value)
```


Gets/sets TeX input directory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.tex.ITeXInputDirectory | ITeXInputDirectory instance |

### getOutputDirectory() {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```


Gets/sets TeX output directory.

**Returns:**
com.aspose.tex.ITeXOutputDirectory - ITeXOutputDirectory instance
### setOutputDirectory(ITeXOutputDirectory value) {#setOutputDirectory-com.aspose.tex.ITeXOutputDirectory-}
```
public final void setOutputDirectory(ITeXOutputDirectory value)
```


Gets/sets TeX output directory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.tex.ITeXOutputDirectory | ITeXOutputDirectory instance |

### getRepeat() {#getRepeat--}
```
public final boolean getRepeat()
```


Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data.

**Returns:**
boolean - boolean value
### setRepeat(boolean value) {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```


Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getSubsetFonts() {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```


Gets/sets the flag indicating whether to subset fonts in output file or not.

**Returns:**
boolean - boolean value
### setSubsetFonts(boolean value) {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```


Gets/sets the flag indicating whether to subset fonts in output file or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getShowTerminalOutput() {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```


Gets/sets the flag indicating whether to show terminal output on the console.

**Returns:**
boolean - boolean value
### setShowTerminalOutput(boolean value) {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```


Gets/sets the flag indicating whether to show terminal output on the console.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


Gets/sets a certain value for date/time primitives like \\year, \\month, \\day and \\time.

**Returns:**
[Date](../../java.util/date) - Date instance
### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


Gets/sets a certain value for date/time primitives like \\year, \\month, \\day and \\time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date instance |

### getNoLigatures() {#getNoLigatures--}
```
public final boolean getNoLigatures()
```


Gets/sets a flag that cancels ligatures in all fonts.

**Returns:**
boolean - boolean value
### setNoLigatures(boolean value) {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```


Gets/sets a flag that cancels ligatures in all fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getRasterizeFormulas() {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```


Gets/sets a flag that allows to rasterize math formulas.

**Returns:**
boolean - boolean value
### setRasterizeFormulas(boolean value) {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```


Gets/sets a flag that allows to rasterize math formulas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

