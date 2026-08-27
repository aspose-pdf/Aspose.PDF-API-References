---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Aspose.PDF for Java API 参考"
description: "提供 PDF 文档中自动标记功能的设置。{@link AutoTaggingSettings} 类允许配置 PDF 内容自动标记的选项。它。"
type: docs
weight: 230
url: /zh/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

提供 PDF 文档自动标记功能的设置。{@link AutoTaggingSettings} 类允许配置 PDF 内容自动标记的选项。它包括用于启用或禁用自动标记、指定标题识别策略以及基于字体大小定义标题级别的属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDefault](#getDefault--) | 获取 PDF 文档中自动标记功能的默认设置。默认设置启用自动标记并使用自动的标题识别策略。这些设置可用作 PDF 格式转换或其他需要自动标记 PDF 内容的操作的基线配置。 |
| [getEnableAutoTagging](#getEnableAutoTagging--) | 获取或设置一个值，指示是否启用自动标记功能。启用后，自动标记功能会自动为 PDF 文档生成标记内容，从而提升可访问性和结构性。 |
| [getHeadingLevels](#getHeadingLevels--) | 获取或设置用于确定 PDF 文档中标题结构的标题级别。{@code HeadingLevels}（{@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}）属性允许配置字体大小到标题级别的映射。这在自动标记过程中用于根据文档中文本元素的字体大小识别并分配适当的标题级别。 |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | 获取或设置在自动标记期间用于识别文档中标题的策略。{@code HeadingRecognitionStrategy}（{@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}）属性决定文档中标题的识别方式。可用的策略包括基于大纲、启发式分析或自动检测的标题识别。将此属性设置为 {@link HeadingRecognitionStrategy#None} 将禁用标题识别。 |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | 获取或设置一个值，指示是否启用自动标记功能。启用后，自动标记功能会自动为 PDF 文档生成标记内容，从而提升可访问性和结构性。 |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | 获取或设置用于确定 PDF 文档中标题结构的标题级别。{@code HeadingLevels}（{@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}）属性允许配置字体大小到标题级别的映射。这在自动标记过程中用于根据文档中文本元素的字体大小识别并分配适当的标题级别。 |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | 获取或设置在自动标记期间用于识别文档中标题的策略。{@code HeadingRecognitionStrategy}（{@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}）属性决定文档中标题的识别方式。可用的策略包括基于大纲、启发式分析或自动检测的标题识别。将此属性设置为 {@link HeadingRecognitionStrategy#None} 将禁用标题识别。 |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

获取 PDF 文档中自动标记功能的默认设置。默认设置启用自动标记并使用自动的标题识别策略。这些设置可用作 PDF 格式转换或其他需要自动标记 PDF 内容的操作的基线配置。

**Returns:**
AutoTaggingSettings 实例

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

获取或设置一个值，指示是否启用自动标记功能。启用后，自动标记功能会自动为 PDF 文档生成标记内容，从而提升可访问性和结构性。

**Returns:**
布尔值

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

获取或设置用于确定 PDF 文档中标题结构的标题级别。{@code HeadingLevels}（{@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}）属性允许配置字体大小到标题级别的映射。这在自动标记过程中用于根据文档中文本元素的字体大小识别并分配适当的标题级别。

**Returns:**
HeadingLevels 实例

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

获取或设置在自动标记期间用于识别文档中标题的策略。{@code HeadingRecognitionStrategy}（{@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}）属性决定文档中标题的识别方式。可用的策略包括基于大纲、启发式分析或自动检测的标题识别。将此属性设置为 {@link HeadingRecognitionStrategy#None} 将禁用标题识别。

**Returns:**
HeadingRecognitionStrategy 元素

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

获取或设置一个值，指示是否启用自动标记功能。启用后，自动标记功能会自动为 PDF 文档生成标记内容，从而提升可访问性和结构性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
获取或设置用于确定 PDF 文档中标题结构的标题级别。{@code HeadingLevels}（{@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}）属性允许配置字体大小到标题级别的映射。这在自动标记过程中用于根据文档中文本元素的字体大小识别并分配适当的标题级别。

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

获取或设置在自动标记期间用于识别文档中标题的策略。{@code HeadingRecognitionStrategy}（{@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}）属性决定文档中标题的识别方式。可用的策略包括基于大纲、启发式分析或自动检测的标题识别。将此属性设置为 {@link HeadingRecognitionStrategy#None} 将禁用标题识别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | HeadingRecognitionStrategy 元素 |
