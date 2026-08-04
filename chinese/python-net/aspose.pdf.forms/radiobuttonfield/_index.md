---
title: "RadioButtonField"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示单选按钮字段的类。"
type: docs
weight: 220
url: /zh/python-net/aspose.pdf.forms/radiobuttonfield/
---

## RadioButtonField class

表示单选按钮字段的类。

RadioButtonField 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| RadioButtonField(page) | 初始化 RadioButtonField 类的新实例 |
| RadioButtonField(doc) | 初始化 RadioButtonField 类的新实例 |
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
| annotation_type | None |
| width | None |
| actions | None |
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
| 页面索引 | 获取包含此 RadioButton 字段的页面索引。 |
| 激活时 | None |
| 高亮 | None |
| 父级 | None |
| 默认外观 | None |
| 只读 | None |
| 必需 | None |
| 可导出 | None |
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
| commit_immediately | 获取或设置在选择更改时提交的标志。 |
| multi_select | 获取或设置多选标志。 |
| selected | 获取或设置所选项的索引。项目编号从 1 开始。 |
| selected_items | 获取或设置所选项目的数组。对于多选列表，数组包含多个项目。对于单选列表，数组仅包含一个项目。 |
| options | 获取单选按钮的选项集合。 |
| style | 字段框的样式。 |
## Indexer
| 名称 | 描述 |
| :- | :- |
| [index] | 按索引获取此字段中包含的子字段。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| add_option(option_name, rect) | 向单选按钮选项添加具有指定矩形的项。 |
| add_option(option_name) | 向单选按钮选项添加具有指定矩形的项。 |
| add_option(export, name) | 向单选按钮选项添加具有指定矩形的项。 |
| clone() | None |
| get_rectangle(consider_rotation) | None |
| accept(visitor) | None |
| flatten() | 移除此字段并将其值直接放置在页面上。 |
| change_after_resize(transform) | None |
| recalculate() | 重新计算表单上所有已计算字段。 |
| copy_to(array, index) | 将此字段的子字段复制到数组中，从指定索引开始。 |
| set_position(point) | 将单选按钮的所有子项移动到页面上指定的位置。 |
| delete_option(option_name) | 通过名称删除选项。 |
| add(new_item) | 向 RadioButton 字段添加新的选项字段 |

### 另请参阅

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

