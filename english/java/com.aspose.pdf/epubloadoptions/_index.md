---
title: EpubLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Contains options for loading/importing EPUB file into pdf document.
type: docs
weight: 1220
url: /java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

Contains options for loading/importing EPUB file into pdf document.

## Constructors

| Constructor | Description |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | Creates default load options for converting EPUB file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Creates default load options for converting EPUB file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508. |

## Methods

| Method | Description |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Gets or sets the custom Css to apply when opening the Epub document. |
| [getEngineType](#getEngineType--) | Select engine type for conversion EPUB to PDF Default is EngineType.NEW |
| [getMargin](#getMargin--) | Gets reference on object that represent marging info. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins. |
| [getPageSize](#getPageSize--) | Gets output page size for import. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document). |
| [setCustomCss](#setCustomCss-java.lang.String-) | Gets or sets the custom Css to apply when opening the Epub document. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | Select engine type for conversion EPUB to PDF Default is EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Gets reference on object that represent marging info. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

Creates default load options for converting EPUB file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
Creates default load options for converting EPUB file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Gets or sets the custom Css to apply when opening the Epub document.

**Returns:**
String value

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

Select engine type for conversion EPUB to PDF Default is EngineType.NEW

**Returns:**
EngineType element

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Gets reference on object that represent marging info.

**Returns:**
MarginInfo object

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins.

**Returns:**
MarginsAreaUsageModes value @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Gets output page size for import.

**Returns:**
Dimension2D object

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document).

**Returns:**
PageSizeAdjustmentModes value @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Gets or sets the custom Css to apply when opening the Epub document.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
Select engine type for conversion EPUB to PDF Default is EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Gets reference on object that represent marging info.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| marginsAreaUsageMode |  | MarginsAreaUsageModes value @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | PageSizeAdjustmentModes value @see PageSizeAdjustmentModes |
