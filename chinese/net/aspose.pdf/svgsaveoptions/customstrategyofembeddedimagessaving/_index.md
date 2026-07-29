---
title: "SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving"
second_title: "Aspose.PDF for .NET API 参考"
description: "SvgSaveOptions 字段。此字段可以包含在转换期间使用的保存策略（如果存在），用于对创建的引用外部图像文件（如嵌入到已保存 SVG 中的 BMP 或 JPEG）进行自定义处理。该策略必须处理资源并返回表示已保存资源在生成的 SVG 中的期望 URI 的字符串。如果出于某种原因必须由转换器代码本身而不是自定义代码来处理此文件或该文件，请在自定义代码中设置 imageSavingInfo 参数变量的标志 CustomProcessingCancelled。它向转换器指示，所有该资源的处理步骤必须在转换器内部完成，就像没有任何外部自定义代码一样。"
type: docs
weight: 30
url: /zh/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

此字段可以包含在转换期间必须使用的保存策略（如果存在），用于对创建的引用外部图像文件（如嵌入的 BMP 或 JPEG）进行自定义处理，这些图像文件会嵌入保存的 SVG 中。该策略必须处理资源并返回表示生成的 SVG 中已保存资源的期望 URI 的字符串。如果出于某种原因必须由转换器的代码本身而不是自定义代码来处理此文件或该文件，请在自定义代码中设置 'CustomProcessingCancelled' 标志于 'imageSavingInfo' 参数的变量。它向转换器指示所有必要的资源处理步骤必须在转换器内部完成，就像没有任何外部自定义代码一样。

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### 另请参见

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


