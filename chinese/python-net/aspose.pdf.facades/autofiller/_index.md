---
title: "AutoFiller"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示一个类，用于从数据库或其他数据源接收数据，将其填充到模板 PDF 的设计字段中，最终生成新的 PDF 文件或流。<br/>             它有两种模板文件输入模式：作为流输入或 PDF 文件。<br/>             它有四种输出模式：一个合并流、一个合并文件、多个小流、多个小文件。<br/>             它可以接收包含在 System.Data.DataTable 中的文字数据。"
type: docs
weight: 20
url: /zh/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

表示一个类，用于从数据库或其他数据源接收数据，将其填充到模板 PDF 的设计字段中，最终生成新的 PDF 文件或流。<br/>             它有两种模板文件输入模式：作为流输入或 PDF 文件。<br/>             它有四种输出模式：一个合并流、一个合并文件、多个小流、多个小文件。<br/>             它可以接收包含在 System.Data.DataTable 中的文字数据。

AutoFiller 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| AutoFiller() | 初始化 AutoFiller 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| output_stream | 获取或设置 OutputStream。四种输出模式之一。其经典用例是 Response.OutputStream。<br/>            请参阅在线演示。 |
| output_streams | 获取或设置多个 Output Streams。四种输出模式之一。 |
| input_stream | 获取或设置输入模板流。两种输入模式之一。 |
| input_file_name | 获取或设置输入模板文件。两种输入模式之一。 |
| output_file_name | 获取或设置合并后的大型输出文件。四种输出模式之一。 |
| generating_path | 获取或设置小 PDF 文件的生成路径（如果要生成多个小 PDF 文件）。它与另一个属性 [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName 配合使用。<br/>            四种输出模式之一。 |
| basic_file_name | 获取或设置在生成多个小文件时的基本文件名。生成的文件将类似于 "BasicFileName0","BasicFileName1",...<br/>            它与另一个属性 [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath 配合使用。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| save() | 保存所有 PDF。 |
| save(dest_file) | 保存所有 PDF。 |
| save(dest_stream) | 保存所有 PDF。 |
| bind_pdf(src_file) | 绑定一个 PDF 文件。 |
| bind_pdf(src_stream) | 绑定一个 PDF 文件。 |
| bind_pdf(src_doc) | 绑定一个 PDF 文档。 |
| close() | 关闭对象和输出流。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

