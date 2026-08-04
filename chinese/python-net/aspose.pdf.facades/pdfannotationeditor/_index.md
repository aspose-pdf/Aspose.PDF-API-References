---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示一个用于处理 PDF 文档注释（评论）的类。"
type: docs
weight: 170
url: /zh/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

表示一个用于处理 PDF 文档注释（评论）的类。

PdfAnnotationEditor 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfAnnotationEditor() | 初始化新的 [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/) 对象。 |
| PdfAnnotationEditor(document) | 初始化 PdfAnnotationEditor 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_file) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_stream) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save(dest_file) | 将 PDF 文档保存到指定文件。 |
| save(dest_stream) | 将 PDF 文档保存到指定流。 |
| import_annotations_from_xfdf(xfdf_file) | 从 XFDF 文件导入所有批注。 |
| import_annotations_from_xfdf(xfdf_stream) | 从 XFDF 数据流导入所有批注。 |
| import_annotation_from_xfdf(xfdf_file) | 从 XFDF 文件导入所有批注。 |
| import_annotation_from_xfdf(xfdf_file, annot_type) | 从 XFDF 文件导入指定的批注。 |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | 从 XFDF 数据流导入指定的批注。 |
| import_annotation_from_xfdf(xfdf_stream) | 从 XFDF 数据流导入指定的批注。 |
| import_annotations(annot_file, annot_type) | 从其他 PDF 文档数组中将指定的批注导入文档。 |
| import_annotations(annot_file) | 从其他 PDF 文档数组中将指定的批注导入文档。 |
| import_annotations(annot_file_stream, annot_type) | 从其他 PDF 文档流数组中将指定的批注导入文档。 |
| import_annotations(annot_file_stream) | 从其他 PDF 文档流数组中将指定的批注导入文档。 |
| flattening_annotations() | 将文档中的所有批注扁平化。 |
| flattening_annotations(flatten_settings) | 将文档中的所有批注扁平化。 |
| flattening_annotations(start, end, annot_type) | 将指定类型的批注扁平化。 |
| delete_annotations() | 删除文档中的所有批注。 |
| delete_annotations(annot_type) | 删除文档中指定类型的所有批注。 |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | 将指定批注类型的内容导出为 XFDF。 |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | 将指定批注类型的内容导出为 XFDF。 |
| extract_annotations(start, end, annot_types) | 获取指定类型批注的列表。 |
| extract_annotations(start, end, annot_types) | 获取指定类型批注的列表。 |
| close() | 释放与当前外观关联的所有资源。 |
| modify_annotations_author(start, end, src_author, des_author) | 修改指定页范围内批注的作者。 |
| delete_annotation(annot_name) | 删除文档中指定类型的所有批注。 |
| export_annotations_to_xfdf(xml_output_stream) | 将批注导出到流。 |
| modify_annotations(start, end, annotation) | 修改指定页范围内指定类型的批注。<br/>            支持修改以下批注属性：Modified、Title、Contents、Color、Subject 和 Open。 |
| redact_area(page_index, rect, color) | 在指定页面上遮盖区域。所有内容均被删除。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

