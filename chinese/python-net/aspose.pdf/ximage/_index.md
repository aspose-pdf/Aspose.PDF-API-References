---
title: "XImage"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示图像 X-Object 的类。"
type: docs
weight: 1680
url: /zh/python-net/aspose.pdf/ximage/
---

## XImage class

表示图像 X-Object 的类。

XImage 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| contains_transparency | 如果图像包含透明度则返回 true；否则返回 false。 |
| grayscaled | 获取图像的灰度版本。 |
| filter_type | 获取图像过滤器类型。 |
| width | 获取图像的宽度。 |
| 高度 | 获取图像的高度。 |
| 名称 | 获取或设置图像名称。请注意，如果更改在页面内容中有引用的图像名称，文档可能会变得不正确。在这种情况下请使用 XImage.Rename 方法。 |
| 元数据 | 图像的元数据。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| save(stream) | 将图像数据以 JPEG 格式保存到流中。 |
| save(stream, format) | 按请求的格式将图像保存到流中。 |
| save(stream, resolution) | 将图像数据以指定分辨率的 JPEG 格式保存到流中。 |
| save(stream, format, resolution) | 按请求的格式并使用指定分辨率将图像保存到流中。 |
| rename(name) | 重命名图像并将所有对该图像的引用替换为新名称 |
| get_color_type() | 返回图像的颜色类型。 |
| detect_color_type(bmp) | 返回图像的颜色类型。 |
| is_the_same_object(image) | 如果两个图像引用同一对象，则返回 true。 |
| get_name_in_collection() | 返回图像在 ints 集合中的名称。 |
| to_stream() | 返回原始图像流。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

