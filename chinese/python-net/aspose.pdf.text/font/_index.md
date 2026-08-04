---
title: "Font"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示字体对象。"
type: docs
weight: 100
url: /zh/python-net/aspose.pdf.text/font/
---

## Font class

表示字体对象。

Font 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| font_name | 获取 [Font](/pdf/python-net/aspose.pdf.text/font/) 对象的字体名称。 |
| decoded_font_name | 有时 PDF 字体（通常是中、日、韩字体）可能具有特定的字体名称。<br/>            该名称是 PDF 字体属性 "BaseFont" 的值，有时该属性<br/>            可能以十六进制形式表示。如果直接读取此名称，可能会呈现为不可读的形式。要获得可读形式，需要按照该字体的特定规则对字体名称进行解码。<br/>            此属性返回解码后的字体名称，因此在遇到不可读的 [font_name](/pdf/python-net/aspose.pdf.text/font/) 时使用它。<br/>            如果属性 [font_name](/pdf/python-net/aspose.pdf.text/font/) 已是可读形式，则此属性与<br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/) 相同，因此在任何需要获取可读字体名称的情况下都可以使用此属性。 |
| base_font | 获取 PDF 字体对象的 BaseFont 值，也称为字体的 PostScript 名称。 |
| is_embedded | 获取或设置指示字体是否已嵌入的值。<br/>            基于 IFont 的字体将自动进行子集化并嵌入 |
| is_subset | 获取或设置指示字体是否为子集的值。<br/>             基于 IFont 的字体将自动进行子集化并嵌入 |
| is_accessible | 获取指示字体是否已在系统中存在（已安装）。 |
| font_options | 用于调节字体行为的有用属性 |
## 方法
| 名称 | 描述 |
| :- | :- |
| get_last_font_embedding_error() | 此方法的目标是返回错误描述，如果尝试<br/>            嵌入字体失败。若没有错误情况，则返回空字符串。 |
| save(stream) | 将字体保存到流中。<br/>            请注意，字体被保存为中间的 TTF 格式，仅用于原始文档的转换副本。<br/>            该字体文件不应在原始文档上下文之外使用。 |
| measure_string(str, font_size) | 测量字符串。 |

### 另请参阅

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

