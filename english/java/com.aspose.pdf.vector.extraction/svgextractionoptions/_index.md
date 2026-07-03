---
title: SvgExtractionOptions
linktitle: SvgExtractionOptions
second_title: Aspose.PDF for Java API Reference
description: Represents an options class for extracting vector graphics from the pdf document page.
type: docs
weight: 30
url: /java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

Represents an options class for extracting vector graphics from the pdf document page.

## Constructors

| Constructor | Description |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | Creates SvgExtractionOptions class instance. |

## Methods

| Method | Description |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Gets and sets the option to automatically group subpaths into images. This option excludes the {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) option. |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | Gets and sets option to extracts every subpath from a PDF document to separate SVG images. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | Gets and sets the bounding rectangle that defines the extraction area for SVG extraction. |
| [getGroupStrength](#getGroupStrength--) | Gets and sets an option The strength of grouping subpaths into images. Allows you to configure the degree of grouping of subpaths. The value ranges is from 0 to 1. A value of 0 corresponds to the {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) option being enabled. A value of 1 will create single image for all vector paths on the page. The option has an effect when {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) is false. The default value is {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Gets or sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5. The value is expressed in transformed user space units of the converted PDF page. By default 1 user space unit is 1/72 inch (0.35 mm), but this can be overridden by the PDF document. Transforms can affect the actual minimum width in the generated SVG. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Gets and sets an option to define strictly checks whether subpaths are within the specified rectangle in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). If set to false, then subpaths that are not completely included in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) will be extracted. The default value is {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Gets and sets a flag that determines whether XFrom found on pages should be unpacked or not. XFrom elements can end up in different SVG files. Only XForms that are rendered by Do statements from the page content are unpacked. Nested XForms are not unpacked. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Gets and sets option to unpack only the XForm corresponding to the specified predicate. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Gets and sets the option to automatically group subpaths into images. This option excludes the {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) option. |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | Gets and sets option to extracts every subpath from a PDF document to separate SVG images. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | Gets and sets the bounding rectangle that defines the extraction area for SVG extraction. |
| [setGroupStrength](#setGroupStrength-double-) | Gets and sets an option The strength of grouping subpaths into images. Allows you to configure the degree of grouping of subpaths. The value ranges is from 0 to 1. A value of 0 corresponds to the {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) option being enabled. A value of 1 will create single image for all vector paths on the page. The option has an effect when {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) is false. The default value is {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Gets or sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5. The value is expressed in transformed user space units of the converted PDF page. By default 1 user space unit is 1/72 inch (0.35 mm), but this can be overridden by the PDF document. Transforms can affect the actual minimum width in the generated SVG. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Gets and sets an option to define strictly checks whether subpaths are within the specified rectangle in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). If set to false, then subpaths that are not completely included in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) will be extracted. The default value is {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Gets and sets a flag that determines whether XFrom found on pages should be unpacked or not. XFrom elements can end up in different SVG files. Only XForms that are rendered by Do statements from the page content are unpacked. Nested XForms are not unpacked. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Gets and sets option to unpack only the XForm corresponding to the specified predicate. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

Creates SvgExtractionOptions class instance.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Gets and sets the option to automatically group subpaths into images. This option excludes the {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) option.

**Returns:**
boolean value

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

Gets and sets option to extracts every subpath from a PDF document to separate SVG images.

**Returns:**
boolean value

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

Gets and sets the bounding rectangle that defines the extraction area for SVG extraction.

**Returns:**
Rectangle instance

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Gets and sets an option The strength of grouping subpaths into images. Allows you to configure the degree of grouping of subpaths. The value ranges is from 0 to 1. A value of 0 corresponds to the {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) option being enabled. A value of 1 will create single image for all vector paths on the page. The option has an effect when {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) is false. The default value is {@code 0.8}.

**Returns:**
double value

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Gets or sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5. The value is expressed in transformed user space units of the converted PDF page. By default 1 user space unit is 1/72 inch (0.35 mm), but this can be overridden by the PDF document. Transforms can affect the actual minimum width in the generated SVG.

**Returns:**
double value

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Gets and sets an option to define strictly checks whether subpaths are within the specified rectangle in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). If set to false, then subpaths that are not completely included in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) will be extracted. The default value is {@code True}.

**Returns:**
boolean value

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Gets and sets a flag that determines whether XFrom found on pages should be unpacked or not. XFrom elements can end up in different SVG files. Only XForms that are rendered by Do statements from the page content are unpacked. Nested XForms are not unpacked.

**Returns:**
boolean value

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Gets and sets option to unpack only the XForm corresponding to the specified predicate.

**Returns:**
internal Predicate instance of XFormPlacement instance

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Gets and sets the option to automatically group subpaths into images. This option excludes the {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

Gets and sets option to extracts every subpath from a PDF document to separate SVG images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
Gets and sets the bounding rectangle that defines the extraction area for SVG extraction.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Gets and sets an option The strength of grouping subpaths into images. Allows you to configure the degree of grouping of subpaths. The value ranges is from 0 to 1. A value of 0 corresponds to the {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) option being enabled. A value of 1 will create single image for all vector paths on the page. The option has an effect when {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) is false. The default value is {@code 0.8}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Gets or sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5. The value is expressed in transformed user space units of the converted PDF page. By default 1 user space unit is 1/72 inch (0.35 mm), but this can be overridden by the PDF document. Transforms can affect the actual minimum width in the generated SVG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Gets and sets an option to define strictly checks whether subpaths are within the specified rectangle in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). If set to false, then subpaths that are not completely included in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) will be extracted. The default value is {@code True}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Gets and sets a flag that determines whether XFrom found on pages should be unpacked or not. XFrom elements can end up in different SVG files. Only XForms that are rendered by Do statements from the page content are unpacked. Nested XForms are not unpacked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Gets and sets option to unpack only the XForm corresponding to the specified predicate.
