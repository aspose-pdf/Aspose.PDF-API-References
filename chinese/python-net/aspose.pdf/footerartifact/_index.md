---
title: "FooterArtifact"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "描述页脚工件。这可用于设置页面的页脚。"
type: docs
weight: 400
url: /zh/python-net/aspose.pdf/footerartifact/
---

## FooterArtifact class

描述页脚工件。这可用于设置页面的页脚。

FooterArtifact 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| FooterArtifact() | 创建 Footer Artifact 实例。 |
## 属性
| 名称 | 描述 |
| :- | :- |
| custom_type | 获取 artifact 类型的名称。如果 artifact 类型非标准，可使用此属性。 |
| custom_subtype | 获取 artifact 子类型的名称。如果 artifact 子类型不是标准子类型，可使用此属性。 |
| type | 获取 artifact 类型。 |
| subtype | 获取制品子类型。如果制品具有非标准子类型，可以通过 CustomSubtype 读取子类型的名称。 |
| 内容 | 获取制品内部运算符的集合。 |
| form | 获取制品的 XForm（如果使用 XForm）。 |
| rectangle | 获取制品的矩形。 |
| position | 获取或设置制品位置。<br/>            如果指定了此属性，则边距和对齐方式将被忽略。 |
| right_margin | 制品的右边距。 <br/>            如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| left_margin | 制品的左边距。 <br/>            如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| top_margin | 制品的上边距。 <br/>            如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| bottom_margin | 制品的下边距。 <br/>            如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| artifact_horizontal_alignment | 制品的水平对齐方式。 <br/>            如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| artifact_vertical_alignment | 制品的垂直对齐方式。 <br/>            如果在 Position 属性中显式指定了位置，则此值将被忽略。 |
| rotation | 获取或设置制品的旋转角度。 |
| text | 获取制品的文本。 |
| image | 获取制品的图像（如果存在）。 |
| opacity | 获取或设置制品的不透明度。可能的取值范围为 0..1。 |
| lines | 多行文本制品的行数。 |
| text_state | 制品文本的文本状态。 |
| is_background | 如果为 true，制品将放置在页面内容之后。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| set_image(image_stream) | 设置 artifact 的图像。 |
| set_image(image_name) | 设置 artifact 的图像。 |
| set_text(formatted_text) | 设置 artifact 的文本。 |
| set_text_and_state(text, text_state) | 设置 artifact 的文本及文本属性。 |
| set_lines_and_state(text, text_state) | 设置 artifact 的文本及文本属性。允许指定多行。 |
| set_pdf_page(page) | 设置 PDF 页面，将其作为 artifact 放置在文档页上。 |
| get_value(name) | 获取 artifact 的自定义值。 |
| set_value(name, value) | 设置 artifact 的自定义值。 |
| remove_value(name) | 从 artifact 中移除自定义值。 |
| begin_updates() | 开始延迟更新。若需要对同一 artifact 进行多次更改以提升性能，请使用此功能。<br/>通常在 artifact 属性被更改时，artifact 操作器会随时被更改。这会导致页面内容在每次 artifact 更改时都被重新修改。<br/>为避免此效果，请将所有 artifact 更新放在 StartUpdates/SaveUpdates 调用之间。<br/>这使得页面内容仅修改一次。 |
| save_updates() | 保存在 BeginUpdates() 调用后对 artifact 所做的所有更新。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

