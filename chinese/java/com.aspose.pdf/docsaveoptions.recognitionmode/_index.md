---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF for Java API 参考"
description: "允许控制 PDF 文档如何转换为文字处理文档。当生成的文档不需要大量处理时，请使用 RecognitionMode.Textbox 模式。"
type: docs
weight: 1050
url: /zh/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

允许控制 PDF 文档转换为文字处理文档的方式。当生成的文档不需要大量后续编辑时，使用 RecognitionMode.Textbox 模式。文本框在内容较少时易于修改。当输出文档需要进一步编辑时，使用 RecognitionMode.Flow 模式。流模式下的段落和文本行便于文本的修改，但不受支持的格式对象的显示效果会比 RecognitionMode.Textbox 模式更差。

## 字段

| 字段 | 描述 |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | 一种支持表格识别的替代 Flow 模式。 |
| [Flow](#Flow) | 完整识别模式，引擎执行分组和多层分析，以恢复原始文档作者的意图并生成可最大程度编辑的文档。 |
| [Textbox](#Textbox) | 此模式快速且有助于最大程度保留 PDF 文件的原始外观，但生成文档的可编辑性可能受限。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

一种支持表格识别的替代 Flow 模式。

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

完整识别模式，引擎执行分组和多层分析，以恢复原始文档作者的意图并生成可最大程度编辑的文档。

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

此模式快速且有助于最大程度保留 PDF 文件的原始外观，但生成文档的可编辑性可能受限。

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
