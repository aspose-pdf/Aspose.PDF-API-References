---
title: IPdfFileEditor.ContentsResizeParameters
linktitle: IPdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for Java API Reference
description: 'Class for specifing page resize parameters. Allow to set the following parameters: Size of result page (width, height) in default space units or in percents of initial pages.'
type: docs
weight: 300
url: /java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Class for specifing page resize parameters. Allow to set the following parameters: Size of result page (width, height) in default space units or in percents of initial pages size; Left, Top, Bottom and Right margins in default space units or in percents of initial page size; Some values may be left null for automatic calculation. These values will be calculated from rest of page size after calculation explicitly specified values. For example: if page width = 100 and new page width specified 60 units then left and right margins are automatically calculated: (100 - 60) / 2 = 15. This class is used in ResizeContents method.

## Constructors

| Constructor | Description |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Creates resize parameters where al values are set to "auto". Later margins and contents size may be specified if required. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Creates resize parameters where al values are set to "auto". Later margins and contents size may be specified if required. |

## Methods

| Method | Description |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Creates resize parameters with specified contents size. |
| [contentSizePercent](#contentSizePercent-double-double-) | Creates resize parameters with specified conets size in percents of initial page size. Margins are caculated automatically. |
| [getBottomMargin](#getBottomMargin--) | Gets or sets bottom margin on the resultant page. |
| [getContentsHeight](#getContentsHeight--) | Gets or sets height of the content of the source page on the resultant page. |
| [getContentsWidth](#getContentsWidth--) | Gets or sets width of the content of the source page on the resultant page. |
| [getLeftMargin](#getLeftMargin--) | Gets or sets left margin on the resultant page. |
| [getRightMargin](#getRightMargin--) | Gets or sets right margin on the resultant page. |
| [getTopMargin](#getTopMargin--) | Gets or sets top margin on the resultant page. |
| [isChangeMediaBox](#isChangeMediaBox--) | Gets whether to adjust the MediaBox of a PDF page during the resizing operation. The default value is {@code false} Setting this parameter enables fitting the MediaBox to the CropBox value during resizing. |
| [margins](#margins-double-double-double-double-) | Creates resize parameters with specifed margins value. Contents size is automatically calculated. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Creates resize parameters. Margins are specified in percents of initial page size. |
| [pageResize](#pageResize-double-double-) | Creates resize paramters for page resize. |
| [pageResizePct](#pageResizePct-double-double-) | Creates resize paramters for page resize. New sizes are specified in percent. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets bottom margin on the resultant page. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | Sets whether to adjust the MediaBox of a PDF page during the resizing operation. The default value is {@code false} Setting this parameter enables fitting the MediaBox to the CropBox value during resizing. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets height of the content of the source page on the resultant page. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets width of the content of the source page on the resultant page. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets left margin on the resultant page. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets right margin on the resultant page. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Gets or sets top margin on the resultant page. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Creates resize parameters where al values are set to "auto". Later margins and contents size may be specified if required.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Creates resize parameters where al values are set to "auto". Later margins and contents size may be specified if required.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Creates resize parameters with specified contents size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | New width of contents. |
| height |  | New height of contetns. |

**Returns:**
Returns new resize parameters.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

Creates resize parameters with specified conets size in percents of initial page size. Margins are caculated automatically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | New content width in percents. |
| height |  | New contents height in percents. |

**Returns:**
New resize parameters.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Gets or sets bottom margin on the resultant page.

**Returns:**
ContentsResizeValue object

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Gets or sets height of the content of the source page on the resultant page.

**Returns:**
ContentsResizeValue object

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Gets or sets width of the content of the source page on the resultant page.

**Returns:**
ContentsResizeValue object

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Gets or sets left margin on the resultant page.

**Returns:**
ContentsResizeValue object

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Gets or sets right margin on the resultant page.

**Returns:**
ContentsResizeValue object

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Gets or sets top margin on the resultant page.

**Returns:**
ContentsResizeValue object

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Gets whether to adjust the MediaBox of a PDF page during the resizing operation. The default value is {@code false} Setting this parameter enables fitting the MediaBox to the CropBox value during resizing.

**Returns:**
whether to adjust the MediaBox of a PDF page during the resizing operation.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Creates resize parameters with specifed margins value. Contents size is automatically calculated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left |  | Left margin. |
| right |  | Right margin. |
| top |  | Top margin. |
| bottom |  | Bottom margin. |

**Returns:**
Created resize parameters.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Creates resize parameters. Margins are specified in percents of initial page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left |  | Left margin (in percents of page width). |
| right |  | Right margin (in percents of page height). |
| top |  | Top margin (in percents of page height). |
| bottom |  | Bottom margin (in percents of page height). |

**Returns:**
Returns new resize parameters.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Creates resize paramters for page resize.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | New page width in units. |
| height |  | New page height in units. |

**Returns:**
New resize paramteres.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Creates resize paramters for page resize. New sizes are specified in percent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| widthPct |  | New page width in percents. |
| heightPct |  | New page height in percents. |

**Returns:**
New resize paramteres.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Gets or sets bottom margin on the resultant page.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

Sets whether to adjust the MediaBox of a PDF page during the resizing operation. The default value is {@code false} Setting this parameter enables fitting the MediaBox to the CropBox value during resizing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | whether to adjust the MediaBox of a PDF page during the resizing operation. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Gets or sets height of the content of the source page on the resultant page.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Gets or sets width of the content of the source page on the resultant page.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Gets or sets left margin on the resultant page.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Gets or sets right margin on the resultant page.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Gets or sets top margin on the resultant page.
