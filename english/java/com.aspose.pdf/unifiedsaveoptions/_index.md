---
title: UnifiedSaveOptions
second_title: Aspose.PDF for Java API Reference
description: This class represents saving options for saving that uses unified conversion way with unified internal document model
type: docs
weight: 397
url: /java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions)
```
public class UnifiedSaveOptions extends SaveOptions
```

This class represents saving options for saving that uses unified conversion way (with unified internal document model)
## Constructors

| Constructor | Description |
| --- | --- |
| [UnifiedSaveOptions()](#UnifiedSaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
### UnifiedSaveOptions() {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```


### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Returns:**
boolean - boolean value
### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | boolean value |

### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

**Returns:**
com.aspose.pdf.ConversionProgressEventsTranslator - ConversionProgressEventsTranslator instance
### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | ConversionProgressEventsTranslator instance |

### isExtractOcrSublayerOnly() {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```


This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer.

Value:  true  text will be extracted in result document; otherwise,  false .

**Returns:**
boolean - boolean value
### setExtractOcrSublayerOnly(boolean value) {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```


This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer.

Value:  true  text will be extracted in result document; otherwise,  false .

--------------------

Default value == false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

