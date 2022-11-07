---
title: SvgSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to SVG format
type: docs
weight: 279
url: /java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions)
```
public class SvgSaveOptions extends SaveOptions
```

Save options for export to SVG format
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgSaveOptions()](#SvgSaveOptions--) | Constructor |
## Fields

| Field | Description |
| --- | --- |
| [CustomStrategyOfEmbeddedImagesSaving](#CustomStrategyOfEmbeddedImagesSaving) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. |
| [TreatTargetFileNameAsDirectory](#TreatTargetFileNameAsDirectory) | This options defines whether will be created target directory (if absent yet) with same name as requested output file instead of requested output file itself. |
| [CompressOutputToZipArchive](#CompressOutputToZipArchive) | Specifies whether output will be created as one zip-archive. |
### SvgSaveOptions() {#SvgSaveOptions--}
```
public SvgSaveOptions()
```


Constructor

### CustomStrategyOfEmbeddedImagesSaving {#CustomStrategyOfEmbeddedImagesSaving}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving
```


This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. That strategy must process resources and return string that represents desirable URI of saved resource in generated SVG. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .

### TreatTargetFileNameAsDirectory {#TreatTargetFileNameAsDirectory}
```
public boolean TreatTargetFileNameAsDirectory
```


This options defines whether will be created target directory (if absent yet) with same name as requested output file instead of requested output file itself. It so, that directory will contain all output SVG-images of pages (like described below). If no, output files of pages other then first one will be created exactly in requested directory as main output file, but will contain in file name suffix \_[2...n], that is defined by page number, f.e. if You define output file "C:\\AsposeTests\\output.svg" and output will contain several svg-files of pages, then files of pages will be created also in directory "C:\\AsposeTests\\" and have names 'output.svg', 'output\_2.svg', 'output\_3.svg' etc.

### CompressOutputToZipArchive {#CompressOutputToZipArchive}
```
public boolean CompressOutputToZipArchive
```


Specifies whether output will be created as one zip-archive. Please refer comment to 'TreatTargetFileNameAsDirectory' options to see rules of naming of svg-files of pages for multipage source document, that are also applied to zipped set of output files.

