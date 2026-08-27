---
title: "FormEditor"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "用于编辑表单（添加/删除字段等）的类。"
type: docs
weight: 110
url: /zh/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

用于编辑表单（添加/删除字段等）的类。

FormEditor 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| FormEditor(src_stream, dest_stream) | 初始化 FormEditor 类的新实例 |
| FormEditor(src_file_name, dest_file_name) | 初始化 FormEditor 类的新实例 |
| FormEditor() | FormEditor 的构造函数。 |
| FormEditor(document) | 初始化 FormEditor 类的新实例 |
| FormEditor(document, dest_file_name) | 初始化 FormEditor 类的新实例 |
| FormEditor(document, dest_stream) | 初始化 FormEditor 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| src_file_name | 获取或设置源文件的名称。 |
| dest_file_name | 获取或设置目标文件名。 |
| src_stream | 获取或设置源流。 |
| dest_stream | 获取或设置目标流。 |
| items | 设置 items，这些 items 将被添加到新创建的列表框或组合框。 |
| export_items | 设置具有导出值的组合框选项。 |
| facade | 设置字段的可视属性。 |
| radio_gap | 成员用于记录两个相邻单选按钮之间的像素间距，默认值为 50。 |
| radio_horiz | 标志指示单选按钮是水平排列还是垂直排列，默认值为 true。 |
| radio_button_item_size | 获取或设置单选按钮项的大小（当添加新的单选按钮字段时）。 |
| submit_flag | 设置提交按钮的提交标志 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_file) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_stream) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save() | 将更改保存到目标文件中。 |
| save(dest_file) | 将更改保存到目标文件中。 |
| save(dest_stream) | 将更改保存到目标文件中。 |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | 向表单添加指定类型的字段。 |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | 向表单添加指定类型的字段。 |
| copy_inner_field(field_name, new_field_name, page_num) | 将现有字段复制到指定页码的相同位置。<br/>            将生成一个新文档，其中包含源文档的所有内容，除了新复制的字段。 |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | 将现有字段复制到由页码和坐标共同指定的新位置。<br/>            将生成一个新文档，其中包含源文档的所有内容，除了新复制的字段。 |
| copy_outer_field(src_file_name, field_name) | 将一个 PDF 文档中的现有字段复制到另一个文档，保持原始页码和坐标。<br/>            注意：仅适用于 AcroForm 字段（不包括单选框）。 |
| copy_outer_field(src_file_name, field_name, page_num) | 将一个 PDF 文档中的现有字段复制到另一个文档，使用指定的页码和原始坐标。<br/>             注意：仅适用于 AcroForm 字段（不包括单选框）。 |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | 将一个 PDF 文档中的现有字段复制到另一个文档，使用指定的页码和坐标。<br/>            注意：仅适用于 AcroForm 字段（不包括单选框）。 |
| decorate_field(field_name) | 更改指定字段的可视属性。 |
| decorate_field(field_type) | 更改所有具有指定字段类型的字段的可视属性。 |
| decorate_field() | 更改指定字段的可视属性。 |
| add_list_item(field_name, item_name) | 向列表框添加新项。 |
| add_list_item(field_name, export_name) | 向现有列表框字段添加具有导出值的新项，仅适用于 AcroForm 组合框字段。 |
| close() | 关闭外观。 |
| set_field_attribute(field_name, flag) | 设置字段的属性。 |
| set_field_appearance(field_name, flags) | 设置字段标志 |
| get_field_appearance(field_name) | 获取字段标志。 |
| set_submit_flag(field_name, submit_form_flag) | 设置提交按钮的提交标志。 |
| set_submit_url(field_name, url) | 设置按钮的 URL。 |
| set_field_limit(field_name, field_limit) | 设置文本字段的最大字符数。 |
| set_field_comb_number(field_name, comb_number) | 设置常规单行文本字段的梳子数量（该字段会 <br/> 自动划分为与 combNumber 参数值等量的等间距位置，或称为梳子， <br/>）。 |
| move_field(field_name, llx, lly, urx, ury) | 设置字段的新位置。 |
| remove_field(field_name) | 从表单中移除字段。 |
| reset_facade() | 将所有可视属性重置为空值。 |
| reset_inner_facade() | 将内部外观的所有可视属性重置为空值。 |
| rename_field(field_name, new_field_name) | 更改字段的名称。 |
| remove_field_action(field_name) | 移除字段的提交操作。 |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | 在表单上添加提交按钮。 |
| del_list_item(field_name, item_name) | 从列表字段中删除项目。 |
| set_field_script(field_name, script) | 为 PushButton 字段设置 JavaScript。如果存在旧的 JavaScript，将被新代码替换。 |
| add_field_script(field_name, script) | 为 PushButton 字段添加 JavaScript。如果旧事件存在，新事件将在其后添加。 |
| single_2_multiple(field_name) | 将单行文本字段更改为多行。 |
| set_field_alignment(field_name, alignment) | 设置文本字段的对齐样式。 |
| set_field_alignment_v(field_name, alignment) | 设置文本字段的垂直对齐样式。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

