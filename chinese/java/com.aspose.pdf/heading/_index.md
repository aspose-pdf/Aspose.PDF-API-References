---
title: "Heading"
linktitle: "Heading"
second_title: "Aspose.PDF for Java API 参考"
description: "表示标题。"
type: docs
weight: 1890
url: /zh/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

表示标题。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Heading](#Heading--) | 仅供内部使用 |
| [Heading](#Heading-int-) | 初始化 Cell 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | 克隆包含所有段的标题。 |
| [deepClone](#deepClone--) | 克隆标题。 |
| [getDestinationPage](#getDestinationPage--) | 获取目标页面。 |
| [getLevel](#getLevel--) | 获取级别。 |
| [getStartNumber](#getStartNumber--) | 获取标题起始编号。 |
| [getStyle](#getStyle--) | 获取或设置样式。 |
| [getTocPage](#getTocPage--) | 获取包含此标题的页面。 |
| [getTop](#getTop--) | 获取此标题的顶部 Y 坐标（供内部使用）。 |
| [getUserLabel](#getUserLabel--) | 获取或设置用户标签。 |
| [isAutoSequence](#isAutoSequence--) | 获取标题是否应自动编号。 |
| [isInList](#isInList--) | 获取标题是否应在目录列表中。 |
| [setAutoSequence](#setAutoSequence-boolean-) | 设置标题是否应自动编号。 |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | 设置目标页面。 |
| [setInList](#setInList-boolean-) | 设置标题是否应在目录列表中。 |
| [setLevel](#setLevel-int-) | 设置级别。 |
| [setStartNumber](#setStartNumber-int-) | 获取标题起始编号。值：The startNumber。 |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | 设置或设置样式。 |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | 设置包含此标题的页面。 |
| [setTop](#setTop-double-) | 设置此标题的顶部 Y（供内部使用）。 |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | 获取或设置用户标签。 |

### Heading {#Heading--}
```
public Heading()
```

仅供内部使用

### Heading {#Heading-int-}
```
public Heading(int level)
```

初始化 Cell 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level |  | 标题的级别。 |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

克隆包含所有段的标题。

**Returns:**
克隆的对象。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆标题。

**Returns:**
克隆的对象。

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

获取目标页面。

**Returns:**
目标页面。

### getLevel {#getLevel--}
```
public int getLevel()
```

获取级别。

**Returns:**
标题级别。

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

获取标题起始编号。

**Returns:**
值：The startNumber。

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

获取或设置样式。

**Returns:**
标题样式。

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

获取包含此标题的页面。

**Returns:**
页面。

### getTop {#getTop--}
```
public double getTop()
```

获取此标题的顶部 Y 坐标（供内部使用）。

**Returns:**
顶部 Y 值

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

获取或设置用户标签。

**Returns:**
TextSegment 对象

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

获取标题是否应自动编号。

**Returns:**
该 IsAutoSequens。

### isInList {#isInList--}
```
public boolean isInList()
```

获取标题是否应在目录列表中。

**Returns:**
该 IsInList。

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

设置标题是否应自动编号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 该 IsAutoSequens。 |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
设置目标页面。

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

设置标题是否应在目录列表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 该 IsInList。 |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

设置级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 标题级别。 |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

获取标题起始编号。值：The startNumber。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 该 startNumber。 |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
设置或设置样式。

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
设置包含此标题的页面。

### setTop {#setTop-double-}
```
public void setTop(double value)
```

设置此标题的顶部 Y（供内部使用）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 顶部 Y 值 |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
获取或设置用户标签。
