---
title: "TextStamp"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示文本印章。"
type: docs
weight: 1550
url: /zh/python-net/aspose.pdf/textstamp/
---

## TextStamp class

表示文本印章。

TextStamp 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| TextStamp(value) | 初始化 TextStamp 类的新实例 |
| TextStamp(value, text_state) | 初始化 TextStamp 类的新实例 |
| TextStamp(formatted_text) | 初始化 TextStamp 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| background | 设置或获取一个布尔值，指示内容是否作为背景进行盖章。<br/>            如果该值为 true，盖章内容放置在底部。<br/>            默认情况下，该值为 false，盖章内容放置在顶部。 |
| opacity | 获取或设置一个值，以指示盖章的不透明度。该值范围为 0.0 到 1.0。<br/>            默认情况下，该值为 1.0。 |
| outline_opacity | 获取或设置一个值，以指示盖章轮廓的不透明度。该值范围为 0.0 到 1.0。<br/>            默认情况下，该值为 1.0。 |
| outline_width | 获取或设置盖章轮廓宽度的值。<br/>            默认情况下，该值为 1.0。 |
| rotate | 设置或获取盖章内容的旋转角度，依据 [Rotation](/pdf/python-net/aspose.pdf/rotation/) 的取值。<br/>            注意：此属性用于设置 90 度的整数倍角度（0、90、180、270 度）。<br/>            若要设置任意角度，请使用 RotateAngle 属性。<br/>            如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。 |
| x_indent | 水平盖章坐标，起始于左侧。 |
| y_indent | 垂直盖章坐标，起始于底部。 |
| horizontal_alignment | 获取或设置盖章在页面上的水平对齐方式。 |
| vertical_alignment | 获取或设置盖章在页面上的垂直对齐方式。 |
| left_margin | 获取或设置盖章的左边距。 |
| right_margin | 获取或设置盖章的右边距。 |
| bottom_margin | 获取或设置盖章的底部边距。 |
| top_margin | 获取或设置盖章的顶部边距。 |
| zoom_x | 印章的水平缩放因子。允许水平缩放印章。 |
| width | 页面上印章的期望宽度。 |
| 高度 | 页面上印章的期望高度。 |
| zoom_y | 印章的垂直缩放因子。允许垂直缩放印章。 |
| zoom | 印章的缩放因子。允许缩放印章。<br/>            请注意，属性对 ZoomX 和 ZoomY 允许分别为每个轴设置缩放因子。 <br/>            设置此属性会同时更改 ZoomX 和 ZoomY 属性。 <br/>            如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 的值。 |
| rotate_angle | 获取或设置印章的旋转角度（单位：度）。<br/>            此属性允许设置任意旋转角度。 |
| draw | 此属性决定印章在页面上的绘制方式。如果 Draw = true，则印章以图形操作符绘制；如果 draw = false，则印章以文本方式绘制。 |
| treat_y_indent_as_base_line | 定义放置文本的坐标原点。<br/>            如果 TreatYIndentAsBaseLine = true（当 Draw = true 时的默认值），YIndent 值将被视为文本基线。<br/>            如果 TreatYIndentAsBaseLine = false（当 Draw = false 时的默认值），YIndent 值将被视为文本的底部（下降线）。 |
| word_wrap | 定义自动换行。如果此属性设置为 true 并指定了 Width 值，文本将被拆分为多行以适应指定的宽度。默认值：false。 |
| justify | 定义文本对齐方式。如果此属性设置为 true，文本的左、右两端将对齐。默认值：false。 |
| scale | 定义文本的缩放。如果此属性设置为 true 并指定了 Width 值，文本将被缩放以适应指定的宽度。 |
| 值 | 获取或设置用于页面印章的字符串值。 |
| text_state | 获取印章的文本属性。详情请参阅 [text_state](/pdf/python-net/aspose.pdf/textstamp/)。 |
| text_alignment | 印章内部文本的对齐方式。 |
| max_row_width | WordWrap 选项的最大行高。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| put(page) | 在页面上添加文本印章。 |
| set_stamp_id(value) | 设置印章 ID。 |
| get_stamp_id() | 返回印章 ID。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

