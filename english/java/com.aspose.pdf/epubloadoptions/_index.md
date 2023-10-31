---
title: EpubLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Contains options for loading/importing EPUB file into pdf document.
type: docs
weight: 98
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
| [EpubLoadOptions(Dimension2D pageSize)](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Creates load options with specified page size. |
## Methods

| Method | Description |
| --- | --- |
| [getPageSize()](#getPageSize--) | Gets output page size for import. |
| [getMargin()](#getMargin--) | Gets reference on object that represent marging info. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Gets reference on object that represent marging info. |
| [getMarginsAreaUsageMode()](#getMarginsAreaUsageMode--) | Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins. |
| [setMarginsAreaUsageMode(int marginsAreaUsageMode)](#setMarginsAreaUsageMode-int-) | Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins. |
| [getPageSizeAdjustmentMode()](#getPageSizeAdjustmentMode--) | ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. |
| [setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)](#setPageSizeAdjustmentMode-int-) | ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. |
### EpubLoadOptions() {#EpubLoadOptions--}
```
public EpubLoadOptions()
```


Creates default load options for converting EPUB file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508.

### EpubLoadOptions(Dimension2D pageSize) {#EpubLoadOptions-java.awt.geom.Dimension2D-}
```
public EpubLoadOptions(Dimension2D pageSize)
```


Creates load options with specified page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | java.awt.geom.Dimension2D | Defines pdf page width and height. |

### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


Gets output page size for import.

**Returns:**
java.awt.geom.Dimension2D - Dimension2D object
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets reference on object that represent marging info.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo object
### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public final void setMargin(MarginInfo value)
```


Gets reference on object that represent marging info.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### getMarginsAreaUsageMode() {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```


Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins.

**Returns:**
int - MarginsAreaUsageModes value
### setMarginsAreaUsageMode(int marginsAreaUsageMode) {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```


Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| marginsAreaUsageMode | int | MarginsAreaUsageModes value |

### getPageSizeAdjustmentMode() {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```


ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document).

**Returns:**
int - PageSizeAdjustmentModes value
### setPageSizeAdjustmentMode(int pageSizeAdjustmentMode) {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```


ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSizeAdjustmentMode | int | PageSizeAdjustmentModes value |

