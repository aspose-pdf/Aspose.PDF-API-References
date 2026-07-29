---
title: "字段"
linktitle: "字段"
second_title: "Aspose.PDF for Java API 参考"
description: "Acro 表单字段的基类。"
type: docs
weight: 1380
url: /zh/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Acro 表单字段的基类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | 在生成器中创建字段以供使用。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | 将此字段的子字段复制到数组中，从指定索引开始。 |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | 将此字段的子字段复制到数组中，从指定索引开始。 |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | 为该字段执行指定的 JavaScript 操作。 |
| [flatten](#flatten--) | 移除此字段并将其值直接放置在页面上。 |
| [get_Item](#get_Item-int-) | 通过索引获取此字段中包含的子字段。 |
| [get_Item](#get_Item-java.lang.String-) | 通过子字段名称获取此字段中包含的子字段。 |
| [getAlternateName](#getAlternateName--) | 获取字段的备用名称（在用户界面中识别字段时，用于替代实际字段名称的备用字段名称）。备用名称在 Adobe Acrobat 中用作字段工具提示。 |
| [getAnnotationIndex](#getAnnotationIndex--) | 获取此批注在页面上的索引。 |
| [getMappingName](#getMappingName--) | 获取在导出文档的交互式表单字段数据时应使用的字段映射名称。 |
| [getMaxFontSize](#getMaxFontSize--) | 字段内容可使用的最大字体大小。-1 表示不检查大小。 |
| [getMinFontSize](#getMinFontSize--) | 字段内容可使用的最小字体大小。-1 表示不检查大小。 |
| [getPageIndex](#getPageIndex--) | 获取包含此字段的页面索引。 |
| [getPartialName](#getPartialName--) | 获取字段的部分名称。 |
| [getRect](#getRect--) | 获取字段的矩形区域。 |
| [getSyncRoot](#getSyncRoot--) | 同步对象。 |
| [getTabOrder](#getTabOrder--) | 获取或设置字段的制表顺序。 |
| [getValue](#getValue--) | 获取字段的值。 |
| [isFitIntoRectangle](#isFitIntoRectangle--) | 如果为 true，则字体大小将缩小以适应指定的矩形区域。 |
| [isGroup](#isGroup--) | 获取布尔值，以指示此字段是否为非终端字段，即字段组。 |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | 用于 Generator 支持的属性。当字段添加到页眉或页脚时使用。如果为 true，则此字段仅创建一次，其外观将在文档的所有页面上可见。如果为 false，则为文档的每一页创建单独的字段。 |
| [isSynchronized](#isSynchronized--) | 如果字典已同步则返回 true。 |
| [iterator](#iterator--) | 返回包含字段的枚举器。 |
| [recalculate](#recalculate--) | 重新计算表单上所有计算字段。 |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | 设置字段的备用名称（在用户界面中识别字段时，用于替代实际字段名称的备用字段名称）。备用名称在 Adobe Acrobat 中用作字段工具提示。 |
| [setAnnotationIndex](#setAnnotationIndex-int-) | 设置此批注在页面上的索引。 |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | 如果为 true，则字体大小将缩小以适应指定的矩形区域。 |
| [setMappingName](#setMappingName-java.lang.String-) | 设置在导出文档的交互式表单字段数据时应使用的字段映射名称。 |
| [setMaxFontSize](#setMaxFontSize-double-) | 字段内容可使用的最大字体大小。-1 表示不检查大小。 |
| [setMinFontSize](#setMinFontSize-double-) | 字段内容可使用的最小字体大小。-1 表示不检查大小。 |
| [setPartialName](#setPartialName-java.lang.String-) | 设置字段的部分名称。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | 设置字段的位置。 |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | 设置字段的矩形区域。 |
| [setSharedField](#setSharedField-boolean-) | 用于 Generator 支持的属性。当字段添加到页眉或页脚时使用。如果为 true，则此字段仅创建一次，其外观将在文档的所有页面上可见。如果为 false，则为文档的每一页创建单独的字段。 |
| [setTabOrder](#setTabOrder-int-) | 获取或设置字段的制表顺序。 |
| [setValue](#setValue-java.lang.String-) | 设置值。 |
| [size](#size--) | 获取此字段中子字段的数量。（例如单选按钮字段中的项目数）。 |
| [updateAppearances](#updateAppearances--) | 更新外观值。 |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
在生成器中创建字段以供使用。

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
将此字段的子字段复制到数组中，从指定索引开始。

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
将此字段的子字段复制到数组中，从指定索引开始。

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
为该字段执行指定的 JavaScript 操作。

### flatten {#flatten--}
```
public void flatten()
```

移除此字段并将其值直接放置在页面上。

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

通过索引获取此字段中包含的子字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 请求的子字段索引。 |

**Returns:**
字段实例。

### get_Item {#get_Item-java.lang.String-}
通过子字段名称获取此字段中包含的子字段。

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

获取字段的备用名称（在用户界面中识别字段时，用于替代实际字段名称的备用字段名称）。备用名称在 Adobe Acrobat 中用作字段工具提示。

**Returns:**
字符串值

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

获取此批注在页面上的索引。

**Returns:**
int 值

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

获取在导出文档的交互式表单字段数据时应使用的字段映射名称。

**Returns:**
字符串值

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

字段内容可使用的最大字体大小。-1 表示不检查大小。

**Returns:**
double 值

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

字段内容可使用的最小字体大小。-1 表示不检查大小。

**Returns:**
double 值

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

获取包含此字段的页面索引。

**Returns:**
int 值

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

获取字段的部分名称。

**Returns:**
字符串值

### getRect {#getRect--}
```
public Rectangle getRect()
```

获取字段的矩形区域。

**Returns:**
字段矩形。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

同步对象。

**Returns:**
对象值

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

获取或设置字段的制表顺序。

**Returns:**
int 值

### getValue {#getValue--}
```
public String getValue()
```

获取字段的值。

**Returns:**
字符串值

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

如果为 true，则字体大小将缩小以适应指定的矩形区域。

**Returns:**
布尔值

### isGroup {#isGroup--}
```
public boolean isGroup()
```

获取布尔值，以指示此字段是否为非终端字段，即字段组。

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

用于 Generator 支持的属性。当字段添加到页眉或页脚时使用。如果为 true，则此字段仅创建一次，其外观将在文档的所有页面上可见。如果为 false，则为文档的每一页创建单独的字段。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

如果字典已同步则返回 true。

**Returns:**
布尔值

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

返回包含字段的枚举器。

**Returns:**
Enumerator 对象。

### recalculate {#recalculate--}
```
public boolean recalculate()
```

重新计算表单上所有计算字段。

**Returns:**
如果在重新计算期间字段值已更改，则为 true。

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
设置字段的备用名称（在用户界面中识别字段时，用于替代实际字段名称的备用字段名称）。备用名称在 Adobe Acrobat 中用作字段工具提示。

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

设置此批注在页面上的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

如果为 true，则字体大小将缩小以适应指定的矩形区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMappingName {#setMappingName-java.lang.String-}
设置在导出文档的交互式表单字段数据时应使用的字段映射名称。

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

字段内容可使用的最大字体大小。-1 表示不检查大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

字段内容可使用的最小字体大小。-1 表示不检查大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setPartialName {#setPartialName-java.lang.String-}
设置字段的部分名称。

### setPosition {#setPosition-com.aspose.pdf.Point-}
设置字段的位置。

### setRect {#setRect-com.aspose.pdf.Rectangle-}
设置字段的矩形区域。

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

用于 Generator 支持的属性。当字段添加到页眉或页脚时使用。如果为 true，则此字段仅创建一次，其外观将在文档的所有页面上可见。如果为 false，则为文档的每一页创建单独的字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

获取或设置字段的制表顺序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setValue {#setValue-java.lang.String-}
设置值。

### size {#size--}
```
public int size()
```

获取此字段中子字段的数量。（例如单选按钮字段中的项目数）。

**Returns:**
int 值

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

更新外观值。
