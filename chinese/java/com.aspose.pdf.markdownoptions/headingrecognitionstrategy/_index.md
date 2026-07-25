---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "表示标题识别策略的类型。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

表示标题识别策略的类型。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Auto](#Auto) | 提供自动标题识别策略的选择。这是默认选项。如果文档包含书签，将选择 {@link HeadingRecognitionStrategy#Outlines} 策略，否则 {@link HeadingRecognitionStrategy#Heuristic} |
| [Heuristic](#Heuristic) | 表示通过启发式规则和字体大小统计的标题识别策略。 |
| [None](#None) | 不识别标题。此选项在格式复杂的文档中可能有用。 |
| [Outlines](#Outlines) | 表示通过大纲的标题识别策略。 |

### Auto {#Auto}
```
public static final int Auto
```

提供自动标题识别策略的选择。这是默认选项。如果文档包含书签，将选择 {@link HeadingRecognitionStrategy#Outlines} 策略，否则 {@link HeadingRecognitionStrategy#Heuristic}

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

表示通过启发式规则和字体大小统计的标题识别策略。

### None {#None}
```
public static final int None
```

不识别标题。此选项在格式复杂的文档中可能有用。

### Outlines {#Outlines}
```
public static final int Outlines
```

表示通过大纲的标题识别策略。
