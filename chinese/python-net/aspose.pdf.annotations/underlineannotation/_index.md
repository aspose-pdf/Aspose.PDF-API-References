---
title: "UnderlineAnnotation"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示在文档文本中出现下划线的下划线注释。"
type: docs
weight: 850
url: /zh/python-net/aspose.pdf.annotations/underlineannotation/
---

## UnderlineAnnotation class

表示在文档文本中出现下划线的下划线注释。

UnderlineAnnotation 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| UnderlineAnnotation(page, rect) | 初始化 UnderlineAnnotation 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| vertical_alignment | None |
| horizontal_alignment | None |
| margin | None |
| is_first_paragraph_in_column | None |
| is_kept_with_next | None |
| is_in_new_page | None |
| is_in_line_paragraph | None |
| hyperlink | None |
| z_index | None |
| update_appearance_on_convert | None |
| use_font_subset | None |
| flags | None |
| annotation_type | 获取注释的类型。 |
| width | None |
| actions | None |
| 高度 | None |
| 矩形 | None |
| 内容 | None |
| 名称 | None |
| 已修改 | None |
| 颜色 | None |
| 边框 | None |
| 激活状态 | None |
| 特性 | None |
| 状态 | None |
| 对齐 | None |
| 文本水平对齐 | None |
| 完整名称 | None |
| 外观 | None |
| 页面索引 | None |
| 标题 | 获取或设置将在注释标题栏中显示的文本。 |
| rich_text | 获取或设置在打开注释时显示在弹出窗口中的富文本字符串。 |
| creation_date | 获取注释创建的日期和时间。 |
| subject | 获取表示对象描述的文本。 |
| popup | 用于输入或编辑与此注释关联的文本的弹出注释。 |
| opacity | 获取或设置用于绘制注释的常量不透明度值。 |
| in_reply_to | 对该注释所“回复”的注释的引用。<br/>            两个注释必须位于文档的同一页。 |
| reply_type | 一个字符串，指定此注释（"reply type"）与 InReplyTo 指定的注释之间的关系。<br/>             |
| quad_points | 获取或设置一个点数组，用于指定 n 个四边形的坐标。每个四边形包含注释底层文本中的一个单词或一组连续的单词。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| clone() | None |
| get_rectangle(consider_rotation) | None |
| accept(visitor) | 接受访问者对象以处理该注释。 |
| flatten() | None |
| change_after_resize(transform) | 根据矩阵变换更新 QuadPoints。 |
| get_marked_text() | 获取标记注释下的文本，作为字符串。 |
| get_marked_text_fragments() | 获取标记注释下的文本，作为 [TextFragmentCollection](/pdf/python-net/aspose.pdf.text/textfragmentcollection/)。 |

### 另请参阅

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

