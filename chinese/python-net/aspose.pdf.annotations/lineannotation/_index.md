---
title: "LineAnnotation"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "类表示线条注释。"
type: docs
weight: 380
url: /zh/python-net/aspose.pdf.annotations/lineannotation/
---

## LineAnnotation class

类表示线条注释。

LineAnnotation 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| LineAnnotation(document, start, end) | 初始化 LineAnnotation 类的新实例 |
| LineAnnotation(page, rect, start, end) | 初始化 LineAnnotation 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| vertical_alignment | None |
| horizontal_alignment | 获取或设置注释的文本对齐方式。 |
| margin | None |
| is_first_paragraph_in_column | None |
| is_kept_with_next | None |
| is_in_new_page | None |
| is_in_line_paragraph | None |
| hyperlink | None |
| z_index | None |
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
| 标题 | 获取或设置将在注释标题栏中显示的文本。 |
| rich_text | 获取或设置在打开注释时显示在弹出窗口中的富文本字符串。 |
| creation_date | 获取注释创建的日期和时间。 |
| subject | 获取表示对象描述的文本。 |
| popup | 用于输入或编辑与此注释关联的文本的弹出注释。 |
| opacity | 获取或设置用于绘制注释的常量不透明度值。 |
| in_reply_to | 对该注释所“回复”的注释的引用。<br/>            两个注释必须位于文档的同一页。 |
| reply_type | 一个字符串，指定此注释（"reply type"）与 InReplyTo 指定的注释之间的关系。<br/>             |
| starting | 获取或设置线的起始点。 |
| starting_style | 获取或设置线起始点的结束样式。 |
| ending | 获取或设置线的结束点。 |
| ending_style | 获取或设置线终点的结束样式。 |
| interior_color | 获取或设置注释的内部颜色。 |
| leader_line | 获取或设置引导线长度。 |
| leader_line_extension | 获取或设置引导线延伸的长度。 |
| show_caption | 获取或设置布尔标志，决定内容是否必须显示为标题。 |
| leader_line_offset | 获取或设置引导线偏移量。 |
| caption_offset | 获取或设置标题文本相对于其正常位置的偏移量。 |
| caption_position | 获取或设置注释标题位置。 |
| measure | 此注释指定的测量单位。 |
| intent | 获取或设置线注释的意图。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| clone() | None |
| get_rectangle(consider_rotation) | 返回考虑页面旋转后的注释矩形。 |
| accept(visitor) | 接受访问者进行注释处理。 |
| flatten() | 将注释内容直接放置在页面上，<br/>            注释对象将被移除。 |
| change_after_resize(transform) | 根据矩阵变换更新起始点和结束点。 |

### 另请参阅

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

