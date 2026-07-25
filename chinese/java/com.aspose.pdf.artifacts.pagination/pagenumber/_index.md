---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Aspose.PDF for Java API 参考"
description: "表示包含页码、总页数和分隔符的页码格式。"
type: docs
weight: 150
url: /zh/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

表示包含页码、总页数和分隔符的页码格式。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDelimiter](#getDelimiter--) | 获取或设置页面编号格式中使用的分隔符。格式化后的字符串将根据指定的分隔符进行更新。 |
| [getIndex](#getIndex--) | 获取或设置页面编号格式中的页索引组件。格式化后的字符串将包含页索引的占位符。 |
| [getOffset](#getOffset--) | 获取或设置要添加到页索引的偏移量。 |
| [getPageNumberString](#getPageNumberString-int-int-) | 返回基于当前设置的页面编号的格式化字符串。 |
| [getTotalNum](#getTotalNum--) | 获取或设置页面编号格式中的总页数组件。格式化后的字符串将包含总页数的占位符。 |
| [setDelimiter](#setDelimiter-java.lang.String-) | 获取或设置页面编号格式中使用的分隔符。格式化后的字符串将根据指定的分隔符进行更新。 |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | 获取或设置页面编号格式中的页索引组件。 |
| [setOffset](#setOffset-int-) | 获取或设置要添加到页索引的偏移量。 |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | 获取或设置页面编号格式中的总页数组件。 |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

获取或设置页面编号格式中使用的分隔符。格式化后的字符串将根据指定的分隔符进行更新。

**Returns:**
字符串值

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

获取或设置页面编号格式中的页索引组件。格式化后的字符串将包含页索引的占位符。

**Returns:**
PageIndex 实例

### getOffset {#getOffset--}
```
public final int getOffset()
```

获取或设置要添加到页索引的偏移量。

**Returns:**
int 值

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

返回基于当前设置的页面编号的格式化字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 当前页码。 |
| 计数 |  | 总页数。 |

**Returns:**
格式化的页码字符串。

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

获取或设置页面编号格式中的总页数组件。格式化后的字符串将包含总页数的占位符。

**Returns:**
PageTotalNum 实例

### setDelimiter {#setDelimiter-java.lang.String-}
获取或设置页面编号格式中使用的分隔符。格式化后的字符串将根据指定的分隔符进行更新。

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
获取或设置页面编号格式中的页索引组件。

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

获取或设置要添加到页索引的偏移量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
获取或设置页面编号格式中的总页数组件。
