---
title: "委托 SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "对于此类属性，您可以分配由自定义方法创建的委托，该方法实现对从 PDF 生成的 SVG 中提取的图像的外部保存处理，并且在 PDF 转 HTML 的转换过程中必须将该图像保存为外部资源。在这种情况下，可以在自定义代码中进行诸如自行保存到流或磁盘的处理，并且该自定义代码必须返回不带引号的路径或其他字符串，随后会被嵌入生成的 SVG 中，以取代原本应有的图像资源路径。此时，图像保存的所有必要操作必须在提供的方法代码中完成，因为转换器代码中的保存结果将不会被使用。如果由于某些原因必须由转换器代码本身（而非自定义代码）处理此文件或该文件，请在自定义代码中设置标志 CustomProcessingCancelled 于 imageSavingInfo 参数变量。它向转换器指示，所有对该资源的必要处理步骤必须在转换器内部完成，就像没有任何外部自定义代码一样。该对象表示已保存图像的信息，可在自定义代码中使用，必须返回表示图像 URL 的字符串，该 URL 将放入 SVG 中。"
type: docs
weight: 10420
url: /zh/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

对于此类属性，您可以分配由自定义方法创建的委托，该方法实现对从 PDF 生成的 SVG 中提取的图像的外部保存处理，并且在 PDF 转 HTML 的转换过程中必须将该图像保存为外部资源。在这种情况下，处理（如自行保存到流或磁盘）可以在自定义代码中完成，并且该自定义代码必须返回路径（或任何其他不带引号的字符串），随后会被嵌入生成的 SVG 中，以取代原本应有的图像资源路径。此时，图像保存的所有必要操作必须在提供的方法代码中完成，因为转换器代码中的保存结果将不会被使用。如果由于某些原因必须由转换器的代码本身（而非自定义代码）处理此文件或该文件，请在自定义代码中设置标志 'CustomProcessingCancelled' 于 'imageSavingInfo' 参数的变量。它向转换器指示，所有对该资源的必要处理步骤必须在转换器内部完成，就像没有任何外部自定义代码一样。该对象表示已保存图像的信息，可在自定义代码中使用，必须返回表示图像 URL 的字符串，该 URL 将放入 SVG 中。

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### 另请参见

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


