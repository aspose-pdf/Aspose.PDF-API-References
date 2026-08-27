---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于比较文档并生成并排输出的选项类。"
type: docs
weight: 60
url: /zh/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

表示用于比较文档并生成并排输出的选项类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | 创建一个 {@link SideBySideComparisonOptions} 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | 获取并设置决定是否显示额外更改标记的属性。设置后，会显示不在当前页但存在于其他页的更改标记。如果更改位于单词之间，标记可能无法相对于空白字符精确定位。默认值为 {@code false}。 |
| [getComparisonArea1](#getComparisonArea1--) | 获取并设置比较区域。用于比较方法中的第一页或文档。此选项不能与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）、{@code ExcludeAreas1}（{@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) 和 {@code ExcludeAreas2}（{@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) 选项同时设置。 |
| [getComparisonArea2](#getComparisonArea2--) | 获取并设置比较区域。用于比较方法中的第二页或文档。此选项不能与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）、{@code ExcludeAreas1}（{@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) 和 {@code ExcludeAreas2}（{@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) 选项同时设置。 |
| [getComparisonMode](#getComparisonMode--) | 获取并设置比较模式。默认值为 {@link ComparisonMode#IgnoreSpaces}。 |
| [getDeleteColor](#getDeleteColor--) | 获取在并排比较期间用于标记已删除内容的颜色。此属性定义比较结果中删除内容的可视化表示。 |
| [getExcludeAreas1](#getExcludeAreas1--) | 获取并设置排除区域。用于比较方法中的第一页或文档。此选项可以与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）一起设置。此选项不能与 {@code ComparisonArea1}（{@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) 选项同时设置。 |
| [getExcludeAreas2](#getExcludeAreas2--) | 获取并设置排除区域。用于比较方法中的第二页或文档。此选项可以与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）一起设置。此选项不能与 {@code ComparisonArea2}（{@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) 选项同时设置。 |
| [getExcludeTables](#getExcludeTables--) | 获取并设置决定是否在比较中排除表格的选项。此选项不能与 {@code ComparisonArea1}（{@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) 和 {@code ComparisonArea2}（{@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) 同时设置。默认值为 {@code false}。 |
| [getInsertColor](#getInsertColor--) | 获取在并排比较期间用于标记插入内容的颜色。此属性定义比较结果中插入内容的可视化表示。 |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | 获取并设置决定是否显示额外更改标记的属性。设置后，会显示不在当前页但存在于其他页的更改标记。如果更改位于单词之间，标记可能无法相对于空白字符精确定位。默认值为 {@code false}。 |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | 获取并设置比较区域。用于比较方法中的第一页或文档。此选项不能与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）、{@code ExcludeAreas1}（{@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) 和 {@code ExcludeAreas2}（{@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) 选项同时设置。 |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | 获取并设置比较区域。用于比较方法中的第二页或文档。此选项不能与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）、{@code ExcludeAreas1}（{@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) 和 {@code ExcludeAreas2}（{@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) 选项同时设置。 |
| [setComparisonMode](#setComparisonMode-int-) | 获取并设置比较模式。默认值为 {@link ComparisonMode#IgnoreSpaces}。 |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | 设置在并排比较期间用于标记已删除内容的颜色。此属性定义比较结果中删除内容的可视化表示。 |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | 获取并设置排除区域。用于比较方法中的第一页或文档。此选项可以与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）一起设置。此选项不能与 {@code ComparisonArea1}（{@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) 选项同时设置。 |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | 获取并设置排除区域。用于比较方法中的第二页或文档。此选项可以与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）一起设置。此选项不能与 {@code ComparisonArea2}（{@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) 选项同时设置。 |
| [setExcludeTables](#setExcludeTables-boolean-) | 获取并设置决定是否在比较中排除表格的选项。此选项不能与 {@code ComparisonArea1}（{@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) 和 {@code ComparisonArea2}（{@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) 同时设置。默认值为 {@code false}。 |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | 设置在并排比较期间用于标记插入内容的颜色。此属性定义比较结果中插入的可视化表示。 |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

创建一个 {@link SideBySideComparisonOptions} 类的实例。

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

获取并设置决定是否显示额外更改标记的属性。设置后，会显示不在当前页但存在于其他页的更改标记。如果更改位于单词之间，标记可能无法相对于空白字符精确定位。默认值为 {@code false}。

**Returns:**
布尔值

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

获取并设置比较区域。用于比较方法中的第一页或文档。此选项不能与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）、{@code ExcludeAreas1}（{@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) 和 {@code ExcludeAreas2}（{@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) 选项同时设置。

**Returns:**
Rectangle 实例

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

获取并设置比较区域。用于比较方法中的第二页或文档。此选项不能与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）、{@code ExcludeAreas1}（{@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) 和 {@code ExcludeAreas2}（{@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) 选项同时设置。

**Returns:**
Rectangle 实例

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

获取并设置比较模式。默认值为 {@link ComparisonMode#IgnoreSpaces}。

**Returns:**
ComparisonMode 元素

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

获取在并排比较期间用于标记已删除内容的颜色。此属性定义比较结果中删除内容的可视化表示。

**Returns:**
在并排比较期间用于标记删除内容的颜色。

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

获取并设置排除区域。用于比较方法中的第一页或文档。此选项可以与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）一起设置。此选项不能与 {@code ComparisonArea1}（{@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) 选项同时设置。

**Returns:**
Rectangle 实例数组

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

获取并设置排除区域。用于比较方法中的第二页或文档。此选项可以与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）一起设置。此选项不能与 {@code ComparisonArea2}（{@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) 选项同时设置。

**Returns:**
Rectangle 实例数组

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

获取并设置决定是否在比较中排除表格的选项。此选项不能与 {@code ComparisonArea1}（{@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) 和 {@code ComparisonArea2}（{@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) 同时设置。默认值为 {@code false}。

**Returns:**
布尔值

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

获取在并排比较期间用于标记插入内容的颜色。此属性定义比较结果中插入内容的可视化表示。

**Returns:**
在并排比较期间用于标记插入内容的颜色。

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

获取并设置决定是否显示额外更改标记的属性。设置后，会显示不在当前页但存在于其他页的更改标记。如果更改位于单词之间，标记可能无法相对于空白字符精确定位。默认值为 {@code false}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
获取并设置比较区域。用于比较方法中的第一页或文档。此选项不能与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）、{@code ExcludeAreas1}（{@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) 和 {@code ExcludeAreas2}（{@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) 选项同时设置。

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
获取并设置比较区域。用于比较方法中的第二页或文档。此选项不能与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）、{@code ExcludeAreas1}（{@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) 和 {@code ExcludeAreas2}（{@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) 选项同时设置。

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

获取并设置比较模式。默认值为 {@link ComparisonMode#IgnoreSpaces}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ComparisonMode 元素 |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
设置在并排比较期间用于标记已删除内容的颜色。此属性定义比较结果中删除内容的可视化表示。

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
获取并设置排除区域。用于比较方法中的第一页或文档。此选项可以与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）一起设置。此选项不能与 {@code ComparisonArea1}（{@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) 选项同时设置。

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
获取并设置排除区域。用于比较方法中的第二页或文档。此选项可以与 {@code ExcludeTables}（{@link #getExcludeTables}/{@link #setExcludeTables(boolean)}）一起设置。此选项不能与 {@code ComparisonArea2}（{@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) 选项同时设置。

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

获取并设置决定是否在比较中排除表格的选项。此选项不能与 {@code ComparisonArea1}（{@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) 和 {@code ComparisonArea2}（{@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) 同时设置。默认值为 {@code false}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
设置在并排比较期间用于标记插入内容的颜色。此属性定义比较结果中插入的可视化表示。

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
