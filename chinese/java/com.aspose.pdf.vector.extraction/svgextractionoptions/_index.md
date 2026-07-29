---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于从 PDF 文档页面提取矢量图形的选项类。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

表示用于从 PDF 文档页面提取矢量图形的选项类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | 创建 SvgExtractionOptions 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | 获取和设置自动将子路径分组为图像的选项。此选项排除 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) 选项。 |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | 获取和设置将 PDF 文档中的每个子路径提取为单独 SVG 图像的选项。 |
| [getExtractionAreaBound](#getExtractionAreaBound--) | 获取和设置定义 SVG 提取区域的边界矩形。 |
| [getGroupStrength](#getGroupStrength--) | 获取和设置子路径分组为图像的强度选项。允许您配置子路径分组的程度。取值范围为 0 到 1。值为 0 时对应启用 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) 选项。值为 1 时将在页面上为所有矢量路径创建单个图像。当 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) 为 false 时，此选项生效。默认值为 {@code 0.8}。 |
| [getMinStrokeWidth](#getMinStrokeWidth--) | 获取或设置生成的 SVG 中使用的最小笔画宽度。如果 PDF 使用更细的笔画宽度，则会被此宽度替代。默认值为 0.5。该值以转换后的 PDF 页面用户空间单位表示。默认情况下 1 个用户空间单位等于 1/72 英寸（0.35 毫米），但 PDF 文档可以覆盖此设置。变换可能会影响生成的 SVG 中的实际最小宽度。 |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | 获取和设置一个选项，以严格检查子路径是否位于 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) 中指定的矩形内。如果设置为 false，则会提取未完全包含在该矩形内的子路径。默认值为 {@code True}。 |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | 获取和设置一个标志，以确定页面上找到的 XFrom 是否应解包。XFrom 元素可能会出现在不同的 SVG 文件中。只有由页面内容中的 Do 语句渲染的 XForm 会被解包。嵌套的 XForm 不会被解包。 |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | 获取和设置仅解包对应指定谓词的 XForm 的选项。 |
| [setAutoGrouping](#setAutoGrouping-boolean-) | 获取和设置自动将子路径分组为图像的选项。此选项排除 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) 选项。 |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | 获取和设置将 PDF 文档中的每个子路径提取为单独 SVG 图像的选项。 |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | 获取和设置定义 SVG 提取区域的边界矩形。 |
| [setGroupStrength](#setGroupStrength-double-) | 获取和设置子路径分组为图像的强度选项。允许您配置子路径分组的程度。取值范围为 0 到 1。值为 0 时对应启用 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) 选项。值为 1 时将在页面上为所有矢量路径创建单个图像。当 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) 为 false 时，此选项生效。默认值为 {@code 0.8}。 |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | 获取或设置生成的 SVG 中使用的最小笔画宽度。如果 PDF 使用更细的笔画宽度，则会被此宽度替代。默认值为 0.5。该值以转换后的 PDF 页面用户空间单位表示。默认情况下 1 个用户空间单位等于 1/72 英寸（0.35 毫米），但 PDF 文档可以覆盖此设置。变换可能会影响生成的 SVG 中的实际最小宽度。 |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | 获取和设置一个选项，以严格检查子路径是否位于 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) 中指定的矩形内。如果设置为 false，则会提取未完全包含在该矩形内的子路径。默认值为 {@code True}。 |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | 获取和设置一个标志，以确定页面上找到的 XFrom 是否应解包。XFrom 元素可能会出现在不同的 SVG 文件中。只有由页面内容中的 Do 语句渲染的 XForm 会被解包。嵌套的 XForm 不会被解包。 |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | 获取和设置仅解包对应指定谓词的 XForm 的选项。 |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

创建 SvgExtractionOptions 类的实例。

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

获取和设置自动将子路径分组为图像的选项。此选项排除 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) 选项。

**Returns:**
布尔值

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

获取和设置将 PDF 文档中的每个子路径提取为单独 SVG 图像的选项。

**Returns:**
布尔值

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

获取和设置定义 SVG 提取区域的边界矩形。

**Returns:**
Rectangle 实例

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

获取和设置子路径分组为图像的强度选项。允许您配置子路径分组的程度。取值范围为 0 到 1。值为 0 时对应启用 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) 选项。值为 1 时将在页面上为所有矢量路径创建单个图像。当 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) 为 false 时，此选项生效。默认值为 {@code 0.8}。

**Returns:**
double 值

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

获取或设置生成的 SVG 中使用的最小笔画宽度。如果 PDF 使用更细的笔画宽度，则会被此宽度替代。默认值为 0.5。该值以转换后的 PDF 页面用户空间单位表示。默认情况下 1 个用户空间单位等于 1/72 英寸（0.35 毫米），但 PDF 文档可以覆盖此设置。变换可能会影响生成的 SVG 中的实际最小宽度。

**Returns:**
double 值

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

获取和设置一个选项，以严格检查子路径是否位于 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) 中指定的矩形内。如果设置为 false，则会提取未完全包含在该矩形内的子路径。默认值为 {@code True}。

**Returns:**
布尔值

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

获取和设置一个标志，以确定页面上找到的 XFrom 是否应解包。XFrom 元素可能会出现在不同的 SVG 文件中。只有由页面内容中的 Do 语句渲染的 XForm 会被解包。嵌套的 XForm 不会被解包。

**Returns:**
布尔值

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

获取和设置仅解包对应指定谓词的 XForm 的选项。

**Returns:**
XFormPlacement 实例的内部 Predicate 实例

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

获取和设置自动将子路径分组为图像的选项。此选项排除 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) 选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

获取和设置将 PDF 文档中的每个子路径提取为单独 SVG 图像的选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
获取和设置定义 SVG 提取区域的边界矩形。

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

获取和设置子路径分组为图像的强度选项。允许您配置子路径分组的程度。取值范围为 0 到 1。值为 0 时对应启用 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) 选项。值为 1 时将在页面上为所有矢量路径创建单个图像。当 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) 为 false 时，此选项生效。默认值为 {@code 0.8}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

获取或设置生成的 SVG 中使用的最小笔画宽度。如果 PDF 使用更细的笔画宽度，则会被此宽度替代。默认值为 0.5。该值以转换后的 PDF 页面用户空间单位表示。默认情况下 1 个用户空间单位等于 1/72 英寸（0.35 毫米），但 PDF 文档可以覆盖此设置。变换可能会影响生成的 SVG 中的实际最小宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

获取和设置一个选项，以严格检查子路径是否位于 {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) 中指定的矩形内。如果设置为 false，则会提取未完全包含在该矩形内的子路径。默认值为 {@code True}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

获取和设置一个标志，以确定页面上找到的 XFrom 是否应解包。XFrom 元素可能会出现在不同的 SVG 文件中。只有由页面内容中的 Do 语句渲染的 XForm 会被解包。嵌套的 XForm 不会被解包。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
获取和设置仅解包对应指定谓词的 XForm 的选项。
