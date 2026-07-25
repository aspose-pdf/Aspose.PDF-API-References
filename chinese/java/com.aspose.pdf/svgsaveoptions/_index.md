---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "导出为 SVG 格式的保存选项"
type: docs
weight: 4720
url: /zh/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

导出为 SVG 格式的保存选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | 此字段可以包含在转换期间（如果提供）用于自定义处理已创建的引用外部图像文件（如嵌入的 BMP 或 JPEG）并嵌入到保存的 SVG 中的保存策略。该策略必须处理资源并返回表示生成的 SVG 中已保存资源的期望 URI 的字符串。如果出于某种原因该文件的处理必须由转换器的代码本身完成，而不是自定义代码，请在自定义代码中设置 'CustomProcessingCancelled' 标志，针对 'imageSavingInfo' 参数的变量。它向转换器指示所有该资源的必要处理步骤必须在转换器内部完成，就好像没有任何外部自定义代码一样。 |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | 指定输出是否将创建为单个 zip 压缩包。请参阅对 'TreatTargetFileNameAsDirectory' 选项的注释，以了解多页源文档的页面 svg 文件命名规则，这些规则同样适用于压缩的输出文件集合。 |
| [isScaleToPixels](#isScaleToPixels--) | 指定是否将输出文档从排版点缩放到像素。 |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | 此选项定义是否在请求的输出文件不存在时创建一个与请求的输出文件同名的目标目录，而不是直接创建输出文件本身。这样，目录将包含所有页面的输出 SVG 图像（如下面所述）。如果选择否，则除第一页之外的页面输出文件将直接创建在请求的目录中，作为主输出文件，但文件名会带有后缀 _[2...n]，该后缀由页码决定，例如，如果您将输出文件定义为 "C:\\AsposeTests\\output.svg" 且输出将包含多个页面的 svg 文件，则页面文件也会创建在目录 "C:\\AsposeTests\\" 中，名称分别为 'output.svg'、'output_2.svg'、'output_3.svg' 等。 |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | 指定输出是否将创建为单个 zip 压缩包。请参阅对 'TreatTargetFileNameAsDirectory' 选项的注释，以了解多页源文档的页面 svg 文件命名规则，这些规则同样适用于压缩的输出文件集合。 |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | 此字段可以包含在转换期间（如果提供）用于自定义处理已创建的引用外部图像文件（如嵌入的 BMP 或 JPEG）并嵌入到保存的 SVG 中的保存策略。 |
| [setScaleToPixels](#setScaleToPixels-boolean-) | 指定是否将输出文档从排版点缩放到像素。 |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | 此选项定义是否在请求的输出文件不存在时创建一个与请求的输出文件同名的目标目录，而不是直接创建输出文件本身。这样，目录将包含所有页面的输出 SVG 图像（如下面所述）。如果选择否，则除第一页之外的页面输出文件将直接创建在请求的目录中，作为主输出文件，但文件名会带有后缀 _[2...n]，该后缀由页码决定，例如，如果您将输出文件定义为 "C:\\AsposeTests\\output.svg" 且输出将包含多个页面的 svg 文件，则页面文件也会创建在目录 "C:\\AsposeTests\\" 中，名称分别为 'output.svg'、'output_2.svg'、'output_3.svg' 等。 |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

构造函数

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

此字段可以包含在转换期间（如果提供）用于自定义处理已创建的引用外部图像文件（如嵌入的 BMP 或 JPEG）并嵌入到保存的 SVG 中的保存策略。该策略必须处理资源并返回表示生成的 SVG 中已保存资源的期望 URI 的字符串。如果出于某种原因该文件的处理必须由转换器的代码本身完成，而不是自定义代码，请在自定义代码中设置 'CustomProcessingCancelled' 标志，针对 'imageSavingInfo' 参数的变量。它向转换器指示所有该资源的必要处理步骤必须在转换器内部完成，就好像没有任何外部自定义代码一样。

**Returns:**
EmbeddedImagesSavingStrategy 实例

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

指定输出是否将创建为单个 zip 压缩包。请参阅对 'TreatTargetFileNameAsDirectory' 选项的注释，以了解多页源文档的页面 svg 文件命名规则，这些规则同样适用于压缩的输出文件集合。

**Returns:**
布尔值

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

指定是否将输出文档从排版点缩放到像素。

**Returns:**
布尔值

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

此选项定义是否在请求的输出文件不存在时创建一个与请求的输出文件同名的目标目录，而不是直接创建输出文件本身。这样，目录将包含所有页面的输出 SVG 图像（如下面所述）。如果选择否，则除第一页之外的页面输出文件将直接创建在请求的目录中，作为主输出文件，但文件名会带有后缀 _[2...n]，该后缀由页码决定，例如，如果您将输出文件定义为 "C:\AsposeTests\output.svg" 且输出将包含多个页面的 svg 文件，则页面文件也会创建在目录 "C:\AsposeTests\" 中，名称分别为 'output.svg'、'output_2.svg'、'output_3.svg' 等。

**Returns:**
布尔值

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

指定输出是否将创建为单个 zip 压缩包。请参阅对 'TreatTargetFileNameAsDirectory' 选项的注释，以了解多页源文档的页面 svg 文件命名规则，这些规则同样适用于压缩的输出文件集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| compressOutputToZipArchive |  | 布尔值 |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
此字段可以包含在转换期间（如果提供）用于自定义处理已创建的引用外部图像文件（如嵌入的 BMP 或 JPEG）并嵌入到保存的 SVG 中的保存策略。

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

指定是否将输出文档从排版点缩放到像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleToPixels |  | 布尔值 |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

此选项定义是否在请求的输出文件不存在时创建一个与请求的输出文件同名的目标目录，而不是直接创建输出文件本身。这样，目录将包含所有页面的输出 SVG 图像（如下面所述）。如果选择否，则除第一页之外的页面输出文件将直接创建在请求的目录中，作为主输出文件，但文件名会带有后缀 _[2...n]，该后缀由页码决定，例如，如果您将输出文件定义为 "C:\AsposeTests\output.svg" 且输出将包含多个页面的 svg 文件，则页面文件也会创建在目录 "C:\AsposeTests\" 中，名称分别为 'output.svg'、'output_2.svg'、'output_3.svg' 等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | 布尔值 |
