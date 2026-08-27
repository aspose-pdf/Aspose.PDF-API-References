---
title: "Form"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示 Acro 表单对象的类。"
type: docs
weight: 80
url: /zh/python-net/aspose.pdf.facades/form/
---

## Form class

表示 Acro 表单对象的类。

Form 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Form(src_stream, dest_stream) | 初始化 Form 类的新实例 |
| Form() | Form 的无参数构造函数。 |
| Form(src_file_name) | 初始化 Form 类的新实例 |
| Form(src_stream) | 初始化 Form 类的新实例 |
| Form(src_file_name, dest_file_name) | 初始化 Form 类的新实例 |
| Form(src_file_name, dest_stream) | 初始化 Form 类的新实例 |
| Form(src_stream, dest_file_name) | 初始化 Form 类的新实例 |
| Form(document) | 初始化 Form 类的新实例 |
| Form(document, dest_file_name) | 初始化 Form 类的新实例 |
| Form(document, dest_stream) | 初始化 Form 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| import_result | 上一次导入操作的结果。一个对象数组，描述每个字段的导入结果。 |
| src_file_name | 获取或设置源文件名。 |
| dest_file_name | 获取或设置目标文件名。 |
| src_stream | 获取或设置源流。 |
| dest_stream | 获取或设置目标流。 |
| field_names | 获取表单上的字段名称列表。 |
| form_submit_button_names | 获取所有表单提交按钮的名称。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_file) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_stream) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save() | 保存已填写字段的值并关闭打开的 PDF 文档。 |
| save(dest_file) | 将文档保存到指定文件。 |
| save(dest_stream) | 将文档保存到指定流。 |
| fill_field(field_name, field_value) | 根据完整限定的字段名称为字段填充值。<br/>            在填充字段之前，必须已知每个字段的名称及其对应的有效值。<br/>            字段名称和值均区分大小写。<br/>            请注意，Aspose.Pdf.Facades 仅支持完整字段名称，不支持部分 <br/>            字段名称，这与 Aspose.Pdf.Kit 不同；<br/>            例如，如果字段的完整名称为 \"Form.Subform.TextField\"，则应指定完整名称，而不是 \"TextField\"。 <br/>            您可以使用 FieldNames 属性来浏览现有字段名称并通过部分名称搜索所需字段。 |
| fill_field(field_name, index) | 根据完整限定的字段名称为单选框字段填充有效的索引值。<br/>            填充字段之前，只需知道字段名称即可。值可以通过其索引指定。<br/>            注意：仅适用于单选框、组合框和列表框字段。<br/>            请注意，Aspose.Pdf.Facades 仅支持完整字段名称，不支持部分 <br/>            字段名称，这与 Aspose.Pdf.Kit 不同；<br/>            例如，如果字段的完整名称为 \"Form.Subform.ListBoxField\"，则应指定完整名称，而不是 \"ListBoxField\"。 <br/>            您可以使用 FieldNames 属性来浏览现有字段名称并通过部分名称搜索所需字段。 |
| fill_field(field_name, be_checked) | 使用布尔值填充复选框字段。<br/>            注意：仅适用于复选框。<br/>            请注意，Aspose.Pdf.Facades 仅支持完整字段名称，不支持部分 <br/>            字段名称，这与 Aspose.Pdf.Kit 不同；<br/>            例如，如果字段的完整名称为 \"Form.Subform.CheckBoxField\"，则应指定完整名称，而不是 \"CheckBoxField\"。 <br/>            您可以使用 FieldNames 属性来浏览现有字段名称并通过部分名称搜索所需字段。 |
| fill_field(field_name, field_values) | 使用文本值填充文本框字段并保存文档。<br/>            与已签名的文档相关。<br/>            注意：仅适用于文本框。<br/>            字段名称和值均区分大小写。 |
| fill_field(field_name, value, fit_font_size) | 使用布尔值填充复选框字段。<br/>            注意：仅适用于复选框。<br/>            请注意，Aspose.Pdf.Facades 仅支持完整字段名称，不支持部分 <br/>            字段名称，这与 Aspose.Pdf.Kit 不同；<br/>            例如，如果字段的完整名称为 \"Form.Subform.CheckBoxField\"，则应指定完整名称，而不是 \"CheckBoxField\"。 <br/>            您可以使用 FieldNames 属性来浏览现有字段名称并通过部分名称搜索所需字段。 |
| import_xml(input_xml_stream) | 从 XML 文件导入字段内容并将其放入新的 PDF 中。 |
| import_xml(input_xml_stream, ignore_form_template_changes) | 从 XML 文件导入字段内容并将其放入新的 PDF 中。 |
| fill_image_field(field_name, image_file_name) | 根据 <br/>            完整限定的字段名称，将图像粘贴到现有按钮字段上作为其外观。 |
| fill_image_field(field_name, image_stream) | FillImageField 的重载函数。<br/>            输入为图像流。 |
| close() | 关闭已打开的文件而不做任何更改。 |
| get_field_facade(field_name) | 返回包含所有外观属性的 FrogmFieldFacade 对象。 |
| fill_fields(field_names, field_values, output) | 使用文本值填充文本框字段并保存文档。<br/>            与已签名的文档相关。<br/>            注意：仅适用于文本框。<br/>            字段名称和值均区分大小写。 |
| get_button_option_current_value(field_name) | 返回单选按钮选项字段的当前值。 |
| get_field(field_name) | 返回包含所有外观属性的 FrogmFieldFacade 对象。 |
| get_full_field_name(field_name) | 根据其简短字段名获取完整字段名。 |
| get_field_limit(field_name) | 获取文本字段的限制。 |
| flatten_all_fields() | 将所有字段展平。 |
| flatten_field(field_name) | 将指定字段使用完全限定的字段名展平。<br/>            任何其他字段将保持不变。如果 fieldName 无效，<br/>            所有字段将保持不变。 |
| fill_barcode_field(field_name, data) | 根据完全限定的字段名填写条形码字段。 |
| import_fdf(input_fdf_stream) | 从 fdf 文件导入字段内容并放入新的 pdf。 |
| export_fdf(output_fdf_stream) | 将 pdf 中字段的内容导出到 fdf 流。 |
| export_xml(output_xml_stream) | 将 pdf 中字段的内容导出到 xml 流。<br/>            按钮字段的值将不会被导出。 |
| extract_xfa_data(output_xml_stream) | 提取 XFA 数据包 |
| set_xfa_data(input_xml_stream) | 使用指定的数据包替换 XFA 数据。数据包可使用 ExtractXfaData 提取。 |
| import_xfdf(input_xfdf_stream) | 从 xfdf(xml) 文件导入字段内容并放入新的 pdf。 |
| export_xfdf(output_xfdf_stream) | 将 pdf 中字段的内容导出到 xml 流。<br/>            按钮字段的值将不会被导出。 |
| rename_field(field_name, new_field_name) | 重命名字段。AcroForm 字段或 XFA 字段均可。 |
| get_rich_text(field_name) | 获取富文本字段的值，包括每个字符的格式信息。 |
| get_submit_flags(field_name) | 返回提交按钮的提交标志。 |
| get_field_type(field_name) | 返回字段的类型。 |
| is_required_field(field_name) | 确定字段是否为必填。 |
| get_field_flag(field_name) | 返回字段的标志。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

