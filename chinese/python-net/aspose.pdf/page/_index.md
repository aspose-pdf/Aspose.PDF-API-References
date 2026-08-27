---
title: "Page"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "类表示 PDF 文档的页面。"
type: docs
weight: 1080
url: /zh/python-net/aspose.pdf/page/
---

## Page class

类表示 PDF 文档的页面。

Page 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| is_add_paragraphs_after_last | 获取或设置在页面最后一个段落之后添加段落的行为 |
| background_image | 获取或设置页面的背景图像（仅用于生成器，在读取文档时不填充）。 |
| toc_info | 获取或设置目录信息。 |
| 页眉 | 获取或设置页面页眉。 |
| 图层 | 获取或设置图层集合。 |
| 页脚 | 获取或设置页面页脚。 |
| paragraphs | 获取段落。 |
| page_info | 获取或设置页面信息（仅用于生成器，读取文档时不填充）。 |
| 矩形 | 获取或设置页面矩形。<br/>            获取时：如果指定，则返回页面裁剪框，否则返回页面媒体框。<br/>            设置时：始终设置页面媒体框。<br/>            请注意，此属性不考虑页面旋转。若需获取考虑旋转的页面矩形，请使用 ActualRect。 |
| color_type | 根据从运算符 SetColor、图像和表单获取的信息设置页面的颜色类型。<br/>             |
| note_line_style | 获取或设置注释的线条样式。（仅用于生成器，读取文档时不填充） |
| tab_order | 获取或设置页面的制表顺序。 <br/>            可选值：Row、Column。默认，Manual |
| duration | 获取或设置页面显示持续时间。这是页面在演示期间显示的秒数。<br/>            如果未定义持续时间，则返回 -1。 |
| contents | 获取页面内容流中的运算符集合。<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| 组 | 获取或设置一个组属性类，指定页面的页面组属性，以用于透明成像模型。 |
| annotations | 获取页面注释的集合。<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | 获取页面资源。Resources 对象包含图像、表单和字体的集合。<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| rotate | 获取或设置页面的旋转。 |
| trim_box | 获取或设置页面的裁剪框。 |
| art_box | 获取或设置页面的 art box。 |
| bleed_box | 获取或设置页面的 bleed box。 |
| crop_box | 获取或设置页面的 crop box。 |
| media_box | 获取或设置页面的 media box。 |
| number | 获取页面的编号。 |
| rotation_matrix | 获取页面的变换矩阵。 |
| background | 获取或设置页面的背景颜色。 |
| watermark | 获取或设置页面的水印。 |
| artifacts | 获取页面上 artifacts 的集合。 |
| actions | 获取页面属性的集合。 |
| fields_in_tab_order | 获取此页面上按 Tab 顺序排列的 Field 对象列表。 |
| user_unit | 获取或设置 UserUnit 值。一个正数，表示默认用户空间单位的大小，以 1 ⁄ 72 英寸的倍数计。<br/>默认值为 1。请设置为零或负数以清除页面中的此条目。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| send_to(device, output) | 将页面发送到给定的页面设备进行处理。 |
| send_to(device, output_file_name) | 将页面发送到给定的页面设备进行处理。 |
| accept(visitor) | 接受 [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) 访问器对象，提供处理注释的功能。 |
| accept(visitor) | 接受 [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 访问器对象，提供处理文本对象的功能。 |
| accept(visitor) | 接受 [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) 访问器对象，提供处理图像放置对象的功能。 |
| accept(visitor) | 接受 [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) 访问器对象，提供处理文本对象的功能。 |
| add_image(image_stream, image_rect) | 将图像添加到页面，并将其放置在指定矩形的中心，同时保持图像的比例。 |
| add_image(hocr, image_stream, image_rect) | 在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。 |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | 在页面上添加图像，并根据图像矩形的位置放置它。 |
| add_image(image_path, rectangle) | 在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。 |
| is_blank(fill_threshold_factor) | 获取页面是否为空的标志。 |
| get_page_rect(consider_rotation) | 返回页面的矩形，依据其 CropBox（如果 CropBox 为 null，则使用 MediaBox）。 |
| calculate_content_b_box() | 计算 bbox 值——包含内容且不含可见边距的矩形。 |
| rotation_to_int(rotation) | 将 rotation 枚举成员转换为整数值。 |
| int_to_rotation(rotation) | 将整数值转换为相应的 rotation 枚举成员。 |
| add_stamp(stamp) | 在页面上放置印章。印章可以是页码、图像或简单文本，例如某个徽标。 |
| flatten() | 删除页面上所有字段，并用它们的值替代。 |
| set_page_size(width, height) | 设置页面的尺寸。 |
| make_grayscale() | 将页面转换为灰度。 |
| free_memory() | 清除缓存数据 |
| get_notifications() | 返回有关页面内容内部操作的通知。（目前仅支持文本添加场景中段落事件的通知。） |
| as_byte_array(resolution) | 将当前页面转换为位图，然后返回字节数组。 |
| as_xml() | 将当前页面转换为 UTF-8 编码的 XML。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

