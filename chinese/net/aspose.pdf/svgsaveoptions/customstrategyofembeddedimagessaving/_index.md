---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions 字段。该字段可以包含在转换过程中必须使用的保存策略，以便自定义处理创建的引用外部图像文件，如嵌入的 BMP 或 JPEG，嵌入到保存的 SVG 中。该策略必须处理资源并返回表示生成的 SVG 中保存资源的期望 URI 的字符串。如果出于某种原因，某个文件的处理必须由转换器的代码本身完成，而不是在自定义代码中，请在自定义代码中设置 'imageSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志。这向转换器发出信号，表示处理该资源所需的所有步骤必须在转换器本身中完成，就好像没有任何外部自定义代码一样。
type: docs
weight: 30
url: /zh/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving 字段

该字段可以包含在转换过程中必须使用的保存策略（如果存在），以便自定义处理创建的引用外部图像文件（如嵌入的 BMP 或 JPEG），嵌入到保存的 SVG 中。该策略必须处理资源并返回表示生成的 SVG 中保存资源的期望 URI 的字符串。如果出于某种原因，某个文件的处理必须由转换器的代码本身完成，而不是在自定义代码中，请在自定义代码中设置 'imageSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志。这向转换器发出信号，表示处理该资源所需的所有步骤必须在转换器本身中完成，就好像没有任何外部自定义代码一样。

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### 另请参见

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)