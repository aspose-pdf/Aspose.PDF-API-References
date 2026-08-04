---
title: "RenderingOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示渲染选项。"
type: docs
weight: 1330
url: /zh/python-net/aspose.pdf/renderingoptions/
---

## RenderingOptions class

表示渲染选项。

RenderingOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| RenderingOptions() | 初始化 RenderingOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| barcode_optimization | 获取或设置条形码优化模式。 |
| optimize_dimensions | 获取或设置优化尺寸模式。 |
| system_fonts_native_rendering | 获取或设置系统字体以本机方式渲染的模式。 |
| use_new_imaging_engine | 获取或设置一个标志，以确定是否使用新成像引擎。 |
| width_extra_units | 获取或设置用于在 AppendRectangle 操作符中增大或减小矩形宽度的值。 |
| height_extra_units | 获取或设置用于在 AppendRectangle 操作符中增大或减小矩形宽度的值。 |
| convert_fonts_to_unicode_ttf | 指示所有字体将被转换为 TTF Unicode 版本。这对于兼容性 <br/>             原因以及优化字体使用很有帮助，因为每个新 TTF 字体不会包含源字体的所有符号 <br/>             而仅包含文本中使用的符号。 |
| use_font_hinting | 使用此标志可开启字体微调机制。字体微调是使用数学指令来调整 <br/>            矢量字体显示的过程。在某些情况下，开启此标志可能会解决文本可读性问题。 <br/>            目前，此标志的使用仅对 TTF 字体生效，前提是这些字体在源文档中被使用。 |
| scale_images_to_fit_page_width | 获取或设置用于将页面上所有图像缩放以适应页面宽度的值。 |
| interpolation_high_quality | 获取或设置插值的高质量模式。 |
| max_fonts_cache_size | 字体缓存中的最大字体数量。默认值为 10。 |
| max_symbols_cache_size | 符号缓存中的最大符号数量。默认值为 100。 |
| default_font_name | 获取/设置用于替代缺失字体的默认字体名称。 |
| ignore_resource_font_errors | 获取或设置指示是否忽略与缺少字体相关的错误。<br/>            true - 表示将忽略缺少字体的错误。引用不正确资源的文本段将在处理期间被跳过。<br/>            默认值为 false |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

