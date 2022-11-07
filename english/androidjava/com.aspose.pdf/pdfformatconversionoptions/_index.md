---
title: PdfFormatConversionOptions
second_title: Aspose.PDF for Java API Reference
description: represents set of options for convert PDF document
type: docs
weight: 227
url: /java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfFormatConversionOptions
```

represents set of options for convert PDF document
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFormatConversionOptions(String outputLogFileName, int format, int action)](#PdfFormatConversionOptions-java.lang.String-int-int-) | Constructor |
| [PdfFormatConversionOptions(String outputLogFileName, int format)](#PdfFormatConversionOptions-java.lang.String-int-) | Constructor |
| [PdfFormatConversionOptions(int format)](#PdfFormatConversionOptions-int-) | Constructor |
| [PdfFormatConversionOptions(int format, int action)](#PdfFormatConversionOptions-int-int-) | Constructor |
| [PdfFormatConversionOptions(String outputLogFileName, int format, int action, int transparencyAction)](#PdfFormatConversionOptions-java.lang.String-int-int-int-) | Constructor |
| [PdfFormatConversionOptions(OutputStream outputLogStream, int format, int action)](#PdfFormatConversionOptions-java.io.OutputStream-int-int-) | Constructor |
## Fields

| Field | Description |
| --- | --- |
| [AlignStrategy](#AlignStrategy) | Strategy to align text. |
## Methods

| Method | Description |
| --- | --- |
| [isLowMemoryMode()](#isLowMemoryMode--) | Is low memory conversion mode enabled |
| [setLowMemoryMode(boolean value)](#setLowMemoryMode-boolean-) | Is low memory conversion mode enabled |
| [getFormat()](#getFormat--) | PDF format. |
| [setFormat(int value)](#setFormat-int-) | PDF format. |
| [getLogFileName()](#getLogFileName--) | Path to file where comments will be stored. |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Path to file where comments will be stored. |
| [getLogStream()](#getLogStream--) | Stream where comments will be stored. |
| [setLogStream(OutputStream value)](#setLogStream-java.io.OutputStream-) | Stream where comments will be stored. |
| [getErrorAction()](#getErrorAction--) | Action for objects that can not be converted |
| [setErrorAction(int value)](#setErrorAction-int-) | Action for objects that can not be converted |
| [getTransparencyAction()](#getTransparencyAction--) | Action for image masked objects |
| [setTransparencyAction(int value)](#setTransparencyAction-int-) | Action for image masked objects |
| [getDefault()](#getDefault--) | Gets PdfFormatConversionOptions object with default parameters |
| [getNonSpecificationCases()](#getNonSpecificationCases--) | Holds flags to control PDF/A conversion process for cases when source document doesn't correspond to PDF/A specification. |
| [getAlignText()](#getAlignText--) | This flag controls text alignment in converted document. |
| [setAlignText(boolean value)](#setAlignText-boolean-) | This flag controls text alignment in converted document. |
| [getPuaTextProcessingStrategy()](#getPuaTextProcessingStrategy--) | Strategy to process symbols from unicode Private Use Area (PUA). |
| [setPuaTextProcessingStrategy(int value)](#setPuaTextProcessingStrategy-int-) | Strategy to process symbols from unicode Private Use Area (PUA). |
| [getOptimizeFileSize()](#getOptimizeFileSize--) | Gets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. |
| [setOptimizeFileSize(boolean value)](#setOptimizeFileSize-boolean-) | Sets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. |
| [getExcludeFontsStrategy()](#getExcludeFontsStrategy--) | Strategy(ies) to exclude superfluous fonts and reduce document file size. |
| [setExcludeFontsStrategy(byte value)](#setExcludeFontsStrategy-byte-) | Strategy(ies) to exclude superfluous fonts and reduce document file size. |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) | Options for cases when it's not possible to embed some fonts into PDF document. |
| [getIccProfileFileName()](#getIccProfileFileName--) | Gets the filename of icc profile name. |
| [setIccProfileFileName(String value)](#setIccProfileFileName-java.lang.String-) | Sets the filename of icc profile name. |
| [getNotAccessibleFonts()](#getNotAccessibleFonts--) | This property is out-property. |
### PdfFormatConversionOptions(String outputLogFileName, int format, int action) {#PdfFormatConversionOptions-java.lang.String-int-int-}
```
public PdfFormatConversionOptions(String outputLogFileName, int format, int action)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where comments will be stored. |
| format | int | The pdf format. |
| action | int | Action for objects that can not be converted |

### PdfFormatConversionOptions(String outputLogFileName, int format) {#PdfFormatConversionOptions-java.lang.String-int-}
```
public PdfFormatConversionOptions(String outputLogFileName, int format)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where comments will be stored. |
| format | int | The pdf format. |

### PdfFormatConversionOptions(int format) {#PdfFormatConversionOptions-int-}
```
public PdfFormatConversionOptions(int format)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | The pdf format. |

### PdfFormatConversionOptions(int format, int action) {#PdfFormatConversionOptions-int-int-}
```
public PdfFormatConversionOptions(int format, int action)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | The pdf format. |
| action | int | Action for objects that can not be converted |

### PdfFormatConversionOptions(String outputLogFileName, int format, int action, int transparencyAction) {#PdfFormatConversionOptions-java.lang.String-int-int-int-}
```
public PdfFormatConversionOptions(String outputLogFileName, int format, int action, int transparencyAction)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where comments will be stored. |
| format | int | The pdf format. |
| action | int | Action for objects that can not be converted |
| transparencyAction | int | Action for image masked objects |

### PdfFormatConversionOptions(OutputStream outputLogStream, int format, int action) {#PdfFormatConversionOptions-java.io.OutputStream-int-int-}
```
public PdfFormatConversionOptions(OutputStream outputLogStream, int format, int action)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | Stream where comments will be stored |
| format | int | The pdf format |
| action | int | Action for objects that can not be converted |

### AlignStrategy {#AlignStrategy}
```
public byte AlignStrategy
```


Strategy to align text. This parameter has sense only when flag  AlignText  is set to true.

### isLowMemoryMode() {#isLowMemoryMode--}
```
public boolean isLowMemoryMode()
```


Is low memory conversion mode enabled

**Returns:**
boolean - boolean value
### setLowMemoryMode(boolean value) {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```


Is low memory conversion mode enabled

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getFormat() {#getFormat--}
```
public int getFormat()
```


PDF format.

**Returns:**
int - PdfFormat element
### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


PDF format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PdfFormat element |

### getLogFileName() {#getLogFileName--}
```
public String getLogFileName()
```


Path to file where comments will be stored.

**Returns:**
java.lang.String - String object
### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public void setLogFileName(String value)
```


Path to file where comments will be stored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getLogStream() {#getLogStream--}
```
public OutputStream getLogStream()
```


Stream where comments will be stored.

**Returns:**
java.io.OutputStream - OutputStream object
### setLogStream(OutputStream value) {#setLogStream-java.io.OutputStream-}
```
public void setLogStream(OutputStream value)
```


Stream where comments will be stored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream | OutputStream object |

### getErrorAction() {#getErrorAction--}
```
public int getErrorAction()
```


Action for objects that can not be converted

**Returns:**
int - ConvertErrorAction element
### setErrorAction(int value) {#setErrorAction-int-}
```
public void setErrorAction(int value)
```


Action for objects that can not be converted

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ConvertErrorAction element |

### getTransparencyAction() {#getTransparencyAction--}
```
public int getTransparencyAction()
```


Action for image masked objects

**Returns:**
int - ConvertTransparencyAction element
### setTransparencyAction(int value) {#setTransparencyAction-int-}
```
public void setTransparencyAction(int value)
```


Action for image masked objects

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ConvertTransparencyAction element |

### getDefault() {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```


Gets PdfFormatConversionOptions object with default parameters

**Returns:**
[PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) - PdfFormatConversionOptions object
### getNonSpecificationCases() {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```


Holds flags to control PDF/A conversion process for cases when source document doesn't correspond to PDF/A specification.

**Returns:**
[PdfANonSpecificationFlags](../../com.aspose.pdf/pdfanonspecificationflags) - PdfANonSpecificationFlags object
### getAlignText() {#getAlignText--}
```
public boolean getAlignText()
```


This flag controls text alignment in converted document. By default document conversion doesn't affect text alignment and leave text as is. But in some cases font substitution causes text overlapping or extra spaces in converted document. When this flag is set special alignment operations will be performed. This flag should be set only for documents which have problems with overlapped text or extra text spaces cause using of this flag decrease performance and in some cases could corrupt text content.

**Returns:**
boolean - boolean value
### setAlignText(boolean value) {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```


This flag controls text alignment in converted document. By default document conversion doesn't affect text alignment and leave text as is. But in some cases font substitution causes text overlapping or extra spaces in converted document. When this flag is set special alignment operations will be performed. This flag should be set only for documents which have problems with overlapped text or extra text spaces cause using of this flag decrease performance and in some cases could corrupt text content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getPuaTextProcessingStrategy() {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```


Strategy to process symbols from unicode Private Use Area (PUA).

**Returns:**
int - PuaProcessingStrategy element
### setPuaTextProcessingStrategy(int value) {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```


Strategy to process symbols from unicode Private Use Area (PUA).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PuaProcessingStrategy element |

### getOptimizeFileSize() {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```


Gets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size.

Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag also will be used to switch on optimization for another data structures, such as graphic.

Set of this flag and mode could significantly reduce file size but at the same time it could significantly decrease performance of conversion.

**Returns:**
boolean - boolean value
### setOptimizeFileSize(boolean value) {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```


Sets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size.

Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag also will be used to switch on optimization for another data structures, such as graphic.

Set of this flag and mode could significantly reduce file size but at the same time it could significantly decrease performance of conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getExcludeFontsStrategy() {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```


Strategy(ies) to exclude superfluous fonts and reduce document file size. This parameter has sense only when flag  OptimizeFileSize  is set to true. By default combination of strategies  SubsetFonts  and  RemoveDuplicatedFonts  is used.

**Returns:**
byte - byte value
### setExcludeFontsStrategy(byte value) {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```


Strategy(ies) to exclude superfluous fonts and reduce document file size. This parameter has sense only when flag  OptimizeFileSize  is set to true. By default combination of strategies  SubsetFonts  and  RemoveDuplicatedFonts  is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | boolean value |

### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```


Options for cases when it's not possible to embed some fonts into PDF document.

**Returns:**
[FontEmbeddingOptions](../../com.aspose.pdf/fontembeddingoptions) - FontEmbeddingOptions object
### getIccProfileFileName() {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```


Gets the filename of icc profile name. In case of null the default icc profile used.

**Returns:**
java.lang.String - String object
### setIccProfileFileName(String value) {#setIccProfileFileName-java.lang.String-}
```
public void setIccProfileFileName(String value)
```


Sets the filename of icc profile name. In case of null the default icc profile used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getNotAccessibleFonts() {#getNotAccessibleFonts--}
```
public String[] getNotAccessibleFonts()
```


This property is out-property. It holds all the fonts(font names) which were not found on computer at last PDF/A conversion.

**Returns:**
java.lang.String[] - Array of Strings
