---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档中出现文本提取错误的位置。"
type: docs
weight: 5050
url: /zh/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

表示 PDF 文档中出现文本提取错误的位置。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | 导致文本提取错误的操作符所使用的 PDF 字体对象的键（名称）。 |
| [getFormKey](#getFormKey--) | 内容流文本提取错误所在的 PDF 表单 XObject 的键（名称）。如果 ObjectType == 'xForm' 则不为空。 |
| [getObjectType](#getObjectType--) | 内容流文本提取错误所在的 PDF 对象（页面或 xForm）的类型。 |
| [getOperatorIndex](#getOperatorIndex--) | 导致文本提取错误的内容流（操作符集合）中显示文本的操作符索引。 |
| [getOperatorString](#getOperatorString--) | 导致文本提取错误的显示文本的操作符。 |
| [getPageNumber](#getPageNumber--) | 文本提取错误所在的文档页号。 |
| [getPath](#getPath--) | 文本提取错误出现的 PDF 文档位置。 |
| [getTextStartPoint](#getTextStartPoint--) | 导致文本提取错误的操作符所使用的 PDF 字体对象的键（名称）。 |
| [toString](#toString--) | 返回字符串表示形式。 |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

导致文本提取错误的操作符所使用的 PDF 字体对象的键（名称）。

**Returns:**
字符串值

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

内容流文本提取错误所在的 PDF 表单 XObject 的键（名称）。如果 ObjectType == 'xForm' 则不为空。

**Returns:**
字符串值

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

内容流文本提取错误所在的 PDF 对象（页面或 xForm）的类型。

**Returns:**
字符串值

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

导致文本提取错误的内容流（操作符集合）中显示文本的操作符索引。

**Returns:**
int 值

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

导致文本提取错误的显示文本的操作符。

**Returns:**
字符串值

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

文本提取错误所在的文档页号。

**Returns:**
int 值

### getPath {#getPath--}
```
public String getPath()
```

文本提取错误出现的 PDF 文档位置。

**Returns:**
字符串值

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

导致文本提取错误的操作符所使用的 PDF 字体对象的键（名称）。

**Returns:**
Point 实例

### toString {#toString--}
```
public String toString()
```

返回字符串表示形式。

**Returns:**
字符串表示形式。
