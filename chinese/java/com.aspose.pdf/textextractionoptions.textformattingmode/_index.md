---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Aspose.PDF for Java API 参考"
description: "定义在将 PDF 文档转换为文本时可使用的不同模式。参见 {@code TextDevice} 类。"
type: docs
weight: 5070
url: /zh/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

定义在将 PDF 文档转换为文本时可使用的不同模式。参见 {@code TextDevice} 类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Flatten](#Flatten) | 通过其坐标使用定位文本片段来表示 pdf 内容。它基本上类似于 "Raw" 模式。但当 "Raw" 侧重于保留文档中文本片段（运算符）的结构时，"Flatten" 则侧重于保持文本的读取顺序。 |
| [MemorySaving](#MemorySaving) | 使用节省内存的提取。它几乎与 'Raw' 模式相同，但运行稍快且使用更少的内存。 |
| [Pure](#Pure) | 使用少量格式化例程来表示 pdf 内容。 |
| [Raw](#Raw) | 按原样表示 pdf 内容，即不进行格式化。 |

### Flatten {#Flatten}
```
public static final int Flatten
```

通过其坐标使用定位文本片段来表示 pdf 内容。它基本上类似于 "Raw" 模式。但当 "Raw" 侧重于保留文档中文本片段（运算符）的结构时，"Flatten" 则侧重于保持文本的读取顺序。

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

使用节省内存的提取。它几乎与 'Raw' 模式相同，但运行稍快且使用更少的内存。

### Pure {#Pure}
```
public static final int Pure
```

使用少量格式化例程来表示 pdf 内容。

### Raw {#Raw}
```
public static final int Raw
```

按原样表示 pdf 内容，即不进行格式化。
