---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文档中清理隐藏数据的配置选项。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

表示文档中清理隐藏数据的配置选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [all](#all--) | 创建一个 {@link HiddenDataSanitizationOptions} 类的新实例，并将所有选项设置为消毒。此操作包括启用删除注释、JavaScript、元数据、附件、搜索索引、私人信息、表单和图层的扁平化，同时禁用将页面转换为图像的选项。像 {@code ImageCompressionOptions}（{@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}）或 {@code ConvertPagesToImages}（{@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}）这样的可选配置可以在获取实例后手动修改，因为默认情况下它们未激活。 |
| [getConvertPagesToImages](#getConvertPagesToImages--) | 获取将页面转换为图像的选项。如果启用此选项，ImageCompressionOptions 选项将被忽略。如果需要，在使用 {@code #All()} 方法时必须手动启用该选项。页面转换为图像的过程将在清除由其他选项控制的主要隐藏数据后进行。 |
| [getFlattenForms](#getFlattenForms--) | 获取一个值，指示在消毒过程中是否应将文档中的表单扁平化。表单扁平化会将交互式表单字段转换为静态内容，使其不可编辑或填写。 |
| [getFlattenLayers](#getFlattenLayers--) | 获取在 PDF 文档中扁平化图层的选项。启用后，文档中的所有图层将合并为单个图层，去除其独立结构。此选项通过简化内容并确保图层中不存在隐藏数据，对文档消毒非常有用。 |
| [getImageCompressionOptions](#getImageCompressionOptions--) | 获取文档图像转换选项。如果需要，在使用 {@code #All()} 方法时必须手动启用该选项。 |
| [getImageDpi](#getImageDpi--) | 获取在转换过程中解析页面图像的选项。 |
| [getRemoveAnnotations](#getRemoveAnnotations--) | 获取一个值，指示是否从文档中删除注释。启用后，文档中存在的所有注释将在消毒过程中被删除。遮蔽注释将被应用。 |
| [getRemoveAttachments](#getRemoveAttachments--) | 获取从文档中删除所有附件的选项。启用后，可确保在消毒过程中删除 PDF 中的任何附件。 |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | 获取一个值，指示是否应从文档中删除 JavaScript 及其相关操作。此选项有助于消除嵌入脚本可能带来的安全漏洞。 |
| [getRemoveMetadata](#getRemoveMetadata--) | 获取从文档中删除元数据的选项。如果设置为 true，将在消毒过程中删除文档属性等元数据以及其他嵌入的元数据信息。 |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | 获取一个值，指示是否应从文档中删除搜索索引和私人信息。此选项启用删除嵌入的搜索索引和私人数据，以提升文档的安全性和隐私性。 |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | 设置将页面转换为图像的选项。如果启用此选项，ImageCompressionOptions 选项将被忽略。如果需要，在使用 {@code #All()} 方法时必须手动启用该选项。页面转换为图像的过程将在清除由其他选项控制的主要隐藏数据后进行。 |
| [setFlattenForms](#setFlattenForms-boolean-) | 设置一个值，指示在消毒过程中是否应将文档中的表单扁平化。表单扁平化会将交互式表单字段转换为静态内容，使其不可编辑或填写。 |
| [setFlattenLayers](#setFlattenLayers-boolean-) | 设置在 PDF 文档中扁平化图层的选项。启用后，文档中的所有图层将合并为单个图层，去除其独立结构。此选项通过简化内容并确保图层中不存在隐藏数据，对文档消毒非常有用。 |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | 设置文档图像转换选项。如果需要，在使用 {@code #All()} 方法时必须手动启用该选项。 |
| [setImageDpi](#setImageDpi-int-) | 设置在转换过程中解析页面图像的选项。 |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | 设置一个值，指示是否从文档中删除注释。启用后，文档中存在的所有注释将在消毒过程中被删除。遮蔽注释将被应用。 |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | 设置从文档中删除所有附件的选项。启用后，可确保在消毒过程中删除 PDF 中的任何附件。 |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | 设置一个值，指示是否应从文档中删除 JavaScript 及其相关操作。此选项有助于消除嵌入脚本可能带来的安全漏洞。 |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | 设置从文档中删除元数据的选项。如果设置为 true，将在消毒过程中删除文档属性等元数据以及其他嵌入的元数据信息。 |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | 设置一个值，指示是否应从文档中删除搜索索引和私人信息。此选项启用删除嵌入的搜索索引和私人数据，以提升文档的安全性和隐私性。 |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

创建一个 {@link HiddenDataSanitizationOptions} 类的新实例，并将所有选项设置为消毒。此操作包括启用删除注释、JavaScript、元数据、附件、搜索索引、私人信息、表单和图层的扁平化，同时禁用将页面转换为图像的选项。像 {@code ImageCompressionOptions}（{@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}）或 {@code ConvertPagesToImages}（{@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}）这样的可选配置可以在获取实例后手动修改，因为默认情况下它们未激活。

**Returns:**
一个已预配置所有消毒选项的 {@link HiddenDataSanitizationOptions} 实例。

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

获取将页面转换为图像的选项。如果启用此选项，ImageCompressionOptions 选项将被忽略。如果需要，在使用 {@code #All()} 方法时必须手动启用该选项。页面转换为图像的过程将在清除由其他选项控制的主要隐藏数据后进行。

**Returns:**
将页面转换为图像的选项。

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

获取一个值，指示在消毒过程中是否应将文档中的表单扁平化。表单扁平化会将交互式表单字段转换为静态内容，使其不可编辑或填写。

**Returns:**
指示在文档清理过程中是否应将表单扁平化的值。

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

获取在 PDF 文档中扁平化图层的选项。启用后，文档中的所有图层将合并为单个图层，去除其独立结构。此选项通过简化内容并确保图层中不存在隐藏数据，对文档消毒非常有用。

**Returns:**
将 PDF 文档中的图层扁平化的选项。

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

获取文档图像转换选项。如果需要，在使用 {@code #All()} 方法时必须手动启用该选项。

**Returns:**
文档图像转换选项。

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

获取在转换过程中解析页面图像的选项。

**Returns:**
在转换过程中解析页面图像的选项。

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

获取一个值，指示是否从文档中删除注释。启用后，文档中存在的所有注释将在消毒过程中被删除。遮蔽注释将被应用。

**Returns:**
指示是否从文档中移除注释的值。

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

获取从文档中删除所有附件的选项。启用后，可确保在消毒过程中删除 PDF 中的任何附件。

**Returns:**
从文档中移除所有附件的选项。

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

获取一个值，指示是否应从文档中删除 JavaScript 及其相关操作。此选项有助于消除嵌入脚本可能带来的安全漏洞。

**Returns:**
指示是否应从文档中移除 JavaScript 及相关操作的值。

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

获取从文档中删除元数据的选项。如果设置为 true，将在消毒过程中删除文档属性等元数据以及其他嵌入的元数据信息。

**Returns:**
从文档中移除元数据的选项。

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

获取一个值，指示是否应从文档中删除搜索索引和私人信息。此选项启用删除嵌入的搜索索引和私人数据，以提升文档的安全性和隐私性。

**Returns:**
指示是否应从文档中移除搜索索引和私人信息的值。

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

设置将页面转换为图像的选项。如果启用此选项，ImageCompressionOptions 选项将被忽略。如果需要，在使用 {@code #All()} 方法时必须手动启用该选项。页面转换为图像的过程将在清除由其他选项控制的主要隐藏数据后进行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 将页面转换为图像的选项。 |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

设置一个值，指示在消毒过程中是否应将文档中的表单扁平化。表单扁平化会将交互式表单字段转换为静态内容，使其不可编辑或填写。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示在文档清理过程中是否应将表单扁平化的值。 |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

设置在 PDF 文档中扁平化图层的选项。启用后，文档中的所有图层将合并为单个图层，去除其独立结构。此选项通过简化内容并确保图层中不存在隐藏数据，对文档消毒非常有用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 将 PDF 文档中的图层扁平化的选项。 |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
设置文档图像转换选项。如果需要，在使用 {@code #All()} 方法时必须手动启用该选项。

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

设置在转换过程中解析页面图像的选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 在转换过程中解析页面图像的选项。 |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

设置一个值，指示是否从文档中删除注释。启用后，文档中存在的所有注释将在消毒过程中被删除。遮蔽注释将被应用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示是否从文档中移除注释的值。 |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

设置从文档中删除所有附件的选项。启用后，可确保在消毒过程中删除 PDF 中的任何附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 从文档中移除所有附件的选项。 |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

设置一个值，指示是否应从文档中删除 JavaScript 及其相关操作。此选项有助于消除嵌入脚本可能带来的安全漏洞。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示是否应从文档中移除 JavaScript 及相关操作的值。 |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

设置从文档中删除元数据的选项。如果设置为 true，将在消毒过程中删除文档属性等元数据以及其他嵌入的元数据信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 从文档中移除元数据的选项。 |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

设置一个值，指示是否应从文档中删除搜索索引和私人信息。此选项启用删除嵌入的搜索索引和私人数据，以提升文档的安全性和隐私性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示是否应从文档中移除搜索索引和私人信息的值。 |
