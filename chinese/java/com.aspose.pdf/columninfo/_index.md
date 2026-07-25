---
title: "ColumnInfo"
linktitle: "ColumnInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "此类表示列的信息。"
type: docs
weight: 730
url: /zh/java/com.aspose.pdf/columninfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ColumnInfo

```
public final class ColumnInfo extends Object
```

此类表示列的信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColumnInfo](#ColumnInfo--) | 初始化 ColumnInfo 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getColumnCount](#getColumnCount--) | 获取指示列数的整数值。 |
| [getColumnSpacing](#getColumnSpacing--) | <p> 获取或设置一个包含列间距的字符串。每个间距的数值应以空格分隔。默认单位是点（point），但也支持厘米（cm）和英寸（inch）。例如，\"120 2.5cm 1.5inch\"。 </p><hr> <p> 如果未设置此属性，将对每个间距使用默认值 0。 </p> |
| [getColumnWidths](#getColumnWidths--) | 获取或设置一个包含列宽的字符串。每列的数值应以空格分隔。默认单位是点（point），但也支持厘米（cm）、英寸（inch）以及可用宽度的百分比。例如，\"120 2.5cm 1.5inch\" |
| [setColumnCount](#setColumnCount-int-) | 设置指示列数的整数值。 |
| [setColumnSpacing](#setColumnSpacing-java.lang.String-) | <p> 获取或设置一个包含列间距的字符串。每个间距的数值应以空格分隔。默认单位是点（point），但也支持厘米（cm）和英寸（inch）。例如，\"120 2.5cm 1.5inch\"。 </p><hr> <p> 如果未设置此属性，将对每个间距使用默认值 0。 </p> |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | 获取或设置一个包含列宽的字符串。每列的数值应以空格分隔。默认单位是点（point），但也支持厘米（cm）、英寸（inch）以及可用宽度的百分比。例如，\"120 2.5cm 1.5inch\" |

### ColumnInfo {#ColumnInfo--}
```
public ColumnInfo()
```

初始化 ColumnInfo 类的新实例。

### getColumnCount {#getColumnCount--}
```
public int getColumnCount()
```

获取指示列数的整数值。

**Returns:**
列计数

### getColumnSpacing {#getColumnSpacing--}
```
public String getColumnSpacing()
```

<p> 获取或设置一个包含列间距的字符串。每个间距的数值应以空格分隔。默认单位是点（point），但也支持厘米（cm）和英寸（inch）。例如，\"120 2.5cm 1.5inch\"。 </p><hr> <p> 如果未设置此属性，将对每个间距使用默认值 0。 </p>

**Returns:**
字符串值

### getColumnWidths {#getColumnWidths--}
```
public String getColumnWidths()
```

获取或设置一个包含列宽的字符串。每列的数值应以空格分隔。默认单位是点（point），但也支持厘米（cm）、英寸（inch）以及可用宽度的百分比。例如，\"120 2.5cm 1.5inch\"

**Returns:**
字符串值

### setColumnCount {#setColumnCount-int-}
```
public void setColumnCount(int value)
```

设置指示列数的整数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 列计数 |

### setColumnSpacing {#setColumnSpacing-java.lang.String-}
<p> 获取或设置一个包含列间距的字符串。每个间距的数值应以空格分隔。默认单位是点（point），但也支持厘米（cm）和英寸（inch）。例如，\"120 2.5cm 1.5inch\"。 </p><hr> <p> 如果未设置此属性，将对每个间距使用默认值 0。 </p>

### setColumnWidths {#setColumnWidths-java.lang.String-}
获取或设置一个包含列宽的字符串。每列的数值应以空格分隔。默认单位是点（point），但也支持厘米（cm）、英寸（inch）以及可用宽度的百分比。例如，\"120 2.5cm 1.5inch\"
