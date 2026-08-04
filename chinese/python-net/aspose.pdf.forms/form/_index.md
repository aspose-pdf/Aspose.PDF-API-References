---
title: "Form"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示表单对象的类。"
type: docs
weight: 110
url: /zh/python-net/aspose.pdf.forms/form/
---

## Form class

表示表单对象的类。

Form 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| is_synchronized | 如果对象是线程安全的则返回 true。 |
| sync_root | 返回同步对象。 |
| auto_recalculate | 如果设置，则在任意字段更改时会重新计算所有表单字段。默认值为 true。将其设为 false 可在填充包含大量计算字段的表单时提升性能。 |
| auto_restore_form | 如果设置，缺失的表单字段将在注释中出现时自动创建。 |
| default_resources | 获取放置在此表单上的默认资源。 |
| 默认外观 | 获取或设置表单的默认外观（描述表单字段默认字体、文字大小和颜色的对象）。 |
| xfa | 获取表单的 XFA 数据（如果存在）。 |
| ignore_needs_rendering | 如果此属性为 true，则在将 XFA 表单转换为标准表单期间会忽略 NeedsRendering 键的值。<br/>默认值为 false。 |
| remove_permission | 如果此属性为 true，则在将动态文档转换为标准文档后，pdf 文档中的 "Perms" 字典将被移除。<br/>"Perms" 字典可能包含会干扰 Adobe Acrobat Reader 中必填字段显示选择的规则。<br/>默认值为 false。 |
| emulate_requierd_groups | 如果此属性为 true，则会为必需的 Xfa exclGroup 元素容器绘制额外的红色边框矩形。<br/>引入此属性是因为在将 Xfa 表单表示转换为标准表单时缺少 exclGroup 的对应实现。<br/>默认值为 false。 |
| type | 获取表单的类型。可能的值有：Standard、Static、Dynamic。 |
| 字段 | 获取层次结构表单最低级别中所有字段的列表。 |
| signatures_exist | 如果设置，则文档至少包含一个签名字段。 |
| signatures_append_only | 如果设置，则文档包含的签名可能会在文件以改变其先前内容的方式保存（写入）时失效，<br/>            而不是增量更新。 |
| sign_dependent_elements_rendering_mode_when_converted | 表单可以包含签名信息，即可以是已签名或未签名。<br/>              表单的视图有时必须取决于表单是否已签名。<br/>              此属性告诉表单转换器（例如在将 XFA 表单转换为 Standard 表单期间）<br/>              结果表单是否必须渲染为已签名或未签名。 |
## Indexer
| 名称 | 描述 |
| :- | :- |
| [index] | 通过字段索引获取表单的字段。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| delete(field) | 从表单中删除字段。 |
| delete(field_name) | 通过字段名称从表单中删除字段。 |
| add(field, page_number) | 在表单上添加字段。 |
| add(field) | 在表单上添加字段。 |
| add(field, partial_name, page_number) | 向表单添加新字段；如果此字段已放置在其他表单或当前表单上，则会创建该字段的副本。 |
| has_field(field) | 检查表单是否已经拥有指定的字段。 |
| has_field(field_name) | 确定具有指定名称的字段是否已添加到表单中。 |
| copy_to(array, index) | 将放置在表单上的字段复制到数组中。 |
| flatten() | 移除所有表单字段并将其值直接放置在页面上。 |
| add_field_appearance(field, page_number, rect) | 在文档的指定位置向指定页面添加字段的额外外观。 |
| get_fields_in_rect(rect) | 返回指定矩形内的字段。 |

### 另请参阅

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

