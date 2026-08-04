---
title: "ImageCompressionOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "类包含一组图像压缩选项。"
type: docs
weight: 10
url: /zh/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

类包含一组图像压缩选项。

ImageCompressionOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| ImageCompressionOptions() | 初始化 ImageCompressionOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| compress_images | 如果此标志设置为 true，文档中的图像将被压缩。压缩级别由 ImageQuality 属性指定。 |
| resize_images | 如果此标志设置为 true 且 CompressImages 为 true，当图像分辨率大于指定的 MaxResolution 参数时，图像将被重新调整大小。 |
| image_quality | 在使用 CompressIamges 标志时指定图像压缩的级别。 |
| max_resolution | 指定图像的最大分辨率。如果图像的分辨率更高，则会进行缩放。 |
| version | 压缩算法的版本。可能的取值有：1. 标准压缩，2. 快速（改进的压缩，比标准更快，但可能并不适用于所有图像），3. 混合（对无法通过更快算法压缩的图像使用标准压缩，这可能提供最佳压缩，但比"fast"算法更慢。版本"Fast"不适用于调整图像大小（将使用标准方法）。默认是"Standard"。） |
| 编码 | 获取或设置用于存储图像的编码。 |

### 另请参阅

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

