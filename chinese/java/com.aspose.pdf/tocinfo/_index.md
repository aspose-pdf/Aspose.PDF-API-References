---
title: "TocInfo"
linktitle: "TocInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示目录信息。"
type: docs
weight: 5370
url: /zh/java/com.aspose.pdf/tocinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TocInfo

```
public final class TocInfo extends Object
```

表示目录信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TocInfo](#TocInfo--) | 初始化 {@code TocInfo} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getColumnInfo](#getColumnInfo--) | 获取列信息。 |
| [getCopyToOutlines](#getCopyToOutlines--) | 获取或设置是否将 TOC 复制到大纲。 |
| [getFormatArray](#getFormatArray--) | 获取目录的格式数组。 |
| [getFormatArrayLength](#getFormatArrayLength--) | 获取格式数组长度 |
| [getLevelIndentation](#getLevelIndentation--) | 获取级别缩进 |
| [getLineDash](#getLineDash--) | 获取或设置 TOC 线条虚线。 |
| [getPageNumbersPrefix](#getPageNumbersPrefix--) | 获取是否在页码前有前缀。 |
| [getTitle](#getTitle--) | 获取目录标题。 |
| [isCountTocPages](#isCountTocPages--) | 获取是否计数或已通过的目录页数。 |
| [isShowPageNumbers](#isShowPageNumbers--) | 获取是否在目录中显示页码。 |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | 设置列信息。 |
| [setCopyToOutlines](#setCopyToOutlines-boolean-) | 获取或设置是否将 TOC 复制到大纲。 |
| [setCountTocPages](#setCountTocPages-boolean-) | 设置是否计数或已通过的目录页数。 |
| [setFormatArray](#setFormatArray-com.aspose.pdf.LevelFormat:A-) | 设置目录的格式数组。 |
| [setFormatArrayLength](#setFormatArrayLength-int-) | 设置格式数组长度 |
| [setLevelIndentation](#setLevelIndentation-int-) | 设置级别缩进 |
| [setLineDash](#setLineDash-int-) | 获取或设置 TOC 线条虚线。 |
| [setPageNumbersPrefix](#setPageNumbersPrefix-java.lang.String-) | 设置是否在页码前有前缀。 |
| [setShowPageNumbers](#setShowPageNumbers-boolean-) | 设置是否在目录中显示页码。 |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | 设置目录标题。 |

### TocInfo {#TocInfo--}
```
public TocInfo()
```

初始化 {@code TocInfo} 类的新实例。

### getColumnInfo {#getColumnInfo--}
```
public final ColumnInfo getColumnInfo()
```

获取列信息。

**Returns:**
ColumnInfo 实例

### getCopyToOutlines {#getCopyToOutlines--}
```
public final boolean getCopyToOutlines()
```

获取或设置是否将 TOC 复制到大纲。

**Returns:**
布尔值

### getFormatArray {#getFormatArray--}
```
public final LevelFormat [] getFormatArray()
```

获取目录的格式数组。

**Returns:**
LevelFormat 数组

### getFormatArrayLength {#getFormatArrayLength--}
```
public final int getFormatArrayLength()
```

获取格式数组长度

**Returns:**
布尔值

### getLevelIndentation {#getLevelIndentation--}
```
public int getLevelIndentation()
```

获取级别缩进

**Returns:**
int 值

### getLineDash {#getLineDash--}
```
public final int getLineDash()
```

获取或设置 TOC 线条虚线。

**Returns:**
TabLeaderType 值

### getPageNumbersPrefix {#getPageNumbersPrefix--}
```
public final String getPageNumbersPrefix()
```

获取是否在页码前有前缀。

**Returns:**
字符串值

### getTitle {#getTitle--}
```
public final TextFragment getTitle()
```

获取目录标题。

**Returns:**
TextFragment 实例

### isCountTocPages {#isCountTocPages--}
```
public final boolean isCountTocPages()
```

获取是否计数或已通过的目录页数。

**Returns:**
布尔值

### isShowPageNumbers {#isShowPageNumbers--}
```
public final boolean isShowPageNumbers()
```

获取是否在目录中显示页码。

**Returns:**
布尔值

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
设置列信息。

### setCopyToOutlines {#setCopyToOutlines-boolean-}
```
public final void setCopyToOutlines(boolean value)
```

获取或设置是否将 TOC 复制到大纲。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCountTocPages {#setCountTocPages-boolean-}
```
public final void setCountTocPages(boolean value)
```

设置是否计数或已通过的目录页数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFormatArray {#setFormatArray-com.aspose.pdf.LevelFormat:A-}
设置目录的格式数组。

### setFormatArrayLength {#setFormatArrayLength-int-}
```
public final void setFormatArrayLength(int value)
```

设置格式数组长度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLevelIndentation {#setLevelIndentation-int-}
```
public void setLevelIndentation(int value)
```

设置级别缩进

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setLineDash {#setLineDash-int-}
```
public final void setLineDash(int value)
```

获取或设置 TOC 线条虚线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | TabLeaderType 值 |

### setPageNumbersPrefix {#setPageNumbersPrefix-java.lang.String-}
设置是否在页码前有前缀。

### setShowPageNumbers {#setShowPageNumbers-boolean-}
```
public final void setShowPageNumbers(boolean value)
```

设置是否在目录中显示页码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
设置目录标题。
