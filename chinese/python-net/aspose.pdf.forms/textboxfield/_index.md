---
title: "TextBoxField"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示文本框字段的类。"
type: docs
weight: 280
url: /zh/python-net/aspose.pdf.forms/textboxfield/
---

## TextBoxField class

表示文本框字段的类。

TextBoxField 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| TextBoxField(doc) | 初始化 TextBoxField 类的新实例 |
| TextBoxField() | 创建 TextBoxField 的实例。 |
| TextBoxField(page, rect) | 初始化 TextBoxField 类的新实例 |
| TextBoxField(doc, rect) | 初始化 TextBoxField 类的新实例 |
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
| actions | 获取注释的操作。 |
| 高度 | None |
| 矩形 | 获取或设置字段矩形。 |
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
| 页面索引 | 获取包含此字段的页面索引。 |
| 激活时 | 当注释被激活时应执行的操作。 |
| 高亮 | 注释高亮模式。 |
| 父级 | 获取注释的父级。 |
| 默认外观 | 获取或设置字段的默认外观。 |
| 只读 | 获取或设置字段的只读状态。 |
| 必需 | 获取或设置字段的必填状态。 |
| 可导出 | 获取或设置字段的可导出标志。 |
| partial_name | 获取或设置字段的部分名称。 |
| alternate_name | 获取或设置字段的备用名称（备用字段 <br/>            名称应在实际字段名称的位置使用 <br/>            在用户界面中标识字段的任何地方）。<br/>            备用名称在 Adobe Acrobat 中用作字段工具提示。 |
| mapping_name | 获取或设置字段的映射名称，该名称将在从文档导出交互式表单字段数据时使用。 |
| 值 | 获取或设置字段的值。 |
| is_synchronized | 如果字典已同步则返回 true。 |
| sync_root | 同步对象。 |
| is_group | 获取或设置布尔值，以指示此字段是否为非终端字段，即字段组。 |
| annotation_index | 获取或设置此注释在页面上的索引。 |
| is_shared_field | 用于 Generator 支持的属性。字段添加到页眉或页脚时使用。如果为 true，则该字段仅创建一次，其外观将在文档的所有页面上可见。如果为 false，则为文档的每一页创建单独的字段。 |
| fit_into_rectangle | 如果为 true，则字体大小将缩小以适应指定的矩形。 |
| max_font_size | 可用于字段内容的最大字体大小。-1 表示不检查大小。 |
| min_font_size | 可用于字段内容的最小字体大小。-1 表示不检查大小。 |
| tab_order | 获取或设置字段的制表顺序。 |
| multiline | 获取或设置字段的多行标志。如果 Multiline 为 true，字段可以包含多行文本。 |
| spell_check | 获取或设置字段的拼写检查标志。如果为 true，则对字段进行拼写检查。 |
| scrollable | 获取或设置字段的可滚动标志。如果为 true，字段可以滚动。 |
| force_combs | 获取或设置指示字段是否被划分为间隔位置的标志。 |
| max_len | 获取或设置字段中文本的最大长度。 |
| text_vertical_alignment | 获取或设置注释的文本垂直对齐方式。 |
## Indexer
| 名称 | 描述 |
| :- | :- |
| [index] | 按索引获取此字段中包含的子字段。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| clone() | None |
| get_rectangle(consider_rotation) | None |
| accept(visitor) | 接受访问者。 |
| flatten() | 移除此字段并将其值直接放置在页面上。 |
| change_after_resize(transform) | None |
| recalculate() | 重新计算表单上所有已计算字段。 |
| copy_to(array, index) | 将此字段的子字段复制到数组中，从指定索引开始。 |
| set_position(point) | 设置字段的位置。 |
| add_image(image) | 将图像添加到字段资源并绘制它。 |
| add_barcode(code) | 向字段中添加 barcode 128。 <br/> 字段值将被更改为该代码，且字段将变为只读。 |

### 另请参阅

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

