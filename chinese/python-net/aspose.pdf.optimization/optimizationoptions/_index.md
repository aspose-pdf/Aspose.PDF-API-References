---
title: "OptimizationOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "描述文档优化算法的类。<br/>            此类的实例可用作 OptimizeResources() 方法的参数。"
type: docs
weight: 20
url: /zh/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

描述文档优化算法的类。<br/>            此类的实例可用作 OptimizeResources() 方法的参数。

OptimizationOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| OptimizationOptions() | 初始化一个新的 OptimizationOptions 类实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| link_duplcate_streams | 如果此标志设置为 true，资源流将被分析。如果发现重复流（即流内容相等），则这些流将存储为一个对象。<br/>            这在某些情况下可以减小文档大小（例如，当同一文档被多次拼接时）。 |
| allow_reuse_page_content | 如果为 true，页面内容将在文档针对相同页面进行优化时被重用。 |
| remove_unused_streams | 如果此标志设置为 true，将检查每个资源的使用情况。如果资源从未被使用，则该资源将被删除。<br/>            这可能会减小文档大小，例如在从文档中提取页面时。 |
| remove_unused_objects | 如果此标志设置为 true，所有文档对象将被检查，未使用的对象（即没有任何引用的对象）将从文档中移除。 |
| image_compression_options | 描述文档中图像是否会被压缩以及压缩参数的一组选项。 |
| compress_images | 如果此标志设置为 true，文档中的图像将被压缩。压缩级别由 ImageQuality 属性指定。 |
| resize_images | 如果此标志设置为 true 且 CompressImages 为 true，当图像分辨率大于指定的 MaxResolution 参数时，图像将被重新调整大小。 |
| image_quality | 在使用 CompressIamges 标志时指定图像压缩的级别。 |
| max_resoultion | 指定图像的最大分辨率。如果图像的分辨率更高，则会进行缩放。 |
| unembed_fonts | 如果设置为 true，则不嵌入字体。 |
| subset_fonts | 如果设置为 true，字体将被转换为子集。 |
| remove_private_info | 删除私人信息（页面片段信息）。 |
| image_encoding | 将使用的图像编码。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| all() | 创建已激活所有选项的优化策略。<br/>            请注意，仅激活不会更改文档任何功能的选项。<br/>            即图像压缩和字体取消嵌入将不会启用（可手动嵌入）。 |

### 另请参阅

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

