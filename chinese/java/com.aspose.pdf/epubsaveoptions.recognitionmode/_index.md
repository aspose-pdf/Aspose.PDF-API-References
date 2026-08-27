---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Aspose.PDF for Java API 参考"
description: "当 PDF 文件（通常具有固定布局）被转换时，转换引擎会尝试执行分组和多层分析，以恢复原始文档。"
type: docs
weight: 1250
url: /zh/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

当 PDF 文件（通常具有固定布局）被转换时，转换引擎会尝试进行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的结果。此属性用于调节该转换，以实现期望的内容识别方式。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Fixed](#Fixed) | 此模式快速且有助于最大程度地保留原始页面外观，但不幸的是，许多 EPUB 阅读器不支持具有固定布局的 XHTML。 |
| [Flow](#Flow) | 完整识别模式，引擎尝试执行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的 XHTML。 |
| [PdfFlow](#PdfFlow) | 此转换的主要思路是基于保存 PDF 文档处理过程中形成的内容渲染的 “自然” 顺序。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

此模式快速且有助于最大程度地保留原始页面外观，但不幸的是，许多 EPUB 阅读器不支持具有固定布局的 XHTML。

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

完整识别模式，引擎尝试执行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的 XHTML。

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

此转换的主要思路是基于保存 PDF 文档处理过程中形成的内容渲染的 “自然” 顺序。

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
