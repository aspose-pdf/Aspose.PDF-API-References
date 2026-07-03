---
title: UnifiedSaveOptions
second_title: Aspose.PDF for Java API Reference
description: This class represents saving options for saving that uses unified conversion way (with unified internal document model)
type: docs
weight: 5420
url: /java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

This class represents saving options for saving that uses unified conversion way (with unified internal document model)

## Fields

| Field | Description |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | Process pages in few threads. |

## Constructors

| Constructor | Description |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. Value: {@code true} text will be extracted in result document; otherwise, {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. </p>Value: {@code true} text will be extracted in result document; otherwise, {@code false}. <hr> Default value == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

Process pages in few threads.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

**Returns:**
ConversionProgressEventsTranslator instance

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. Value: {@code true} text will be extracted in result document; otherwise, {@code false}.

**Returns:**
boolean value

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Returns:**
boolean value

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. </p>Value: {@code true} text will be extracted in result document; otherwise, {@code false}. <hr> Default value == false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | boolean value |
