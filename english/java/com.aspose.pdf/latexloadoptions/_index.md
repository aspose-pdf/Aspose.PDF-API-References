---
title: LatexLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing TeX file into PDF document.
type: docs
weight: 186
url: /java/com.aspose.pdf/latexloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions), [com.aspose.pdf.TeXLoadOptions](../../com.aspose.pdf/texloadoptions)
```
public final class LatexLoadOptions extends TeXLoadOptions
```

Represents options for loading/importing TeX file into PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [LatexLoadOptions()](#LatexLoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDateTime()](#getDateTime--) | Gets/sets a certain value for date/time primitives like \\year, \\month, \\day and \\time. |
| [getInputDirectory()](#getInputDirectory--) | Gets/sets TeX input directory. |
| [getJobName()](#getJobName--) | Gets/set the name of the job. |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
| [getNoLigatures()](#getNoLigatures--) | Gets/sets a flag that cancels ligatures in all fonts. |
| [getOutputDirectory()](#getOutputDirectory--) | Gets/sets TeX output directory. |
| [getRasterizeFormulas()](#getRasterizeFormulas--) | Gets/sets a flag that allows to rasterize math formulas. |
| [getRepeat()](#getRepeat--) | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). |
| [getShowTerminalOutput()](#getShowTerminalOutput--) | Gets/sets the flag indicating whether to show terminal output on the console. |
| [getSubsetFonts()](#getSubsetFonts--) | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | Gets/sets a certain value for date/time primitives like \\year, \\month, \\day and \\time. |
| [setInputDirectory(ITeXInputDirectory value)](#setInputDirectory-com.aspose.tex.ITeXInputDirectory-) | Gets/sets TeX input directory. |
| [setJobName(String value)](#setJobName-java.lang.String-) | Gets/set the name of the job. |
| [setNoLigatures(boolean value)](#setNoLigatures-boolean-) | Gets/sets a flag that cancels ligatures in all fonts. |
| [setOutputDirectory(ITeXOutputDirectory value)](#setOutputDirectory-com.aspose.tex.ITeXOutputDirectory-) | Gets/sets TeX output directory. |
| [setRasterizeFormulas(boolean value)](#setRasterizeFormulas-boolean-) | Gets/sets a flag that allows to rasterize math formulas. |
| [setRepeat(boolean value)](#setRepeat-boolean-) | Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). |
| [setShowTerminalOutput(boolean value)](#setShowTerminalOutput-boolean-) | Gets/sets the flag indicating whether to show terminal output on the console. |
| [setSubsetFonts(boolean value)](#setSubsetFonts-boolean-) | Gets/sets the flag indicating whether to subset fonts in output file or not. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LatexLoadOptions() {#LatexLoadOptions--}
```
public LatexLoadOptions()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


Gets/sets a certain value for date/time primitives like \\year, \\month, \\day and \\time.

**Returns:**
[Date](../../java.util/date) - Date instance
### getInputDirectory() {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```


Gets/sets TeX input directory.

**Returns:**
com.aspose.tex.ITeXInputDirectory - ITeXInputDirectory instance
### getJobName() {#getJobName--}
```
public final String getJobName()
```


Gets/set the name of the job.

**Returns:**
java.lang.String - String value
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Represents file format which  LoadOptions  describes.

**Returns:**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat element
### getNoLigatures() {#getNoLigatures--}
```
public final boolean getNoLigatures()
```


Gets/sets a flag that cancels ligatures in all fonts.

**Returns:**
boolean - boolean value
### getOutputDirectory() {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```


Gets/sets TeX output directory.

**Returns:**
com.aspose.tex.ITeXOutputDirectory - ITeXOutputDirectory instance
### getRasterizeFormulas() {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```


Gets/sets a flag that allows to rasterize math formulas.

**Returns:**
boolean - boolean value
### getRepeat() {#getRepeat--}
```
public final boolean getRepeat()
```


Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data.

**Returns:**
boolean - boolean value
### getShowTerminalOutput() {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```


Gets/sets the flag indicating whether to show terminal output on the console.

**Returns:**
boolean - boolean value
### getSubsetFonts() {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```


Gets/sets the flag indicating whether to subset fonts in output file or not.

**Returns:**
boolean - boolean value
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Returns:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


Gets/sets a certain value for date/time primitives like \\year, \\month, \\day and \\time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date instance |

### setInputDirectory(ITeXInputDirectory value) {#setInputDirectory-com.aspose.tex.ITeXInputDirectory-}
```
public final void setInputDirectory(ITeXInputDirectory value)
```


Gets/sets TeX input directory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.tex.ITeXInputDirectory | ITeXInputDirectory instance |

### setJobName(String value) {#setJobName-java.lang.String-}
```
public final void setJobName(String value)
```


Gets/set the name of the job.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setNoLigatures(boolean value) {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```


Gets/sets a flag that cancels ligatures in all fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOutputDirectory(ITeXOutputDirectory value) {#setOutputDirectory-com.aspose.tex.ITeXOutputDirectory-}
```
public final void setOutputDirectory(ITeXOutputDirectory value)
```


Gets/sets TeX output directory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.tex.ITeXOutputDirectory | ITeXOutputDirectory instance |

### setRasterizeFormulas(boolean value) {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```


Gets/sets a flag that allows to rasterize math formulas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRepeat(boolean value) {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```


Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input TeX file(s). In general, this behavior is useful when the engine collects some data along the typesetting process and stores it in an auxilliary file, all at the first run. And at the second run, the engine somehow uses that data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setShowTerminalOutput(boolean value) {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```


Gets/sets the flag indicating whether to show terminal output on the console.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSubsetFonts(boolean value) {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```


Gets/sets the flag indicating whether to subset fonts in output file or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

