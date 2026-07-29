---
title: "HiddenDataSanitizer"
linktitle: "HiddenDataSanitizer"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于清理隐藏数据的类。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.security/hiddendatasanitizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizer

```
public final class HiddenDataSanitizer extends Object
```

表示用于清理隐藏数据的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HiddenDataSanitizer](#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-) | 提供从 PDF 文档中清理隐藏数据的功能，确保元数据、注释、JavaScript 或私有内容等敏感或不必要的信息被删除或转换。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [sanitize](#sanitize-com.aspose.pdf.Document-) | 通过删除或转换隐藏数据来清理给定的 PDF 文档。 |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-) | 将页面内容替换为图像并删除其他隐藏数据。允许您使用背景颜色删除隐藏文本，以及删除图像下方的隐藏文本。同时，完全移除所有交互元素。文档会先按原样转换为图像，然后清除任何剩余的隐藏数据。如果需要先清除再转换，请使用主类方法。 |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-int-) | 将页面内容替换为图像并删除其他隐藏数据。允许您使用背景颜色删除隐藏文本，以及删除图像下方的隐藏文本。也完全移除所有交互元素。文档会先按原样转换为图像，然后清除任何剩余的隐藏数据。如果需要先清除再转换，请使用主类方法。 |

### HiddenDataSanitizer {#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-}
提供从 PDF 文档中清理隐藏数据的功能，确保元数据、注释、JavaScript 或私有内容等敏感或不必要的信息被删除或转换。

### sanitize {#sanitize-com.aspose.pdf.Document-}
通过删除或转换隐藏数据来清理给定的 PDF 文档。

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-}
将页面内容替换为图像并删除其他隐藏数据。允许您使用背景颜色删除隐藏文本，以及删除图像下方的隐藏文本。同时，完全移除所有交互元素。文档会先按原样转换为图像，然后清除任何剩余的隐藏数据。如果需要先清除再转换，请使用主类方法。

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-int-}
将页面内容替换为图像并删除其他隐藏数据。允许您使用背景颜色删除隐藏文本，以及删除图像下方的隐藏文本。也完全移除所有交互元素。文档会先按原样转换为图像，然后清除任何剩余的隐藏数据。如果需要先清除再转换，请使用主类方法。
