---
title: "MovieAnnotation"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示包含动画图形和声音的电影注释，这些内容将在计算机屏幕和扬声器上呈现。激活注释时，电影将播放。"
type: docs
weight: 480
url: /zh/python-net/aspose.pdf.annotations/movieannotation/
---

## MovieAnnotation class

表示包含动画图形和声音的电影注释，这些内容将在计算机屏幕和扬声器上呈现。激活注释时，电影将播放。

MovieAnnotation 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| MovieAnnotation(document, movie_file) | 初始化 MovieAnnotation 类的新实例 |
| MovieAnnotation(page, rect, movie_file) | 初始化 MovieAnnotation 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| vertical_alignment | 获取或设置段落的垂直对齐方式 |
| horizontal_alignment | 获取或设置注释的文本对齐方式。 |
| margin | 获取或设置段落的外边距（用于 PDF 生成） |
| is_first_paragraph_in_column | 获取或设置一个布尔值，指示此段落是否将在下一列。<br/>            默认值为 false。（用于 PDF 生成） |
| is_kept_with_next | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。<br/>            默认值为 false。（用于 PDF 生成） |
| is_in_new_page | 获取或设置一个布尔值，强制此段落在新页面生成。<br/>            默认值为 false。（用于 PDF 生成） |
| is_in_line_paragraph | 获取或设置段落是否为内联。<br/>            默认值为 false。（用于 PDF 生成） |
| hyperlink | 获取或设置片段超链接（用于 PDF 生成器）。 |
| z_index | 获取或设置一个整数值，指示 graph 的 Z 顺序。ZIndex 较大的 graph <br/>            将放置在 ZIndex 较小的 graph 之上。ZIndex 可以为负数。ZIndex 为负的 graph <br/>            将放置在页面文本的后面。 |
| update_appearance_on_convert | 如果为 true，注释外观将在将 PF 文档转换为图像之前更新。这可以正确转换字段，但可能需要更多时间。 |
| use_font_subset | 如果此属性设置为 true，字体将以子集形式添加到文档中。默认值为 true。 |
| flags | 注释的标志。 |
| annotation_type | 获取注释的类型。 |
| width | 获取或设置注释的宽度。 |
| actions | 获取注释操作的列表。 |
| 高度 | 获取或设置注释的高度。 |
| 矩形 | 获取或设置注释矩形。 |
| 内容 | 获取或设置注释文本。 |
| 名称 | 获取或设置页面上注释的名称。 |
| 已修改 | 获取或设置注释最近修改的日期和时间。 |
| 颜色 | 获取或设置注释颜色。 |
| border | 获取或设置注释边框特性。 [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| 激活状态 | 获取或设置当前注释外观状态。 |
| 特性 | 获取注释特性。 |
| 状态 | 获取注释的外观字典。 |
| 对齐 | 注释对齐方式。此属性已过时。请改用 HorizontalAligment。 |
| 文本水平对齐 | 获取或设置注释的文本对齐方式。 |
| 完整名称 | 获取注释的完全限定名称。 |
| 外观 | 获取该注释的外观字典。 |
| 页面索引 | 获取包含注释的页面索引。 |
| 标题 | 获取或设置电影注释的标题。 |
| file | 获取或设置用于标识自描述电影文件的文件规范。 |
| poster | 获取或设置一个标志或流，用于指定是否以及如何显示代表电影的海报图像。如果为 true，则从电影文件中检索海报图像；如果为 false，则不显示海报。 |
| aspect | 获取或设置电影边界框的宽度和高度（单位为像素）。 |
| rotate | 获取或设置电影相对于页面顺时针旋转的角度数。该值必须是 90 的倍数。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| clone() | 克隆此实例。<br/>            虚拟方法。始终返回 null。 |
| get_rectangle(consider_rotation) | 返回考虑页面旋转后的注释矩形。 |
| accept(visitor) | 接受访问者对象以处理该注释。 |
| flatten() | 将注释内容直接放置在页面上，<br/>            注释对象将被移除。 |
| change_after_resize(transform) | 根据矩阵变换更新参数和外观。 |

### 另请参阅

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

