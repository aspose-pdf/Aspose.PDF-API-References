---
title: "PdfPageEditor"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示用于编辑 PDF 文件页面的类，包括旋转页面、缩放页面、移动位置和更改页面尺寸。"
type: docs
weight: 340
url: /zh/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

表示用于编辑 PDF 文件页面的类，包括旋转页面、缩放页面、移动位置和更改页面尺寸。

PdfPageEditor 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfPageEditor() | PdfPageEditor 类的构造函数。 |
| PdfPageEditor(document) | 初始化 PdfPageEditor 类的新实例。 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| transition_duration | 获取或设置过渡效果的持续时间。 |
| transition_type | 获取或设置在演示过程中从另一页切换到此页时使用的过渡样式。 |
| display_duration | 获取或设置页面的显示持续时间。 |
| process_pages | 获取或设置要编辑的页码。默认情况下，将编辑每一页。 |
| rotation | 获取或设置页面的旋转角度，旋转必须为 0、90、180 或 270。<br/>            默认值为 0。 |
| zoom | 获取或设置缩放系数。值 1.0 对应 100%。<br/>            默认值为 1.0。 |
| page_size | 获取或设置输出文件的页面大小。 |
| 对齐 | 获取或设置原始 PDF 内容在结果页上的水平对齐方式，默认值为 AlignmentType.Left。 |
| horizontal_alignment | 获取或设置原始 PDF 内容在结果页上的水平对齐方式，默认值为 AlignmentType.Left。 |
| vertical_alignment | 获取或设置原始 PDF 内容在结果页上的垂直对齐方式，默认值为 VerticalAlignmentType.Bottom。 |
| vertical_alignment_type | 获取或设置原始 PDF 内容在结果页上的垂直对齐方式，默认值为 VerticalAlignmentType.Bottom。 |
| SPLITVOUT | 垂直拆分输出 |
| SPLITHOUT | 向外水平拆分 |
| SPLITVIN | 向内垂直拆分 |
| SPLITHIN | 向内水平拆分 |
| BLINDV | 垂直百叶窗 |
| BLINDH | 垂直百叶窗 |
| INBOX | 向内盒子 |
| OUTBOX | 向外盒子 |
| LRWIPE | 左右擦拭 |
| RLWIPE | 右左擦拭 |
| BTWIPE | 底部到顶部擦拭 |
| TBWIPE | 顶部到底部擦拭 |
| DISSOLVE | 旧页面溶解 |
| LRGLITTER | 左右闪光 |
| TBGLITTER | 上下闪光 |
| DGLITTER | 对角闪光 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_file) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_stream) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save(output_file) | 将更改的文档保存到文件中。 |
| save(output_stream) | 将更改的文档保存到流中。 |
| close() | 释放与当前外观关联的所有资源。 |
| move_position(move_x, move_y) | 将原点从 (0, 0) 移动到指定的点。 <br/>            原点位于左下角，单位为点（1 英寸 = 72 点）。 |
| get_pages() | 返回页面的总数。 |
| get_page_size(page) | 返回指定页面的页面大小。 |
| get_page_rotation(page) | 返回指定页面的旋转角度。 |
| get_page_box_size(page, page_box_name) | 返回文档中指定框的大小。 |
| apply_changes() | 应用对文档页面所做的更改。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

