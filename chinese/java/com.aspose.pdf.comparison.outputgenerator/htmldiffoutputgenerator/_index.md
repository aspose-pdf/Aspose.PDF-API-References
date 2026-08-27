---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于生成文本差异 HTML 表示的类。已删除的换行通过 - 段落标记表示。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

表示用于生成文本差异 HTML 表示的类。已删除的换行通过 - 段落标记表示。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | 创建 {@link HtmlDiffOutputGenerator} 类的实例。 |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | 创建 {@link HtmlDiffOutputGenerator} 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [generateOutput1](#generateOutput1-java.util.List-) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | 内部方法 |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | 获取和设置删除操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | 获取和设置相等操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | 获取和设置插入操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | 获取或设置删除操作的 text-decoration: line-through 样式。默认值为 {@code False}。 |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | 获取和设置删除操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | 获取和设置相等操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | 获取和设置插入操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | 获取或设置删除操作的 text-decoration: line-through 样式。默认值为 {@code False}。 |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

创建 {@link HtmlDiffOutputGenerator} 类的实例。

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
创建 {@link HtmlDiffOutputGenerator} 类的实例。

### generateOutput {#generateOutput-java.util.List-}
根据文本之间的差异生成输出并将其保存到文件中。

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
根据文本之间的差异生成输出并将其保存到文件中。

### generateOutput1 {#generateOutput1-java.util.List-}
根据文本之间的差异生成输出并将其保存到文件中。

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
根据文本之间的差异生成输出并将其保存到文件中。

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
内部方法

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

获取和设置删除操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66;

**Returns:**
字符串值

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

获取和设置相等操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66;

**Returns:**
字符串值

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

获取和设置插入操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66;

**Returns:**
字符串值

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

获取或设置删除操作的 text-decoration: line-through 样式。默认值为 {@code False}。

**Returns:**
布尔值

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
获取和设置删除操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
获取和设置相等操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
获取和设置插入操作的 CSS 样式字符串。示例：color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

获取或设置删除操作的 text-decoration: line-through 样式。默认值为 {@code False}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
