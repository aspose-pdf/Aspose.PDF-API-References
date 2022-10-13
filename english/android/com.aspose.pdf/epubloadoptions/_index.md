---
title: EpubLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Contains options for loading/importing EPUB file into pdf document.
type: docs
weight: 84
url: /java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class EpubLoadOptions extends LoadOptions
```

Contains options for loading/importing EPUB file into pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [EpubLoadOptions()](#EpubLoadOptions--) | Creates default load options for converting EPUB file into pdf document. |
## Fields

| Field | Description |
| --- | --- |
| [MarginsAreaUsageMode](#MarginsAreaUsageMode) | Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins. |
| [PageSizeAdjustmentMode](#PageSizeAdjustmentMode) | ATTENTION! |
## Methods

| Method | Description |
| --- | --- |
| [getMargin()](#getMargin--) | Gets reference on object that represent marging info. |
### EpubLoadOptions() {#EpubLoadOptions--}
```
public EpubLoadOptions()
```


Creates default load options for converting EPUB file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508.

### MarginsAreaUsageMode {#MarginsAreaUsageMode}
```
public int MarginsAreaUsageMode
```


Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins.

### PageSizeAdjustmentMode {#PageSizeAdjustmentMode}
```
public int PageSizeAdjustmentMode
```


ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document).

### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets reference on object that represent marging info.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo object
