---
title: "TeXFragment"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示 TeX 片段。"
type: docs
weight: 1510
url: /zh/python-net/aspose.pdf/texfragment/
---

## TeXFragment class

表示 TeX 片段。

TeXFragment 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| TeXFragment(text) | 初始化 TeXFragment 类的新实例 |
| TeXFragment(text, remove_indents) | 初始化 TeXFragment 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| vertical_alignment | 获取或设置段落的垂直对齐方式 |
| horizontal_alignment | 获取或设置段落的水平对齐方式 |
| margin | 获取或设置段落的外边距（用于 PDF 生成） |
| is_first_paragraph_in_column | 获取或设置一个布尔值，指示此段落是否将在下一列。<br/>            默认值为 false。（用于 PDF 生成） |
| is_kept_with_next | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。<br/>            默认值为 false。（用于 PDF 生成） |
| is_in_new_page | 获取或设置一个布尔值，强制此段落在新页面生成。<br/>            默认值为 false。（用于 PDF 生成） |
| is_in_line_paragraph | 获取或设置段落是否为内联。<br/>            默认值为 false。（用于 PDF 生成） |
| hyperlink | 获取或设置片段超链接（用于 PDF 生成器）。 |
| z_index | 获取或设置一个整数值，指示 graph 的 Z 顺序。ZIndex 较大的 graph <br/>            将放置在 ZIndex 较小的 graph 之上。ZIndex 可以为负数。ZIndex 为负的 graph <br/>            将放置在页面文本的后面。 |
| te_x_load_options_of_instance | 获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 TeXLoadOptions。<br/>请在需要为此实例或其他实例的 LaTeX 导入使用特定设置时使用它<br/>（例如，当此实例或其他实例应使用特定的 BasePath 来导入 LaTeX，或应使用特定的外部资源加载器时）<br/>如果参数为默认值（null），则使用标准的 LaTeX 加载选项。 |
| latex_load_options_of_instance | 获取或设置将在此类实例中用于加载（和渲染）LaTeX 的 TeXLoadOptions。<br/>请在需要为此实例或其他实例的 LaTeX 导入使用特定设置时使用它<br/>（例如，当此实例或其他实例应使用特定的 BasePath 来导入 LaTeX，或应使用特定的外部资源加载器时）<br/>如果参数为默认值（null），则使用标准的 LaTeX 加载选项。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| clone() | 克隆片段。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

