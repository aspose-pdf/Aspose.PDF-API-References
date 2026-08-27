---
title: "PdfFileSanitization"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示清理和恢复 API。<br/>            如果您无法以其他方式创建/打开文档，请使用它。"
type: docs
weight: 290
url: /zh/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

表示清理和恢复 API。<br/>            如果您无法以其他方式创建/打开文档，请使用它。

PdfFileSanitization 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfFileSanitization() | 初始化 PdfFileSanitization 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| 日志 | 文件保存后，您可以检查对文件所做的操作。 |
| use_trim_top | 允许在 pdf 数据之前删除数据。 |
| use_trim_bottom | 允许在 pdf 数据之后删除数据 |
| use_rebuild_xref_and_trailer | 允许为文档生成新的 xref 和 trailer。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(input_file) | 绑定用于 Sanitize 的 Pdf 文件。 |
| bind_pdf(input_stream) | 绑定用于 Sanitize 的 Pdf 流。 |
| bind_pdf(src_doc) | 初始化外观。 |
| save(output_file) | 将结果 PDF 保存到文件。 |
| save(output_stream) | 将结果 PDF 保存到流。 |
| close() | 关闭外观。 |
| recover() | 恢复文档。<br/>            使用属性进行自定义。 |
| trim_top() | 删除 %PDF 之前的数据。 |
| trim_bottom() | 删除最后的 %%EOF 之后的数据。 |
| rebuild_xref_and_trailer() | 删除带有 trailer 的旧 xref 并创建新的带有 trailer 的 xref。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

