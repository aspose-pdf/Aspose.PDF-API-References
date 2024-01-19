---
title: SvgSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to SVG format
type: docs
weight: 348
url: /java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class SvgSaveOptions extends UnifiedSaveOptions
```

Save options for export to SVG format
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgSaveOptions()](#SvgSaveOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving()](#getCustomStrategyOfEmbeddedImagesSaving--) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. |
| [setCustomStrategyOfEmbeddedImagesSaving(SvgSaveOptions.EmbeddedImagesSavingStrategy customStrategyOfEmbeddedImagesSaving)](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. |
| [isTreatTargetFileNameAsDirectory()](#isTreatTargetFileNameAsDirectory--) | This options defines whether will be created target directory (if absent yet) with same name as requested output file instead of requested output file itself. |
| [setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)](#setTreatTargetFileNameAsDirectory-boolean-) | This options defines whether will be created target directory (if absent yet) with same name as requested output file instead of requested output file itself. |
| [isCompressOutputToZipArchive()](#isCompressOutputToZipArchive--) | Specifies whether output will be created as one zip-archive. |
| [setCompressOutputToZipArchive(boolean compressOutputToZipArchive)](#setCompressOutputToZipArchive-boolean-) | Specifies whether output will be created as one zip-archive. |
| [isScaleToPixels()](#isScaleToPixels--) | Specifies whether to scale the output document from typographic points to pixels. |
| [setScaleToPixels(boolean scaleToPixels)](#setScaleToPixels-boolean-) | Specifies whether to scale the output document from typographic points to pixels. |
### SvgSaveOptions() {#SvgSaveOptions--}
```
public SvgSaveOptions()
```


Constructor

### getCustomStrategyOfEmbeddedImagesSaving() {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```


This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. That strategy must process resources and return string that represents desirable URI of saved resource in generated SVG. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .

**Returns:**
[EmbeddedImagesSavingStrategy](../../com.aspose.pdf/embeddedimagessavingstrategy) - EmbeddedImagesSavingStrategy instance
### setCustomStrategyOfEmbeddedImagesSaving(SvgSaveOptions.EmbeddedImagesSavingStrategy customStrategyOfEmbeddedImagesSaving) {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
```
public void setCustomStrategyOfEmbeddedImagesSaving(SvgSaveOptions.EmbeddedImagesSavingStrategy customStrategyOfEmbeddedImagesSaving)
```


This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. That strategy must process resources and return string that represents desirable URI of saved resource in generated SVG. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customStrategyOfEmbeddedImagesSaving | [EmbeddedImagesSavingStrategy](../../com.aspose.pdf/embeddedimagessavingstrategy) | EmbeddedImagesSavingStrategy instance |

### isTreatTargetFileNameAsDirectory() {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```


This options defines whether will be created target directory (if absent yet) with same name as requested output file instead of requested output file itself. It so, that directory will contain all output SVG-images of pages (like described below). If no, output files of pages other then first one will be created exactly in requested directory as main output file, but will contain in file name suffix \_[2...n], that is defined by page number, f.e. if You define output file "C:\\AsposeTests\\output.svg" and output will contain several svg-files of pages, then files of pages will be created also in directory "C:\\AsposeTests\\" and have names 'output.svg', 'output\_2.svg', 'output\_3.svg' etc.

**Returns:**
boolean - boolean value
### setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory) {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```


This options defines whether will be created target directory (if absent yet) with same name as requested output file instead of requested output file itself. It so, that directory will contain all output SVG-images of pages (like described below). If no, output files of pages other then first one will be created exactly in requested directory as main output file, but will contain in file name suffix \_[2...n], that is defined by page number, f.e. if You define output file "C:\\AsposeTests\\output.svg" and output will contain several svg-files of pages, then files of pages will be created also in directory "C:\\AsposeTests\\" and have names 'output.svg', 'output\_2.svg', 'output\_3.svg' etc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| treatTargetFileNameAsDirectory | boolean | boolean value |

### isCompressOutputToZipArchive() {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```


Specifies whether output will be created as one zip-archive. Please refer comment to 'TreatTargetFileNameAsDirectory' options to see rules of naming of svg-files of pages for multipage source document, that are also applied to zipped set of output files.

**Returns:**
boolean - boolean value
### setCompressOutputToZipArchive(boolean compressOutputToZipArchive) {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```


Specifies whether output will be created as one zip-archive. Please refer comment to 'TreatTargetFileNameAsDirectory' options to see rules of naming of svg-files of pages for multipage source document, that are also applied to zipped set of output files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressOutputToZipArchive | boolean | boolean value |

### isScaleToPixels() {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```


Specifies whether to scale the output document from typographic points to pixels.

**Returns:**
boolean - boolean value
### setScaleToPixels(boolean scaleToPixels) {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```


Specifies whether to scale the output document from typographic points to pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleToPixels | boolean | boolean value |

