---
title: PdfFormatConversionOptions
second_title: Aspose.PDF for Java API Reference
description: represents set of options for convert PDF document
type: docs
weight: 3730
url: /java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

represents set of options for convert PDF document

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | Strategy to align text. This parameter has sense only when flag {@code AlignText} is set to true. |
| [getAlignText](#getAlignText--) | This flag controls text alignment in converted document. By default document conversion doesn't affect text alignment and leave text as is. But in some cases font substitution causes text overlapping or extra spaces in converted document. When this flag is set special alignment operations will be performed. This flag should be set only for documents which have problems with overlapped text or extra text spaces cause using of this flag decrease performance and in some cases could corrupt text content. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | Gets or sets the settings for automatic tagging during PDF format conversion. Automatic tagging settings are used to configure the behavior of the auto-tagging process, which is typically employed to enhance the accessibility and structure of a PDF document during conversion to a specific PDF format. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | Action for images with soft mask. |
| [getDefault](#getDefault--) | Gets PdfFormatConversionOptions object with default parameters |
| [getErrorAction](#getErrorAction--) | Action for objects that can not be converted |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | Strategy(ies) to exclude superfluous fonts and reduce document file size. This parameter has sense only when flag {@code OptimizeFileSize} is set to true. By default combination of strategies {@code SubsetFonts} and {@code RemoveDuplicatedFonts} is used. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | Options for cases when it's not possible to embed some fonts into PDF document. |
| [getFormat](#getFormat--) | PDF format. |
| [getIccProfileFileName](#getIccProfileFileName--) | Gets the filename of icc profile name. In case of null the default icc profile used. |
| [getLogFileName](#getLogFileName--) | Path to file where comments will be stored. |
| [getLogStream](#getLogStream--) | Stream where comments will be stored. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | Holds flags to control PDF/A conversion process for cases when source document doesn't correspond to PDF/A specification. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | This property is out-property. It holds all the fonts(font names) which were not found on computer at last PDF/A conversion. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | Gets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag also will be used to switch on optimization for another data structures, such as graphic. Set of this flag and mode could significantly reduce file size but at the same time it could significantly decrease performance of conversion. |
| [getOutputIntent](#getOutputIntent--) | Gets or sets the {@link OutputIntent} for the PDF format conversion. The {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specifies the intended output device or condition for which the PDF document is being prepared. It is used to ensure that the colors in the document are rendered correctly on the target device. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Strategy to process symbols from unicode Private Use Area (PUA). |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable. |
| [getTransparencyAction](#getTransparencyAction--) | Action for image masked objects |
| [getTransparencyResolution](#getTransparencyResolution--) | Sets resolution during converting transparent images. The higher resolution, the slower converting speed. The default value is 300. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Rules to solve problems with unicode mapping. Can be null. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | Gets/sets run of image streams in async mode. |
| [isLowMemoryMode](#isLowMemoryMode--) | Is low memory conversion mode enabled |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | Is font analyse on page by page basis mode enabled Default value = false |
| [isTransferInfo](#isTransferInfo--) | Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. True by default. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | Default value FALSE and transparency color will be proceed to keep document appearance. With value TRUE transparency color will be converted into non-transparency, some objects could be covered. |
| [setAlignStrategy](#setAlignStrategy-byte-) | Strategy to align text. This parameter has sense only when flag {@code AlignText} is set to true. |
| [setAlignText](#setAlignText-boolean-) | This flag controls text alignment in converted document. By default document conversion doesn't affect text alignment and leave text as is. But in some cases font substitution causes text overlapping or extra spaces in converted document. When this flag is set special alignment operations will be performed. This flag should be set only for documents which have problems with overlapped text or extra text spaces cause using of this flag decrease performance and in some cases could corrupt text content. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | Gets/sets run of image streams in async mode. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | Gets or sets the settings for automatic tagging during PDF format conversion. Automatic tagging settings are used to configure the behavior of the auto-tagging process, which is typically employed to enhance the accessibility and structure of a PDF document during conversion to a specific PDF format. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | Action for images with soft mask. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | Action for objects that can not be converted |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | Strategy(ies) to exclude superfluous fonts and reduce document file size. This parameter has sense only when flag {@code OptimizeFileSize} is set to true. By default combination of strategies {@code SubsetFonts} and {@code RemoveDuplicatedFonts} is used. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | PDF format. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | Sets the filename of icc profile name. In case of null the default icc profile used. |
| [setLogFileName](#setLogFileName-java.lang.String-) | Path to file where comments will be stored. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | Stream where comments will be stored. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | Is low memory conversion mode enabled |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | Sets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag also will be used to switch on optimization for another data structures, such as graphic. Set of this flag and mode could significantly reduce file size but at the same time it could significantly decrease performance of conversion. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | Gets or sets the {@link OutputIntent} for the PDF format conversion. The {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specifies the intended output device or condition for which the PDF document is being prepared. It is used to ensure that the colors in the document are rendered correctly on the target device. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | Set font analyse on page by page basis mode enabled Default value = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Strategy to process symbols from unicode Private Use Area (PUA). |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable. |
| [setTransferInfo](#setTransferInfo-boolean-) | Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. True by default. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | Action for image masked objects |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | Default value FALSE and transparency color will be proceed to keep document appearance. With value TRUE transparency color will be converted into non-transparency, some objects could be covered. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | Sets resolution during converting transparent images. The higher resolution, the slower converting speed. The default value is 300. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Rules to solve problems with unicode mapping. Can be null. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Constructor

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

Strategy to align text. This parameter has sense only when flag {@code AlignText} is set to true.

**Returns:**
SegmentAlignStrategy element @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

This flag controls text alignment in converted document. By default document conversion doesn't affect text alignment and leave text as is. But in some cases font substitution causes text overlapping or extra spaces in converted document. When this flag is set special alignment operations will be performed. This flag should be set only for documents which have problems with overlapped text or extra text spaces cause using of this flag decrease performance and in some cases could corrupt text content.

**Returns:**
boolean value

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

Gets or sets the settings for automatic tagging during PDF format conversion. Automatic tagging settings are used to configure the behavior of the auto-tagging process, which is typically employed to enhance the accessibility and structure of a PDF document during conversion to a specific PDF format.

**Returns:**
AutoTaggingSettings instance

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

Action for images with soft mask.

**Returns:**
int value

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

Gets PdfFormatConversionOptions object with default parameters

**Returns:**
PdfFormatConversionOptions object

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

Action for objects that can not be converted

**Returns:**
ConvertErrorAction element @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

Strategy(ies) to exclude superfluous fonts and reduce document file size. This parameter has sense only when flag {@code OptimizeFileSize} is set to true. By default combination of strategies {@code SubsetFonts} and {@code RemoveDuplicatedFonts} is used.

**Returns:**
byte value @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

Options for cases when it's not possible to embed some fonts into PDF document.

**Returns:**
FontEmbeddingOptions object

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

PDF format.

**Returns:**
PdfFormat element @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

Gets the filename of icc profile name. In case of null the default icc profile used.

**Returns:**
String object

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

Path to file where comments will be stored.

**Returns:**
String object

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

Stream where comments will be stored.

**Returns:**
OutputStream object

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

Holds flags to control PDF/A conversion process for cases when source document doesn't correspond to PDF/A specification.

**Returns:**
PdfANonSpecificationFlags object

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

This property is out-property. It holds all the fonts(font names) which were not found on computer at last PDF/A conversion.

**Returns:**
Array of Strings

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

Gets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag also will be used to switch on optimization for another data structures, such as graphic. Set of this flag and mode could significantly reduce file size but at the same time it could significantly decrease performance of conversion.

**Returns:**
boolean value

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

Gets or sets the {@link OutputIntent} for the PDF format conversion. The {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specifies the intended output device or condition for which the PDF document is being prepared. It is used to ensure that the colors in the document are rendered correctly on the target device.

**Returns:**
OutputIntent instance

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Strategy to process symbols from unicode Private Use Area (PUA).

**Returns:**
PuaProcessingStrategy element @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable.

**Returns:**
PdfASymbolicFontEncodingStrategy object

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

Action for image masked objects

**Returns:**
ConvertTransparencyAction element @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

Sets resolution during converting transparent images. The higher resolution, the slower converting speed. The default value is 300.

**Returns:**
Resolution value

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Rules to solve problems with unicode mapping. Can be null.

**Returns:**
ToUnicodeProcessingRules object

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

Gets/sets run of image streams in async mode.

**Returns:**
boolean value

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

Is low memory conversion mode enabled

**Returns:**
boolean value

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

Is font analyse on page by page basis mode enabled Default value = false

**Returns:**
boolean value

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. True by default.

**Returns:**
boolean value

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

Default value FALSE and transparency color will be proceed to keep document appearance. With value TRUE transparency color will be converted into non-transparency, some objects could be covered.

**Returns:**
boolean value

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

Strategy to align text. This parameter has sense only when flag {@code AlignText} is set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alignStrategy |  | SegmentAlignStrategy element @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

This flag controls text alignment in converted document. By default document conversion doesn't affect text alignment and leave text as is. But in some cases font substitution causes text overlapping or extra spaces in converted document. When this flag is set special alignment operations will be performed. This flag should be set only for documents which have problems with overlapped text or extra text spaces cause using of this flag decrease performance and in some cases could corrupt text content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

Gets/sets run of image streams in async mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
Gets or sets the settings for automatic tagging during PDF format conversion. Automatic tagging settings are used to configure the behavior of the auto-tagging process, which is typically employed to enhance the accessibility and structure of a PDF document during conversion to a specific PDF format.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
Action for images with soft mask.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
Action for objects that can not be converted

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

Strategy(ies) to exclude superfluous fonts and reduce document file size. This parameter has sense only when flag {@code OptimizeFileSize} is set to true. By default combination of strategies {@code SubsetFonts} and {@code RemoveDuplicatedFonts} is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
PDF format.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
Sets the filename of icc profile name. In case of null the default icc profile used.

### setLogFileName {#setLogFileName-java.lang.String-}
Path to file where comments will be stored.

### setLogStream {#setLogStream-java.io.OutputStream-}
Stream where comments will be stored.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

Is low memory conversion mode enabled

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

Sets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag also will be used to switch on optimization for another data structures, such as graphic. Set of this flag and mode could significantly reduce file size but at the same time it could significantly decrease performance of conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
Gets or sets the {@link OutputIntent} for the PDF format conversion. The {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specifies the intended output device or condition for which the PDF document is being prepared. It is used to ensure that the colors in the document are rendered correctly on the target device.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

Set font analyse on page by page basis mode enabled Default value = false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b |  | boolean value |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Strategy to process symbols from unicode Private Use Area (PUA).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | PuaProcessingStrategy element @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. True by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
Action for image masked objects

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

Default value FALSE and transparency color will be proceed to keep document appearance. With value TRUE transparency color will be converted into non-transparency, some objects could be covered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

Sets resolution during converting transparent images. The higher resolution, the slower converting speed. The default value is 300.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpi |  | Resolution value |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Rules to solve problems with unicode mapping. Can be null.
