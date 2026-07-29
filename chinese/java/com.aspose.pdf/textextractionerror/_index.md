---
title: "TextExtractionError"
linktitle: "TextExtractionError"
second_title: "Aspose.PDF for Java API 参考"
description: "描述 PDF 文档中出现的文本提取错误。"
type: docs
weight: 5040
url: /zh/java/com.aspose.pdf/textextractionerror/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionError

```
public final class TextExtractionError extends Object
```

描述 PDF 文档中出现的文本提取错误。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDescription](#getDescription--) | 错误的扩展描述。 |
| [getExtractedText](#getExtractedText--) | 实际提取的文本。 |
| [getFontKey](#getFontKey--) | 用于显示导致提取错误的文本的 Font 对象的键（PDF 名称）。 |
| [getFontName](#getFontName--) | 用于显示导致提取错误的文本的 Font 对象的可读（内部）名称。 |
| [getLocation](#getLocation--) | 错误位置。 |
| [getSummary](#getSummary--) | 错误的简要描述。 |
| [toString](#toString--) | 返回字符串表示形式。 |

### getDescription {#getDescription--}
```
public String getDescription()
```

错误的扩展描述。

**Returns:**
字符串值

### getExtractedText {#getExtractedText--}
```
public String getExtractedText()
```

实际提取的文本。

**Returns:**
字符串值

### getFontKey {#getFontKey--}
```
public String getFontKey()
```

用于显示导致提取错误的文本的 Font 对象的键（PDF 名称）。

**Returns:**
字符串值

### getFontName {#getFontName--}
```
public String getFontName()
```

用于显示导致提取错误的文本的 Font 对象的可读（内部）名称。

**Returns:**
字符串值

### getLocation {#getLocation--}
```
public TextExtractionErrorLocation getLocation()
```

错误位置。

**Returns:**
TextExtractionErrorLocation 实例

### getSummary {#getSummary--}
```
public String getSummary()
```

错误的简要描述。

**Returns:**
字符串值

### toString {#toString--}
```
public String toString()
```

返回字符串表示形式。

**Returns:**
字符串表示形式
