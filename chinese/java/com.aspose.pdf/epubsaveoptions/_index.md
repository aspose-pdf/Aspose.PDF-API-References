---
title: "EpubSaveOptions"
linktitle: "EpubSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "导出为 EPUB 格式的保存选项"
type: docs
weight: 1240
url: /zh/java/com.aspose.pdf/epubsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.EpubSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.EpubSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.EpubSaveOptions

```
public class EpubSaveOptions extends UnifiedSaveOptions
```

导出为 EPUB 格式的保存选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EpubSaveOptions](#EpubSaveOptions--) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getContentRecognitionMode](#getContentRecognitionMode--) | 当 PDF 文件（通常具有固定布局）被转换时，转换引擎会尝试进行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的结果。此属性用于调节该转换，以实现期望的内容识别方式。 |
| [getTitle](#getTitle--) | 获取或设置 EPUB 文档标题。 |
| [setContentRecognitionMode](#setContentRecognitionMode-com.aspose.pdf.EpubSaveOptions.RecognitionMode-) | 当 PDF 文件（通常具有固定布局）被转换时，转换引擎会尝试执行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的结果。 |
| [setTitle](#setTitle-java.lang.String-) | 获取或设置 EPUB 文档标题。 |

### EpubSaveOptions {#EpubSaveOptions--}
```
public EpubSaveOptions()
```

构造函数

### getContentRecognitionMode {#getContentRecognitionMode--}
```
public EpubSaveOptions.RecognitionMode getContentRecognitionMode()
```

当 PDF 文件（通常具有固定布局）被转换时，转换引擎会尝试进行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的结果。此属性用于调节该转换，以实现期望的内容识别方式。

**Returns:**
RecognitionMode 元素 @see RecognitionMode

### getTitle {#getTitle--}
```
public final String getTitle()
```

获取或设置 EPUB 文档标题。

**Returns:**
字符串值

### setContentRecognitionMode {#setContentRecognitionMode-com.aspose.pdf.EpubSaveOptions.RecognitionMode-}
当 PDF 文件（通常具有固定布局）被转换时，转换引擎会尝试执行分组和多层分析，以恢复原始文档作者的意图并生成流式布局的结果。

### setTitle {#setTitle-java.lang.String-}
获取或设置 EPUB 文档标题。
