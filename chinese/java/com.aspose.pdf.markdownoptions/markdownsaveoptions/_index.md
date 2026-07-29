---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 Markdown 格式的文档保存选项类。"
type: docs
weight: 60
url: /zh/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

表示 Markdown 格式的文档保存选项类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | 创建一个用于将文档保存为 markdown 格式的实例选项。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | 获取或设置用于提取内容为 markdown 的矩形区域。 |
| [getEmphasisStyle](#getEmphasisStyle--) | 获取或设置生成文档的强调样式。 |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | 获取和设置指示是否应提取矢量图形的属性。 |
| [getHeadingLevels](#getHeadingLevels--) | 定义在 FontSize 识别标题策略中使用的预期标题级别。如果设置了此属性值，则在设置 {@link HeadingRecognitionStrategy#Auto} 策略时，即使文档包含书签，也会选择 {@link HeadingRecognitionStrategy#Heuristic} 标题识别策略。 |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | 获取或设置标题识别策略。 |
| [getHeadingStyle](#getHeadingStyle--) | 获取或设置生成文档的标题样式。 |
| [getLineBreakStyle](#getLineBreakStyle--) | 获取或设置生成文档的换行样式。 |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | 获取和设置用于保存文档资源（如图像）的目录名称。如果未指定该值，则图像将写入与 markdown 文件本身相同的目录。这不是路径，仅是名称！该目录将在保存的 markdown 文件所在的目录中自动创建。 |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | 获取和设置用于保存文档资源（如图像）的目录名称。该目录将在保存的 markdown 文件所在的目录中自动创建。 |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | 获取并设置是否允许转换下标和上标。默认值为 true。 |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | 获取并设置是否允许使用 img 标签在文本左侧或右侧插入图像。在这种情况下，markdown 查看器中，文本将环绕图像换行。 |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | 获取或设置用于提取内容为 markdown 的矩形区域。 |
| [setEmphasisStyle](#setEmphasisStyle-int-) | 获取或设置生成文档的强调样式。 |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | 获取和设置指示是否应提取矢量图形的属性。 |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | 定义在 FontSize 识别标题策略中使用的预期标题级别。如果设置了此属性值，则在设置 {@link HeadingRecognitionStrategy#Auto} 策略时，即使文档包含书签，也会选择 {@link HeadingRecognitionStrategy#Heuristic} 标题识别策略。 |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | 获取或设置标题识别策略。 |
| [setHeadingStyle](#setHeadingStyle-int-) | 获取或设置生成文档的标题样式。 |
| [setLineBreakStyle](#setLineBreakStyle-int-) | 获取或设置生成文档的换行样式。 |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | 获取和设置用于保存文档资源（如图像）的目录名称。如果未指定该值，则图像将写入与 markdown 文件本身相同的目录。这不是路径，仅是名称！该目录将在保存的 markdown 文件所在的目录中自动创建。 |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | 获取和设置用于保存文档资源（如图像）的目录名称。该目录将在保存的 markdown 文件所在的目录中自动创建。 |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | 获取并设置是否允许转换下标和上标。默认值为 true。 |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | 获取并设置是否允许使用 img 标签在文本左侧或右侧插入图像。在这种情况下，markdown 查看器中，文本将环绕图像换行。 |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

创建一个用于将文档保存为 markdown 格式的实例选项。

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

获取或设置用于提取内容为 markdown 的矩形区域。

**Returns:**
Rectangle 实例

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

获取或设置生成文档的强调样式。

**Returns:**
EmphasisStyle 元素

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

获取和设置指示是否应提取矢量图形的属性。

**Returns:**
布尔值

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

定义在 FontSize 识别标题策略中使用的预期标题级别。如果设置了此属性值，则在设置 {@link HeadingRecognitionStrategy#Auto} 策略时，即使文档包含书签，也会选择 {@link HeadingRecognitionStrategy#Heuristic} 标题识别策略。

**Returns:**
HeadingLevels 实例

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

获取或设置标题识别策略。

**Returns:**
HeadingRecognitionStrategy 元素

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

获取或设置生成文档的标题样式。

**Returns:**
HeadingStyle 元素

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

获取或设置生成文档的换行样式。

**Returns:**
LineBreakStyle 元素

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

获取和设置用于保存文档资源（如图像）的目录名称。如果未指定该值，则图像将写入与 markdown 文件本身相同的目录。这不是路径，仅是名称！该目录将在保存的 markdown 文件所在的目录中自动创建。

**Returns:**
字符串值

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

获取和设置用于保存文档资源（如图像）的目录名称。该目录将在保存的 markdown 文件所在的目录中自动创建。

**Returns:**
字符串值

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

获取并设置是否允许转换下标和上标。默认值为 true。

**Returns:**
布尔值

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

获取并设置是否允许使用 img 标签在文本左侧或右侧插入图像。在这种情况下，markdown 查看器中，文本将环绕图像换行。

**Returns:**
布尔值

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
获取或设置用于提取内容为 markdown 的矩形区域。

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

获取或设置生成文档的强调样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | EmphasisStyle 元素 |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

获取和设置指示是否应提取矢量图形的属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
定义在 FontSize 识别标题策略中使用的预期标题级别。如果设置了此属性值，则在设置 {@link HeadingRecognitionStrategy#Auto} 策略时，即使文档包含书签，也会选择 {@link HeadingRecognitionStrategy#Heuristic} 标题识别策略。

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

获取或设置标题识别策略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | HeadingRecognitionStrategy 元素 |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

获取或设置生成文档的标题样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | HeadingStyle 元素 |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

获取或设置生成文档的换行样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | LineBreakStyle 元素 |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
获取和设置用于保存文档资源（如图像）的目录名称。如果未指定该值，则图像将写入与 markdown 文件本身相同的目录。这不是路径，仅是名称！该目录将在保存的 markdown 文件所在的目录中自动创建。

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
获取和设置用于保存文档资源（如图像）的目录名称。该目录将在保存的 markdown 文件所在的目录中自动创建。

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

获取并设置是否允许转换下标和上标。默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

获取并设置是否允许使用 img 标签在文本左侧或右侧插入图像。在这种情况下，markdown 查看器中，文本将环绕图像换行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
