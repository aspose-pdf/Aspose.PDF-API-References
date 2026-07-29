---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "此类表示在将 PDF 转换为其他格式（例如 HTML）期间涉及外部资源文件保存的一组数据。"
type: docs
weight: 4440
url: /zh/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

此类表示在将 PDF 转换为其他格式（例如 HTML）期间涉及外部资源文件保存的一组数据。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getContentStream](#getContentStream--) | 由转换器设置。表示已保存文件的二进制内容。 |
| [getResourceType](#getResourceType--) | 由转换器设置。假定的文件名从转换器传递到自定义方法的代码，可在自定义代码中用于决定如何处理或将文件保存到何处。 |
| [getSupposedFileName](#getSupposedFileName--) | 由转换器设置。假定的文件名从转换器传递到自定义方法的代码，可在自定义代码中用于决定如何处理或将文件保存到何处。 |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | 如果出于某些原因，建议的文件应由转换器的代码而非自定义代码进行处理，则必须在自定义代码中将此标志设置为 "true"。因此，将此设置为 true 表示自定义代码未处理引用的文件，转换器必须自行处理（包括保存位置和在引用文件中的命名）。 |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | 如果出于某些原因，建议的文件应由转换器的代码而非自定义代码进行处理，则必须在自定义代码中将此标志设置为 "true"。因此，将此设置为 true 表示自定义代码未处理引用的文件，转换器必须自行处理（包括保存位置和在引用文件中的命名）。 |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

由转换器设置。表示已保存文件的二进制内容。

**Returns:**
字节数组

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

由转换器设置。假定的文件名从转换器传递到自定义方法的代码，可在自定义代码中用于决定如何处理或将文件保存到何处。

**Returns:**
NodeLevelResourceType 元素 @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

由转换器设置。假定的文件名从转换器传递到自定义方法的代码，可在自定义代码中用于决定如何处理或将文件保存到何处。

**Returns:**
字符串值

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

如果出于某些原因，建议的文件应由转换器的代码而非自定义代码进行处理，则必须在自定义代码中将此标志设置为 "true"。因此，将此设置为 true 表示自定义代码未处理引用的文件，转换器必须自行处理（包括保存位置和在引用文件中的命名）。

**Returns:**
布尔值

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

如果出于某些原因，建议的文件应由转换器的代码而非自定义代码进行处理，则必须在自定义代码中将此标志设置为 "true"。因此，将此设置为 true 表示自定义代码未处理引用的文件，转换器必须自行处理（包括保存位置和在引用文件中的命名）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| customProcessingCancelled |  | 布尔值 |
