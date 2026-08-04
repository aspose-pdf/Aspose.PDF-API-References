---
title: "TextState"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示文本的状态"
type: docs
weight: 490
url: /zh/python-net/aspose.pdf.text/textstate/
---

## TextState class

表示文本的状态

TextState 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| TextState() | 创建文本状态对象。 |
| TextState(font_size) | 初始化 TextState 类的新实例。 |
| TextState(foreground_color) | 初始化 TextState 类的新实例。 |
| TextState(foreground_color, font_size) | 初始化 TextState 类的新实例。 |
| TextState(font_family) | 初始化 TextState 类的新实例。 |
| TextState(font_family, bold, italic) | 初始化 TextState 类的新实例。 |
| TextState(font_family, font_size) | 初始化 TextState 类的新实例。 |
## 属性
| 名称 | 描述 |
| :- | :- |
| character_spacing | 获取或设置文本的字符间距。 |
| line_spacing | 获取或设置文本的行间距。 |
| horizontal_scaling | 获取或设置文本的水平缩放。 |
| subscript | 获取或设置文本的下标。 |
| superscript | 获取或设置文本的上标。 |
| word_spacing | 获取或设置文本的字间距。 |
| invisible | 获取或设置文本的不可见性。这基本上反映了 [rendering_mode](/pdf/python-net/aspose.pdf.text/textstate/) 状态，除了一些特殊情况（如剪裁）。 |
| rendering_mode | 获取或设置文本的渲染模式。 |
| font_size | 获取或设置文本的字体大小。 |
| font | 获取或设置文本的字体。 |
| foreground_color | 获取或设置文本的前景颜色。 |
| stroking_color | 获取或设置文本的前景颜色。 |
| underline | 获取或设置文本的下划线，由 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 对象表示 |
| strike_out | 设置文本的删除线，由 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 对象表示 |
| background_color | 设置文本的背景颜色。 |
| font_style | 设置文本的字体样式。 |
| horizontal_alignment | 获取或设置文本的水平对齐方式。 |
| TAB_TAG | 您可以在文本中放置此标签以声明制表符。 |
| TABSTOP_DEFAULT_VALUE | 默认字体空格字符宽度的制表符默认值。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| apply_changes_from(text_state) | 从另一个 textState 应用设置。 |
| measure_string(str) | 测量字符串。 |

### 另请参阅

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

