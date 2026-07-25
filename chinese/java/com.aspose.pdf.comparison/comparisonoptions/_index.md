---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档比较选项类。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

表示 PDF 文档比较选项类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | 创建一个 {@link ComparisonOptions} 类实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | 获取并设置编辑操作顺序。 |
| [getExcludeAreas1](#getExcludeAreas1--) | 获取并设置排除区域。用于比较方法中的第一页或文档。此选项可以与 {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) 一起设置。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。 |
| [getExcludeAreas2](#getExcludeAreas2--) | 获取并设置排除区域。用于比较方法中的第二页或文档。此选项可以与 {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) 一起设置。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。 |
| [getExtractionArea](#getExtractionArea--) | 获取并设置页面文本比较的矩形区域。此选项不能与 {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) 和 { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) 选项一起设置。 |
| [isExcludeTables](#isExcludeTables--) | 获取并设置决定是否在比较中排除表格的选项。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。默认值为 {@code false}。 |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | 获取并设置编辑操作顺序。 |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | 获取并设置排除区域。用于比较方法中的第一页或文档。此选项可以与 {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) 一起设置。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。 |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | 获取并设置排除区域。用于比较方法中的第二页或文档。此选项可以与 {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) 一起设置。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。 |
| [setExcludeTables](#setExcludeTables-boolean-) | 获取并设置决定是否在比较中排除表格的选项。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。默认值为 {@code false}。 |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | 获取并设置页面文本比较的矩形区域。此选项不能与 {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) 和 { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) 选项一起设置。 |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

创建一个 {@link ComparisonOptions} 类实例。

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

获取并设置编辑操作顺序。

**Returns:**
EditOperationsOrder 元素

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

获取并设置排除区域。用于比较方法中的第一页或文档。此选项可以与 {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) 一起设置。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。

**Returns:**
Rectangle 实例数组

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

获取并设置排除区域。用于比较方法中的第二页或文档。此选项可以与 {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) 一起设置。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。

**Returns:**
Rectangle 实例数组

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

获取并设置页面文本比较的矩形区域。此选项不能与 {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) 和 { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) 选项一起设置。

**Returns:**
Rectangle 实例

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

获取并设置决定是否在比较中排除表格的选项。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。默认值为 {@code false}。

**Returns:**
布尔值

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
获取并设置编辑操作顺序。

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
获取并设置排除区域。用于比较方法中的第一页或文档。此选项可以与 {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) 一起设置。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
获取并设置排除区域。用于比较方法中的第二页或文档。此选项可以与 {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}) 一起设置。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

获取并设置决定是否在比较中排除表格的选项。此选项不能与 {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) 选项一起设置。默认值为 {@code false}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
获取并设置页面文本比较的矩形区域。此选项不能与 {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) 和 { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) 选项一起设置。
