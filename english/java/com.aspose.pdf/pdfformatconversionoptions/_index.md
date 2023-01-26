---
title: PdfFormatConversionOptions
second_title: Aspose.PDF for Java API Reference
description: represents set of options for convert PDF document
type: docs
weight: 281
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
| [PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action)](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-) | Constructor |
| [PdfFormatConversionOptions(String outputLogFileName, PdfFormat format)](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Constructor |
| [PdfFormatConversionOptions(PdfFormat format)](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Constructor |
| [PdfFormatConversionOptions(PdfFormat format, int action)](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-int-) | Constructor |
| [PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action, int transparencyAction)](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-int-) | Constructor |
| [PdfFormatConversionOptions(OutputStream outputLogStream, PdfFormat format, int action)](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [isAsyncImageStreamsConversionMode()](#isAsyncImageStreamsConversionMode--) | Gets/sets run of image streams in async mode. |
| [setAsyncImageStreamsConversionMode(boolean value)](#setAsyncImageStreamsConversionMode-boolean-) | Gets/sets run of image streams in async mode. |
| [isLowMemoryMode()](#isLowMemoryMode--) | Is low memory conversion mode enabled |
| [setLowMemoryMode(boolean value)](#setLowMemoryMode-boolean-) | Is low memory conversion mode enabled |
| [getFormat()](#getFormat--) | PDF format. |
| [setFormat(PdfFormat value)](#setFormat-com.aspose.pdf.PdfFormat-) | PDF format. |
| [getLogFileName()](#getLogFileName--) | Path to file where comments will be stored. |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Path to file where comments will be stored. |
| [getLogStream()](#getLogStream--) | Stream where comments will be stored. |
| [setLogStream(OutputStream value)](#setLogStream-java.io.OutputStream-) | Stream where comments will be stored. |
| [getErrorAction()](#getErrorAction--) | Action for objects that can not be converted |
| [setErrorAction(int value)](#setErrorAction-int-) | Action for objects that can not be converted |
| [getTransparencyAction()](#getTransparencyAction--) | Action for image masked objects |
| [setTransparencyAction(int value)](#setTransparencyAction-int-) | Action for image masked objects |
| [isTransparencyIgnore()](#isTransparencyIgnore--) | Default value FALSE and transparency color will be proceed to keep document appearance. |
| [setTransparencyIgnore(boolean value)](#setTransparencyIgnore-boolean-) | Default value FALSE and transparency color will be proceed to keep document appearance. |
| [getConvertSoftMaskAction()](#getConvertSoftMaskAction--) | Action for images with soft mask. |
| [setConvertSoftMaskAction(int value)](#setConvertSoftMaskAction-int-) | Action for images with soft mask. |
| [getDefault()](#getDefault--) | Gets PdfFormatConversionOptions object with default parameters |
| [getNonSpecificationCases()](#getNonSpecificationCases--) | Holds flags to control PDF/A conversion process for cases when source document doesn't correspond to PDF/A specification. |
| [getSymbolicFontEncodingStrategy()](#getSymbolicFontEncodingStrategy--) | Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable. |
| [setSymbolicFontEncodingStrategy(PdfASymbolicFontEncodingStrategy value)](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable. |
| [getAlignText()](#getAlignText--) | This flag controls text alignment in converted document. |
| [setAlignText(boolean value)](#setAlignText-boolean-) | This flag controls text alignment in converted document. |
| [getPuaTextProcessingStrategy()](#getPuaTextProcessingStrategy--) | Strategy to process symbols from unicode Private Use Area (PUA). |
| [setPuaTextProcessingStrategy(int value)](#setPuaTextProcessingStrategy-int-) | Strategy to process symbols from unicode Private Use Area (PUA). |
| [getOptimizeFileSize()](#getOptimizeFileSize--) | Gets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. |
| [setOptimizeFileSize(boolean value)](#setOptimizeFileSize-boolean-) | Sets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. |
| [getExcludeFontsStrategy()](#getExcludeFontsStrategy--) | Strategy(ies) to exclude superfluous fonts and reduce document file size. |
| [setExcludeFontsStrategy(byte value)](#setExcludeFontsStrategy-byte-) | Strategy(ies) to exclude superfluous fonts and reduce document file size. |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) | Options for cases when it's not possible to embed some fonts into PDF document. |
| [getUnicodeProcessingRules()](#getUnicodeProcessingRules--) | Rules to solve problems with unicode mapping. |
| [setUnicodeProcessingRules(ToUnicodeProcessingRules value)](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Rules to solve problems with unicode mapping. |
| [getIccProfileFileName()](#getIccProfileFileName--) | Gets the filename of icc profile name. |
| [setIccProfileFileName(String value)](#setIccProfileFileName-java.lang.String-) | Sets the filename of icc profile name. |
| [getNotAccessibleFonts()](#getNotAccessibleFonts--) | This property is out-property. |
| [isTransferInfo()](#isTransferInfo--) | Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. |
| [setTransferInfo(boolean value)](#setTransferInfo-boolean-) | Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. |
| [getTransparencyResolution()](#getTransparencyResolution--) | Sets resolution during converting transparent images. |
| [setTransparencyResolution(int dpi)](#setTransparencyResolution-int-) | Sets resolution during converting transparent images. |
| [setPageByPageFontProcess(boolean b)](#setPageByPageFontProcess-boolean-) | Set font analyse on page by page basis mode enabled |
| [isPageByPageFontProcess()](#isPageByPageFontProcess--) | Is font analyse on page by page basis mode enabled |
| [getAlignStrategy()](#getAlignStrategy--) | Strategy to align text. |
| [setAlignStrategy(byte alignStrategy)](#setAlignStrategy-byte-) | Strategy to align text. |
| [addNotAccessibleFont(String fontName)](#addNotAccessibleFont-java.lang.String-) |  |
### PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action) {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-}
```
public PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | The pdf format. |
| action | int | Action for objects that can not be converted |

### PdfFormatConversionOptions(String outputLogFileName, PdfFormat format) {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
```
public PdfFormatConversionOptions(String outputLogFileName, PdfFormat format)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | The pdf format. |

### PdfFormatConversionOptions(PdfFormat format) {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
```
public PdfFormatConversionOptions(PdfFormat format)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | The pdf format. |

### PdfFormatConversionOptions(PdfFormat format, int action) {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-int-}
```
public PdfFormatConversionOptions(PdfFormat format, int action)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | The pdf format. |
| action | int | Action for objects that can not be converted |

### PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action, int transparencyAction) {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-int-}
```
public PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action, int transparencyAction)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | The pdf format. |
| action | int | Action for objects that can not be converted |
| transparencyAction | int | Action for image masked objects |

### PdfFormatConversionOptions(OutputStream outputLogStream, PdfFormat format, int action) {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-}
```
public PdfFormatConversionOptions(OutputStream outputLogStream, PdfFormat format, int action)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | Stream where comments will be stored |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | The pdf format |
| action | int | Action for objects that can not be converted |

### isAsyncImageStreamsConversionMode() {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```


Gets/sets run of image streams in async mode.

**Returns:**
boolean - boolean value
### setAsyncImageStreamsConversionMode(boolean value) {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```


Gets/sets run of image streams in async mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isLowMemoryMode() {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
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
public PdfFormat getFormat()
```


PDF format.

**Returns:**
[PdfFormat](../../com.aspose.pdf/pdfformat) - PdfFormat element
### setFormat(PdfFormat value) {#setFormat-com.aspose.pdf.PdfFormat-}
```
public void setFormat(PdfFormat value)
```


PDF format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat element |

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

### isTransparencyIgnore() {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```


Default value FALSE and transparency color will be proceed to keep document appearance. With value TRUE transparency color will be converted into non-transparency, some objects could be covered.

**Returns:**
boolean - boolean value
### setTransparencyIgnore(boolean value) {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```


Default value FALSE and transparency color will be proceed to keep document appearance. With value TRUE transparency color will be converted into non-transparency, some objects could be covered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getConvertSoftMaskAction() {#getConvertSoftMaskAction--}
```
public final int getConvertSoftMaskAction()
```


Action for images with soft mask.

**Returns:**
int - int value
### setConvertSoftMaskAction(int value) {#setConvertSoftMaskAction-int-}
```
public final void setConvertSoftMaskAction(int value)
```


Action for images with soft mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

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
### getSymbolicFontEncodingStrategy() {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```


Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable.

**Returns:**
[PdfASymbolicFontEncodingStrategy](../../com.aspose.pdf/pdfasymbolicfontencodingstrategy) - PdfASymbolicFontEncodingStrategy object
### setSymbolicFontEncodingStrategy(PdfASymbolicFontEncodingStrategy value) {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
```
public void setSymbolicFontEncodingStrategy(PdfASymbolicFontEncodingStrategy value)
```


Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfASymbolicFontEncodingStrategy](../../com.aspose.pdf/pdfasymbolicfontencodingstrategy) | PdfASymbolicFontEncodingStrategy object |

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
### getUnicodeProcessingRules() {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```


Rules to solve problems with unicode mapping. Can be null.

**Returns:**
[ToUnicodeProcessingRules](../../com.aspose.pdf/tounicodeprocessingrules) - ToUnicodeProcessingRules object
### setUnicodeProcessingRules(ToUnicodeProcessingRules value) {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
```
public void setUnicodeProcessingRules(ToUnicodeProcessingRules value)
```


Rules to solve problems with unicode mapping. Can be null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ToUnicodeProcessingRules](../../com.aspose.pdf/tounicodeprocessingrules) | ToUnicodeProcessingRules object |

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
### isTransferInfo() {#isTransferInfo--}
```
public final boolean isTransferInfo()
```


Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. True by default.

**Returns:**
boolean - boolean value
### setTransferInfo(boolean value) {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```


Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. True by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getTransparencyResolution() {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```


Sets resolution during converting transparent images. The higher resolution, the slower converting speed. The default value is 300.

**Returns:**
int - Resolution value
### setTransparencyResolution(int dpi) {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```


Sets resolution during converting transparent images. The higher resolution, the slower converting speed. The default value is 300.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpi | int | Resolution value |

### setPageByPageFontProcess(boolean b) {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```


Set font analyse on page by page basis mode enabled

Default value = false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b | boolean | boolean value |

### isPageByPageFontProcess() {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```


Is font analyse on page by page basis mode enabled

Default value = false

**Returns:**
boolean - boolean value
### getAlignStrategy() {#getAlignStrategy--}
```
public byte getAlignStrategy()
```


Strategy to align text. This parameter has sense only when flag  AlignText  is set to true.

**Returns:**
byte - SegmentAlignStrategy element
### setAlignStrategy(byte alignStrategy) {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```


Strategy to align text. This parameter has sense only when flag  AlignText  is set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alignStrategy | byte | SegmentAlignStrategy element |

### addNotAccessibleFont(String fontName) {#addNotAccessibleFont-java.lang.String-}
```
public void addNotAccessibleFont(String fontName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String |  |

